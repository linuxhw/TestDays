Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 102315

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-MA69VM-S2                | [5aa8ec8c7e](https://linux-hardware.org/?probe=5aa8ec8c7e) | Apr 17, 2022 |
| MSI           | H510M PRO                   | [a9ce7c295a](https://linux-hardware.org/?probe=a9ce7c295a) | Apr 17, 2022 |
| ASUSTek       | PRIME B550M-A               | [72a48fb5d6](https://linux-hardware.org/?probe=72a48fb5d6) | Apr 17, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [8f8f3b74e6](https://linux-hardware.org/?probe=8f8f3b74e6) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| ASUSTek       | H110M-A/M.2                 | [1cfc273a11](https://linux-hardware.org/?probe=1cfc273a11) | Apr 16, 2022 |
| HP            | 1497                        | [6d2caeac34](https://linux-hardware.org/?probe=6d2caeac34) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| MSI           | MS-7438 100                 | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | [1ed579d3d1](https://linux-hardware.org/?probe=1ed579d3d1) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | [dae8a4db62](https://linux-hardware.org/?probe=dae8a4db62) | Apr 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f20c2c3665](https://linux-hardware.org/?probe=f20c2c3665) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| AZW           | U59                         | [fc7e5f0c5c](https://linux-hardware.org/?probe=fc7e5f0c5c) | Apr 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [a016ec1bce](https://linux-hardware.org/?probe=a016ec1bce) | Apr 16, 2022 |
| MSI           | A320M PRO-M2 V2             | [7a3fa3e4a4](https://linux-hardware.org/?probe=7a3fa3e4a4) | Apr 16, 2022 |
| AZW           | U59                         | [377d280037](https://linux-hardware.org/?probe=377d280037) | Apr 16, 2022 |
| Dell          | 02YYK5 A01                  | [f2e4d7052d](https://linux-hardware.org/?probe=f2e4d7052d) | Apr 16, 2022 |
| Apple         | Mac-F221BEC8                | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| ASUSTek       | P8B75-M                     | [861c47b139](https://linux-hardware.org/?probe=861c47b139) | Apr 16, 2022 |
| ASUSTek       | H61M-K                      | [c2a4357527](https://linux-hardware.org/?probe=c2a4357527) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | [10ad704b03](https://linux-hardware.org/?probe=10ad704b03) | Apr 16, 2022 |
| ASUSTek       | P6T DELUXE                  | [1ceaddfc92](https://linux-hardware.org/?probe=1ceaddfc92) | Apr 16, 2022 |
| ASUSTek       | D540MA-C                    | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Gigabyte      | GA-990FX-GAMING             | [dc1e145cf3](https://linux-hardware.org/?probe=dc1e145cf3) | Apr 16, 2022 |
| Gigabyte      | H61M-S1                     | [dfd89c6a60](https://linux-hardware.org/?probe=dfd89c6a60) | Apr 16, 2022 |
| ASUSTek       | H61M-K                      | [690867d18c](https://linux-hardware.org/?probe=690867d18c) | Apr 16, 2022 |
| ASRock        | H110M-DVS R2.0              | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| ASUSTek       | A68HM-PLUS                  | [0bfefd6499](https://linux-hardware.org/?probe=0bfefd6499) | Apr 16, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7efbdedc5f](https://linux-hardware.org/?probe=7efbdedc5f) | Apr 16, 2022 |
| MSI           | B560M-A PRO                 | [c394557d17](https://linux-hardware.org/?probe=c394557d17) | Apr 16, 2022 |
| Dell          | 08WKV3 A00                  | [f3afe20dae](https://linux-hardware.org/?probe=f3afe20dae) | Apr 16, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [9a5d59c375](https://linux-hardware.org/?probe=9a5d59c375) | Apr 16, 2022 |
| Medion        | H110H4-EM                   | [b1fcc5abcf](https://linux-hardware.org/?probe=b1fcc5abcf) | Apr 16, 2022 |
| ASUSTek       | PRIME A320M-K               | [b5094d96cc](https://linux-hardware.org/?probe=b5094d96cc) | Apr 16, 2022 |
| ASRock        | B560M Pro4                  | [2fe297dc4b](https://linux-hardware.org/?probe=2fe297dc4b) | Apr 16, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [3e3e2fd22f](https://linux-hardware.org/?probe=3e3e2fd22f) | Apr 16, 2022 |
| ASUSTek       | P7H55                       | [d619f35fb8](https://linux-hardware.org/?probe=d619f35fb8) | Apr 16, 2022 |
| ASUSTek       | Maximus VI HERO             | [923a82e975](https://linux-hardware.org/?probe=923a82e975) | Apr 16, 2022 |
| Dell          | 0Y5DDC A00                  | [c9510b64e8](https://linux-hardware.org/?probe=c9510b64e8) | Apr 16, 2022 |
| MSI           | H110M PRO-VD                | [2fc240d0aa](https://linux-hardware.org/?probe=2fc240d0aa) | Apr 16, 2022 |
| ASUSTek       | A88XM-A                     | [427335d90c](https://linux-hardware.org/?probe=427335d90c) | Apr 16, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [65b68d5bb9](https://linux-hardware.org/?probe=65b68d5bb9) | Apr 16, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| Dell          | 06D7TR A01                  | [9a21a6c0f4](https://linux-hardware.org/?probe=9a21a6c0f4) | Apr 16, 2022 |
| ASUSTek       | P5VD2-MX                    | [57fec52891](https://linux-hardware.org/?probe=57fec52891) | Apr 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [7afe8794c5](https://linux-hardware.org/?probe=7afe8794c5) | Apr 16, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [1959eab901](https://linux-hardware.org/?probe=1959eab901) | Apr 16, 2022 |
| ASRock        | P67 Pro3                    | [2f98f9cdee](https://linux-hardware.org/?probe=2f98f9cdee) | Apr 16, 2022 |
| Gigabyte      | M61PME-S2P                  | [cb64383c99](https://linux-hardware.org/?probe=cb64383c99) | Apr 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| HP            | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [f83ee2cc17](https://linux-hardware.org/?probe=f83ee2cc17) | Apr 16, 2022 |
| MSI           | Z270-A PRO                  | [55c72a253b](https://linux-hardware.org/?probe=55c72a253b) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [eef3c69fcd](https://linux-hardware.org/?probe=eef3c69fcd) | Apr 16, 2022 |
| ASUSTek       | Z97-P                       | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| HP            | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| Dell          | 0DN075                      | [05bd1b50f1](https://linux-hardware.org/?probe=05bd1b50f1) | Apr 16, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [0a7ccf21d6](https://linux-hardware.org/?probe=0a7ccf21d6) | Apr 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [6a9e2b3174](https://linux-hardware.org/?probe=6a9e2b3174) | Apr 16, 2022 |
| Gigabyte      | H110M-H-CF                  | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| Supermicro    | H8QG6                       | [060f1e3d34](https://linux-hardware.org/?probe=060f1e3d34) | Apr 16, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [7c4882a4ef](https://linux-hardware.org/?probe=7c4882a4ef) | Apr 16, 2022 |
| Dell          | 0VYXHD A00                  | [4280de633d](https://linux-hardware.org/?probe=4280de633d) | Apr 16, 2022 |
| Gigabyte      | GA-870A-UD3                 | [2bc3cb42bb](https://linux-hardware.org/?probe=2bc3cb42bb) | Apr 16, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [a186aa76d5](https://linux-hardware.org/?probe=a186aa76d5) | Apr 16, 2022 |
| ASUSTek       | P8H67-M LX                  | [65116c3b59](https://linux-hardware.org/?probe=65116c3b59) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [0d1f53febb](https://linux-hardware.org/?probe=0d1f53febb) | Apr 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [b0a5b307c9](https://linux-hardware.org/?probe=b0a5b307c9) | Apr 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3d894ef45c](https://linux-hardware.org/?probe=3d894ef45c) | Apr 16, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [5971999c12](https://linux-hardware.org/?probe=5971999c12) | Apr 16, 2022 |
| Dell          | 0VHXCD A03                  | [290987223e](https://linux-hardware.org/?probe=290987223e) | Apr 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | [6f358d55e7](https://linux-hardware.org/?probe=6f358d55e7) | Apr 16, 2022 |
| ASUSTek       | PRIME H410M-R               | [c8146beb84](https://linux-hardware.org/?probe=c8146beb84) | Apr 16, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [9ba73648b1](https://linux-hardware.org/?probe=9ba73648b1) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3                    | [1785652200](https://linux-hardware.org/?probe=1785652200) | Apr 16, 2022 |
| Gigabyte      | B450M DS3H V2               | [b097841482](https://linux-hardware.org/?probe=b097841482) | Apr 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0ad6471ecf](https://linux-hardware.org/?probe=0ad6471ecf) | Apr 16, 2022 |
| Gigabyte      | X99P-SLI-CF                 | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | [44b99daa8e](https://linux-hardware.org/?probe=44b99daa8e) | Apr 16, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0169381aeb](https://linux-hardware.org/?probe=0169381aeb) | Apr 15, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [474bb81b18](https://linux-hardware.org/?probe=474bb81b18) | Apr 15, 2022 |
| MSI           | 2AE0                        | [b1059198e0](https://linux-hardware.org/?probe=b1059198e0) | Apr 15, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Gigabyte      | F2A68HM-H                   | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [f6a1a50a75](https://linux-hardware.org/?probe=f6a1a50a75) | Apr 15, 2022 |
| Gigabyte      | EP31-DS3L                   | [13324a7aea](https://linux-hardware.org/?probe=13324a7aea) | Apr 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c8161370ea](https://linux-hardware.org/?probe=c8161370ea) | Apr 15, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [d7f72a830c](https://linux-hardware.org/?probe=d7f72a830c) | Apr 15, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| ASUSTek       | M5A78L/USB3                 | [48deb234f0](https://linux-hardware.org/?probe=48deb234f0) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [90486ad164](https://linux-hardware.org/?probe=90486ad164) | Apr 15, 2022 |
| Unknown       | HX90                        | [a9b1d5a579](https://linux-hardware.org/?probe=a9b1d5a579) | Apr 15, 2022 |
| ASUSTek       | M5A78L/USB3                 | [bb302cfbbd](https://linux-hardware.org/?probe=bb302cfbbd) | Apr 15, 2022 |
| ASUSTek       | B150-PRO                    | [1ebe5f0e99](https://linux-hardware.org/?probe=1ebe5f0e99) | Apr 15, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [623024de22](https://linux-hardware.org/?probe=623024de22) | Apr 15, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [c3d8900f58](https://linux-hardware.org/?probe=c3d8900f58) | Apr 15, 2022 |
| Gigabyte      | EP31-DS3L                   | [a0a68f0980](https://linux-hardware.org/?probe=a0a68f0980) | Apr 15, 2022 |
| MSI           | 990FXA-GD80                 | [391705d3c1](https://linux-hardware.org/?probe=391705d3c1) | Apr 15, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [3e7ec0a1bb](https://linux-hardware.org/?probe=3e7ec0a1bb) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [a01b211bb4](https://linux-hardware.org/?probe=a01b211bb4) | Apr 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [9d2aeecf05](https://linux-hardware.org/?probe=9d2aeecf05) | Apr 15, 2022 |
| ASUSTek       | M2NPV-MX                    | [8192abd2c4](https://linux-hardware.org/?probe=8192abd2c4) | Apr 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [83edb7e224](https://linux-hardware.org/?probe=83edb7e224) | Apr 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [f149542bb7](https://linux-hardware.org/?probe=f149542bb7) | Apr 15, 2022 |
| Gigabyte      | Z68P-DS3                    | [b9913d6c6b](https://linux-hardware.org/?probe=b9913d6c6b) | Apr 15, 2022 |
| ASRock        | ConRoe1333-D667             | [d2bba273a0](https://linux-hardware.org/?probe=d2bba273a0) | Apr 15, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [c58a4b9726](https://linux-hardware.org/?probe=c58a4b9726) | Apr 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | [bdc8f9b39e](https://linux-hardware.org/?probe=bdc8f9b39e) | Apr 15, 2022 |
| Gigabyte      | G41MT-D3V                   | [b1944bf89e](https://linux-hardware.org/?probe=b1944bf89e) | Apr 15, 2022 |
| ASRock        | ConRoe1333-D667             | [24ba95b6ea](https://linux-hardware.org/?probe=24ba95b6ea) | Apr 15, 2022 |
| ASRock        | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| HP            | 2129                        | [be64efcffd](https://linux-hardware.org/?probe=be64efcffd) | Apr 15, 2022 |
| ASRock        | H110M-DGS R3.0              | [aa36281de8](https://linux-hardware.org/?probe=aa36281de8) | Apr 15, 2022 |
| ASUSTek       | GRYPHON Z87                 | [557390f9cf](https://linux-hardware.org/?probe=557390f9cf) | Apr 15, 2022 |
| Gigabyte      | H370M DS3H-CF               | [c3eadb27ad](https://linux-hardware.org/?probe=c3eadb27ad) | Apr 15, 2022 |
| Lenovo        | SDK0J40700 WIN              | [142a0092f1](https://linux-hardware.org/?probe=142a0092f1) | Apr 15, 2022 |
| Dell          | 0HN7XN A01                  | [5a9ba12201](https://linux-hardware.org/?probe=5a9ba12201) | Apr 15, 2022 |
| HP            | 21B4 A01                    | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Gigabyte      | G41MT-D3V                   | [19b11d696f](https://linux-hardware.org/?probe=19b11d696f) | Apr 15, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [eae3d7f803](https://linux-hardware.org/?probe=eae3d7f803) | Apr 15, 2022 |
| BESSTAR Te... | TL50                        | [28dba12634](https://linux-hardware.org/?probe=28dba12634) | Apr 15, 2022 |
| MSI           | G31TM-P35                   | [f5aba83efe](https://linux-hardware.org/?probe=f5aba83efe) | Apr 15, 2022 |
| ASRock        | 960GM-GS3 FX                | [4cf37abd8d](https://linux-hardware.org/?probe=4cf37abd8d) | Apr 15, 2022 |
| ASUSTek       | P8Z77-V LX                  | [997b338c67](https://linux-hardware.org/?probe=997b338c67) | Apr 15, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| Dell          | 0M5DCD A00                  | [8da74b67c8](https://linux-hardware.org/?probe=8da74b67c8) | Apr 15, 2022 |
| Dell          | 0C522T A00                  | [593941cc0a](https://linux-hardware.org/?probe=593941cc0a) | Apr 15, 2022 |
| Dell          | 0P01GV A03                  | [7d156875bb](https://linux-hardware.org/?probe=7d156875bb) | Apr 15, 2022 |
| MSI           | MAG B460M MORTAR            | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| Medion        | MS-7728                     | [443a5ff3dd](https://linux-hardware.org/?probe=443a5ff3dd) | Apr 15, 2022 |
| HP            | 2B2C                        | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [0a8d0e5302](https://linux-hardware.org/?probe=0a8d0e5302) | Apr 15, 2022 |
| ASRock        | G41M-VGS3                   | [62f424c896](https://linux-hardware.org/?probe=62f424c896) | Apr 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | [8f490a29f3](https://linux-hardware.org/?probe=8f490a29f3) | Apr 15, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [4a93a73c74](https://linux-hardware.org/?probe=4a93a73c74) | Apr 15, 2022 |
| Unknown       | Unknown                     | [c9c0498d72](https://linux-hardware.org/?probe=c9c0498d72) | Apr 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d14605acc1](https://linux-hardware.org/?probe=d14605acc1) | Apr 15, 2022 |
| Unknown       | Unknown                     | [0735862439](https://linux-hardware.org/?probe=0735862439) | Apr 15, 2022 |
| Foxconn       | 2ABF                        | [8994d0ea9f](https://linux-hardware.org/?probe=8994d0ea9f) | Apr 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [bafa818dea](https://linux-hardware.org/?probe=bafa818dea) | Apr 15, 2022 |
| Gigabyte      | EP45-UD3P                   | [973d2cc2f1](https://linux-hardware.org/?probe=973d2cc2f1) | Apr 15, 2022 |
| MSI           | X470 GAMING PLUS            | [72af1b2afe](https://linux-hardware.org/?probe=72af1b2afe) | Apr 15, 2022 |
| MSI           | Z87-GD65 GAMING             | [8c57fd797b](https://linux-hardware.org/?probe=8c57fd797b) | Apr 15, 2022 |
| Medion        | H110H4-EM                   | [d4c3d27956](https://linux-hardware.org/?probe=d4c3d27956) | Apr 15, 2022 |
| Dell          | 06X1TJ A00                  | [d92d515d6b](https://linux-hardware.org/?probe=d92d515d6b) | Apr 15, 2022 |
| Dell          | 06X1TJ A00                  | [32b40d296d](https://linux-hardware.org/?probe=32b40d296d) | Apr 15, 2022 |
| ASRock        | H110M-DGS                   | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [96faf32841](https://linux-hardware.org/?probe=96faf32841) | Apr 15, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [36d5c02824](https://linux-hardware.org/?probe=36d5c02824) | Apr 15, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [0b5246a205](https://linux-hardware.org/?probe=0b5246a205) | Apr 15, 2022 |
| MSI           | B85I GAMING                 | [be865001b9](https://linux-hardware.org/?probe=be865001b9) | Apr 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [14f5389e9e](https://linux-hardware.org/?probe=14f5389e9e) | Apr 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [90559719b1](https://linux-hardware.org/?probe=90559719b1) | Apr 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [7cc9a1bbb7](https://linux-hardware.org/?probe=7cc9a1bbb7) | Apr 15, 2022 |
| Gigabyte      | B85-HD3                     | [89fb08092b](https://linux-hardware.org/?probe=89fb08092b) | Apr 15, 2022 |
| Biostar       | G31M+                       | [bbc349a405](https://linux-hardware.org/?probe=bbc349a405) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | [76a80df275](https://linux-hardware.org/?probe=76a80df275) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [edca3eae97](https://linux-hardware.org/?probe=edca3eae97) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | [74b8687993](https://linux-hardware.org/?probe=74b8687993) | Apr 15, 2022 |
| ASUSTek       | P5QL/EPU                    | [d7c378ac40](https://linux-hardware.org/?probe=d7c378ac40) | Apr 15, 2022 |
| Intel         | DQ67EP AAG12529-307         | [8e345bbb6a](https://linux-hardware.org/?probe=8e345bbb6a) | Apr 15, 2022 |
| MSI           | 790FX-GD70                  | [0a8776ac60](https://linux-hardware.org/?probe=0a8776ac60) | Apr 15, 2022 |
| Dell          | 00V62H A00                  | [499a00bcf8](https://linux-hardware.org/?probe=499a00bcf8) | Apr 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [2aac95b872](https://linux-hardware.org/?probe=2aac95b872) | Apr 15, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| ASUSTek       | A68HM-PLUS                  | [f52ef2faf2](https://linux-hardware.org/?probe=f52ef2faf2) | Apr 15, 2022 |
| Unknown       | Unknown                     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [172be13d6d](https://linux-hardware.org/?probe=172be13d6d) | Apr 15, 2022 |
| ASUSTek       | P7P55D LE                   | [381477f3e6](https://linux-hardware.org/?probe=381477f3e6) | Apr 15, 2022 |
| Dell          | 0200DY A00                  | [1b0ad4ce13](https://linux-hardware.org/?probe=1b0ad4ce13) | Apr 14, 2022 |
| Unknown       | Unknown                     | [6476542bc7](https://linux-hardware.org/?probe=6476542bc7) | Apr 14, 2022 |
| Gigabyte      | Z77X-D3H                    | [da67065e13](https://linux-hardware.org/?probe=da67065e13) | Apr 14, 2022 |
| GALAX         | A320M G10g                  | [958fc1bf94](https://linux-hardware.org/?probe=958fc1bf94) | Apr 14, 2022 |
| Huanan        | X99-AD3 V4.0                | [186bccefad](https://linux-hardware.org/?probe=186bccefad) | Apr 14, 2022 |
| MSI           | Z390-A PRO                  | [1e26bb146f](https://linux-hardware.org/?probe=1e26bb146f) | Apr 14, 2022 |
| Itautec       | ST 4262 ST-4262 Padrao 0... | [1dd8e2f31b](https://linux-hardware.org/?probe=1dd8e2f31b) | Apr 14, 2022 |
| Dell          | 0NW6H5 A00                  | [dd5d897f4c](https://linux-hardware.org/?probe=dd5d897f4c) | Apr 14, 2022 |
| MSI           | H81M-P33                    | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| ASUSTek       | Z97-K                       | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| ASUSTek       | P5G41T-M LX                 | [3a0df7b88f](https://linux-hardware.org/?probe=3a0df7b88f) | Apr 14, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | [37e172faec](https://linux-hardware.org/?probe=37e172faec) | Apr 14, 2022 |
| Dell          | 0WMJ54 A01                  | [d113301081](https://linux-hardware.org/?probe=d113301081) | Apr 14, 2022 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [72b9c04a51](https://linux-hardware.org/?probe=72b9c04a51) | Apr 14, 2022 |
| ASUSTek       | M4A78 PRO                   | [9ed3f59682](https://linux-hardware.org/?probe=9ed3f59682) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [0bd7facf9b](https://linux-hardware.org/?probe=0bd7facf9b) | Apr 14, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [c8afb3fce8](https://linux-hardware.org/?probe=c8afb3fce8) | Apr 14, 2022 |
| Gigabyte      | H61MS                       | [84e8094305](https://linux-hardware.org/?probe=84e8094305) | Apr 14, 2022 |
| ASUSTek       | Z97-K/USB                   | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [247cd43da9](https://linux-hardware.org/?probe=247cd43da9) | Apr 14, 2022 |
| HP            | 21EF                        | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| Dell          | 0YR541 A01                  | [f206c3667e](https://linux-hardware.org/?probe=f206c3667e) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | [17622a538e](https://linux-hardware.org/?probe=17622a538e) | Apr 14, 2022 |
| HP            | 0A54h                       | [11c5e77be7](https://linux-hardware.org/?probe=11c5e77be7) | Apr 14, 2022 |
| NZXT          | N7 B550                     | [71e92a4807](https://linux-hardware.org/?probe=71e92a4807) | Apr 14, 2022 |
| MSI           | A68HM-E33 V2                | [9f77473319](https://linux-hardware.org/?probe=9f77473319) | Apr 14, 2022 |
| Unknown       | Unknown                     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [4021615a20](https://linux-hardware.org/?probe=4021615a20) | Apr 14, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [6bc3ced902](https://linux-hardware.org/?probe=6bc3ced902) | Apr 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b30795783f](https://linux-hardware.org/?probe=b30795783f) | Apr 14, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [abe538f1ed](https://linux-hardware.org/?probe=abe538f1ed) | Apr 14, 2022 |
| MSI           | Z370-A PRO                  | [d23bd1d06f](https://linux-hardware.org/?probe=d23bd1d06f) | Apr 14, 2022 |
| HP            | 8298                        | [a9796ddd8d](https://linux-hardware.org/?probe=a9796ddd8d) | Apr 14, 2022 |
| BESSTAR Te... | HM80                        | [80b368187a](https://linux-hardware.org/?probe=80b368187a) | Apr 14, 2022 |
| MSI           | Z390-A PRO                  | [a642b9ec3a](https://linux-hardware.org/?probe=a642b9ec3a) | Apr 14, 2022 |
| Pegatron      | 2AD5                        | [e172be90b8](https://linux-hardware.org/?probe=e172be90b8) | Apr 14, 2022 |
| MSI           | B250M MORTAR                | [8bf9715804](https://linux-hardware.org/?probe=8bf9715804) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [83dda83cdf](https://linux-hardware.org/?probe=83dda83cdf) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [92eaa72b3c](https://linux-hardware.org/?probe=92eaa72b3c) | Apr 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| HP            | 3048h                       | [2d19799047](https://linux-hardware.org/?probe=2d19799047) | Apr 14, 2022 |
| Lenovo        | 3098 NOK                    | [c5a4b14cc3](https://linux-hardware.org/?probe=c5a4b14cc3) | Apr 14, 2022 |
| ASUSTek       | F2A85-V                     | [6200a8f946](https://linux-hardware.org/?probe=6200a8f946) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [843c3d4758](https://linux-hardware.org/?probe=843c3d4758) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | [a7da4b6ee0](https://linux-hardware.org/?probe=a7da4b6ee0) | Apr 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [c372810f3f](https://linux-hardware.org/?probe=c372810f3f) | Apr 14, 2022 |
| Lenovo        | 3098 NOK                    | [45b5664eb1](https://linux-hardware.org/?probe=45b5664eb1) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | [a0ab75ee00](https://linux-hardware.org/?probe=a0ab75ee00) | Apr 14, 2022 |
| ASUSTek       | PRIME X570-P                | [57a3a5a999](https://linux-hardware.org/?probe=57a3a5a999) | Apr 14, 2022 |
| Fujitsu       | D3434-S2 S26361-D3434-S2    | [7ff488cc8d](https://linux-hardware.org/?probe=7ff488cc8d) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [e1b00199f8](https://linux-hardware.org/?probe=e1b00199f8) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| ASUSTek       | PRIME X470-PRO              | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| ASRock        | TRX40 Taichi                | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| MSI           | A68HM-P33                   | [8c395556de](https://linux-hardware.org/?probe=8c395556de) | Apr 14, 2022 |
| Biostar       | H61MHV2                     | [e05349d6a0](https://linux-hardware.org/?probe=e05349d6a0) | Apr 14, 2022 |
| ASUSTek       | PRIME X570-P                | [f9b71f206c](https://linux-hardware.org/?probe=f9b71f206c) | Apr 14, 2022 |
| Gigabyte      | Z270P-D3-CF                 | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | Z390 UD                     | [5f4832051e](https://linux-hardware.org/?probe=5f4832051e) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | [bbd732b5ca](https://linux-hardware.org/?probe=bbd732b5ca) | Apr 14, 2022 |
| MSI           | MEG X570 GODLIKE            | [184356c1d7](https://linux-hardware.org/?probe=184356c1d7) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f28318e17b](https://linux-hardware.org/?probe=f28318e17b) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| ASRock        | B250 Pro4                   | [cb77fb75b5](https://linux-hardware.org/?probe=cb77fb75b5) | Apr 14, 2022 |
| Dell          | 04PT3G A00                  | [a10754ebca](https://linux-hardware.org/?probe=a10754ebca) | Apr 14, 2022 |
| Gigabyte      | B85M-D3H                    | [a0c2314e31](https://linux-hardware.org/?probe=a0c2314e31) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| MSI           | Z97 PC Mate                 | [930c18b320](https://linux-hardware.org/?probe=930c18b320) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASRock        | AB350 Pro4                  | [137e25f240](https://linux-hardware.org/?probe=137e25f240) | Apr 14, 2022 |
| HP            | 158B                        | [01b455c74a](https://linux-hardware.org/?probe=01b455c74a) | Apr 14, 2022 |
| Dell          | 0H7TGR A00                  | [70bdc97d85](https://linux-hardware.org/?probe=70bdc97d85) | Apr 14, 2022 |
| Gigabyte      | EP45-DS3L                   | [4727ba6ee4](https://linux-hardware.org/?probe=4727ba6ee4) | Apr 14, 2022 |
| Dell          | 0773VG A00                  | [3f0d544715](https://linux-hardware.org/?probe=3f0d544715) | Apr 14, 2022 |
| Foxconn       | 2AB1                        | [0276364302](https://linux-hardware.org/?probe=0276364302) | Apr 14, 2022 |
| MSI           | X79A-GD45 Plus              | [fd93542a14](https://linux-hardware.org/?probe=fd93542a14) | Apr 14, 2022 |
| MSI           | MEG X570 GODLIKE            | [b7df514e20](https://linux-hardware.org/?probe=b7df514e20) | Apr 14, 2022 |
| Foxconn       | 2AB1                        | [a816c79e4e](https://linux-hardware.org/?probe=a816c79e4e) | Apr 14, 2022 |
| Dell          | 0D24M8 A01                  | [fe4bb32aa1](https://linux-hardware.org/?probe=fe4bb32aa1) | Apr 14, 2022 |
| Gigabyte      | J1900M-D2P                  | [794fbc68d8](https://linux-hardware.org/?probe=794fbc68d8) | Apr 14, 2022 |
| Dell          | 014GRG A00                  | [1783efe96b](https://linux-hardware.org/?probe=1783efe96b) | Apr 14, 2022 |
| HP            | ProLiant ML330 G6           | [a62736690a](https://linux-hardware.org/?probe=a62736690a) | Apr 14, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [43aa5ccd47](https://linux-hardware.org/?probe=43aa5ccd47) | Apr 14, 2022 |
| ASUSTek       | PRO H410M-C                 | [6d4e35a28f](https://linux-hardware.org/?probe=6d4e35a28f) | Apr 14, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5f49d4d7d8](https://linux-hardware.org/?probe=5f49d4d7d8) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| ASUSTek       | P8H67-M                     | [ca7dd7880b](https://linux-hardware.org/?probe=ca7dd7880b) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [5ec598483e](https://linux-hardware.org/?probe=5ec598483e) | Apr 14, 2022 |
| ASUSTek       | Crosshair V Formula         | [3b66db6997](https://linux-hardware.org/?probe=3b66db6997) | Apr 14, 2022 |
| Unknown       | Unknown                     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| MSI           | B550-A PRO                  | [d0933b6a76](https://linux-hardware.org/?probe=d0933b6a76) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| ASRock        | AB350M                      | [f79bfabcf5](https://linux-hardware.org/?probe=f79bfabcf5) | Apr 14, 2022 |
| ASUSTek       | H61M-K                      | [b8da99fd26](https://linux-hardware.org/?probe=b8da99fd26) | Apr 14, 2022 |
| MSI           | 970A-G43 PLUS               | [9200891771](https://linux-hardware.org/?probe=9200891771) | Apr 14, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Biostar       | H61MLV2                     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| Dell          | 0D28YY A02                  | [c1ff26008f](https://linux-hardware.org/?probe=c1ff26008f) | Apr 14, 2022 |
| Dell          | 0GN6JF A01                  | [c215aa8e06](https://linux-hardware.org/?probe=c215aa8e06) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2a5f0afcc8](https://linux-hardware.org/?probe=2a5f0afcc8) | Apr 14, 2022 |
| Dell          | 0Y2MRG A00                  | [47f495eda5](https://linux-hardware.org/?probe=47f495eda5) | Apr 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a5c9b7fc78](https://linux-hardware.org/?probe=a5c9b7fc78) | Apr 14, 2022 |
| ASUSTek       | X79-DELUXE                  | [77d75fd5b2](https://linux-hardware.org/?probe=77d75fd5b2) | Apr 14, 2022 |
| MSI           | Z370-A PRO                  | [4296dc030e](https://linux-hardware.org/?probe=4296dc030e) | Apr 14, 2022 |
| MSI           | X370 KRAIT GAMING           | [26be53ebd1](https://linux-hardware.org/?probe=26be53ebd1) | Apr 14, 2022 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [d00bde2a05](https://linux-hardware.org/?probe=d00bde2a05) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7e080e5205](https://linux-hardware.org/?probe=7e080e5205) | Apr 14, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [191880e24b](https://linux-hardware.org/?probe=191880e24b) | Apr 14, 2022 |
| MSI           | MEG B550 UNIFY              | [8ebb61ef39](https://linux-hardware.org/?probe=8ebb61ef39) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [91a7810a37](https://linux-hardware.org/?probe=91a7810a37) | Apr 14, 2022 |
| ASUSTek       | M4A78T-E                    | [3cbf78454e](https://linux-hardware.org/?probe=3cbf78454e) | Apr 14, 2022 |
| Gigabyte      | B75M-D3P                    | [cfb6502298](https://linux-hardware.org/?probe=cfb6502298) | Apr 14, 2022 |
| MSI           | H110M ECO                   | [398ba68d9f](https://linux-hardware.org/?probe=398ba68d9f) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [dba38dc289](https://linux-hardware.org/?probe=dba38dc289) | Apr 13, 2022 |
| Gigabyte      | Z590 VISION D               | [4bde7cc5cd](https://linux-hardware.org/?probe=4bde7cc5cd) | Apr 13, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [0f449aecbc](https://linux-hardware.org/?probe=0f449aecbc) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [656e8c50dd](https://linux-hardware.org/?probe=656e8c50dd) | Apr 13, 2022 |
| ASUSTek       | PRIME B550M-A               | [44dd6e1190](https://linux-hardware.org/?probe=44dd6e1190) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [cf0c239670](https://linux-hardware.org/?probe=cf0c239670) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1a7a8bf92e](https://linux-hardware.org/?probe=1a7a8bf92e) | Apr 13, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| MSI           | B150M PRO-VD D3             | [84bd94d672](https://linux-hardware.org/?probe=84bd94d672) | Apr 13, 2022 |
| ASUSTek       | P8H77-M                     | [a5a366f7e7](https://linux-hardware.org/?probe=a5a366f7e7) | Apr 13, 2022 |
| HP            | 18E5                        | [3b4f9e8525](https://linux-hardware.org/?probe=3b4f9e8525) | Apr 13, 2022 |
| ASRock        | A320M-ITX                   | [eaf6bbd74e](https://linux-hardware.org/?probe=eaf6bbd74e) | Apr 13, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [76bb4d06e3](https://linux-hardware.org/?probe=76bb4d06e3) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8a5920ae1a](https://linux-hardware.org/?probe=8a5920ae1a) | Apr 13, 2022 |
| MSI           | H81M-E33                    | [460099f77f](https://linux-hardware.org/?probe=460099f77f) | Apr 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI           | B450-A PRO MAX              | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5d45d7b3f7](https://linux-hardware.org/?probe=5d45d7b3f7) | Apr 13, 2022 |
| MSI           | MEG X570 UNIFY              | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [a0b6dfe7e4](https://linux-hardware.org/?probe=a0b6dfe7e4) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [0c0f293e16](https://linux-hardware.org/?probe=0c0f293e16) | Apr 13, 2022 |
| ASRock        | X570M Pro4                  | [b7373e1f8f](https://linux-hardware.org/?probe=b7373e1f8f) | Apr 13, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [a676bf83eb](https://linux-hardware.org/?probe=a676bf83eb) | Apr 13, 2022 |
| Dell          | 0773VG A00                  | [e0ebd58f3d](https://linux-hardware.org/?probe=e0ebd58f3d) | Apr 13, 2022 |
| ASUSTek       | Z97-A                       | [df33a057b6](https://linux-hardware.org/?probe=df33a057b6) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | [acd0ebed7c](https://linux-hardware.org/?probe=acd0ebed7c) | Apr 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [4c86ab8c47](https://linux-hardware.org/?probe=4c86ab8c47) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9af096ef7f](https://linux-hardware.org/?probe=9af096ef7f) | Apr 13, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [645c74ef90](https://linux-hardware.org/?probe=645c74ef90) | Apr 13, 2022 |
| Intel         | D945GCL AAD82064-200        | [c6d6c5a3df](https://linux-hardware.org/?probe=c6d6c5a3df) | Apr 13, 2022 |
| MSI           | Z270 SLI PLUS               | [fa00f6ccd6](https://linux-hardware.org/?probe=fa00f6ccd6) | Apr 13, 2022 |
| Gigabyte      | Z77-HD4                     | [f6323a1611](https://linux-hardware.org/?probe=f6323a1611) | Apr 13, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8e46ef2a00](https://linux-hardware.org/?probe=8e46ef2a00) | Apr 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3cc5e949a](https://linux-hardware.org/?probe=e3cc5e949a) | Apr 13, 2022 |
| Dell          | 0RY007                      | [f4384d4c1e](https://linux-hardware.org/?probe=f4384d4c1e) | Apr 13, 2022 |
| Dell          | 0YC03K A04                  | [4fd6bd10ff](https://linux-hardware.org/?probe=4fd6bd10ff) | Apr 13, 2022 |
| ASUSTek       | Z97-A                       | [94783711b3](https://linux-hardware.org/?probe=94783711b3) | Apr 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0dddcf5626](https://linux-hardware.org/?probe=0dddcf5626) | Apr 13, 2022 |
| MSI           | X470 GAMING PLUS            | [5100c45b65](https://linux-hardware.org/?probe=5100c45b65) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | [0ad016db29](https://linux-hardware.org/?probe=0ad016db29) | Apr 13, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [c28c553d03](https://linux-hardware.org/?probe=c28c553d03) | Apr 13, 2022 |
| ASUSTek       | H81M-E                      | [b26d147ae3](https://linux-hardware.org/?probe=b26d147ae3) | Apr 13, 2022 |
| Gigabyte      | P55M-UD2                    | [f1e49447b0](https://linux-hardware.org/?probe=f1e49447b0) | Apr 13, 2022 |
| Gigabyte      | B85M-D3H-A                  | [46dc99c237](https://linux-hardware.org/?probe=46dc99c237) | Apr 13, 2022 |
| HP            | 83E0                        | [6d3109eba8](https://linux-hardware.org/?probe=6d3109eba8) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| HARDKERNEL    | ODROID-H2                   | [63ab4fa5ac](https://linux-hardware.org/?probe=63ab4fa5ac) | Apr 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| ASUSTek       | X99-A                       | [2ac66bb174](https://linux-hardware.org/?probe=2ac66bb174) | Apr 13, 2022 |
| ECS           | H81H3-I                     | [1bf6cc284c](https://linux-hardware.org/?probe=1bf6cc284c) | Apr 13, 2022 |
| MSI           | MAG B550M MORTAR            | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| Foxconn       | 2AB7                        | [1f974543fc](https://linux-hardware.org/?probe=1f974543fc) | Apr 13, 2022 |
| Dell          | 0GY6Y8 A02                  | [5f2f221d6c](https://linux-hardware.org/?probe=5f2f221d6c) | Apr 13, 2022 |
| ASUSTek       | PRIME Z370-P                | [3b91a78742](https://linux-hardware.org/?probe=3b91a78742) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e3a8701de2](https://linux-hardware.org/?probe=e3a8701de2) | Apr 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [bad4b60ec4](https://linux-hardware.org/?probe=bad4b60ec4) | Apr 13, 2022 |
| ASRock        | TRX40 Taichi                | [7ce5e071a2](https://linux-hardware.org/?probe=7ce5e071a2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-A                | [cb3eb74403](https://linux-hardware.org/?probe=cb3eb74403) | Apr 13, 2022 |
| Dell          | 0C2XKD A00                  | [4ece5fe0b7](https://linux-hardware.org/?probe=4ece5fe0b7) | Apr 13, 2022 |
| MSI           | H110M ECO                   | [90c061e58f](https://linux-hardware.org/?probe=90c061e58f) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [392f621ca6](https://linux-hardware.org/?probe=392f621ca6) | Apr 13, 2022 |
| Gigabyte      | X570 GAMING X               | [b089bb9293](https://linux-hardware.org/?probe=b089bb9293) | Apr 13, 2022 |
| ASUSTek       | PRIME A520M-K               | [58dab53fb1](https://linux-hardware.org/?probe=58dab53fb1) | Apr 13, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| ASRockRack    | ROMED8-2T                   | [600b198520](https://linux-hardware.org/?probe=600b198520) | Apr 13, 2022 |
| MSI           | B450M MORTAR MAX            | [2ae073e712](https://linux-hardware.org/?probe=2ae073e712) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| Dell          | 0D6H9T A03                  | [964485a193](https://linux-hardware.org/?probe=964485a193) | Apr 13, 2022 |
| Gigabyte      | GA-A55M-S2HP                | [68c70673ef](https://linux-hardware.org/?probe=68c70673ef) | Apr 13, 2022 |
| System76      | Thelio Major thelio-majo... | [5924b8c844](https://linux-hardware.org/?probe=5924b8c844) | Apr 13, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| Lenovo        | NOK                         | [f99d93fc1e](https://linux-hardware.org/?probe=f99d93fc1e) | Apr 13, 2022 |
| Foxconn       | Cinema Series FAB           | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASRock        | B550 Extreme4               | [f74831788b](https://linux-hardware.org/?probe=f74831788b) | Apr 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3fade276ac](https://linux-hardware.org/?probe=3fade276ac) | Apr 13, 2022 |
| ASUSTek       | Z87-PLUS                    | [22fe7aea72](https://linux-hardware.org/?probe=22fe7aea72) | Apr 13, 2022 |
| Dell          | 0WVYMC A00                  | [e2f9d3638d](https://linux-hardware.org/?probe=e2f9d3638d) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | [3ac4860cb3](https://linux-hardware.org/?probe=3ac4860cb3) | Apr 13, 2022 |
| ASRock        | X570 Taichi                 | [e048f91515](https://linux-hardware.org/?probe=e048f91515) | Apr 13, 2022 |
| Intel         | D54250WYK H13922-303        | [8619f35452](https://linux-hardware.org/?probe=8619f35452) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6ac57575d9](https://linux-hardware.org/?probe=6ac57575d9) | Apr 13, 2022 |
| Gigabyte      | 990FXA-UD5                  | [79b33f857d](https://linux-hardware.org/?probe=79b33f857d) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [13ad3d5cb4](https://linux-hardware.org/?probe=13ad3d5cb4) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | [70b154b039](https://linux-hardware.org/?probe=70b154b039) | Apr 13, 2022 |
| Dell          | 03V3TG A00                  | [a91e96515c](https://linux-hardware.org/?probe=a91e96515c) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e05e4dc47b](https://linux-hardware.org/?probe=e05e4dc47b) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f2a040ef2b](https://linux-hardware.org/?probe=f2a040ef2b) | Apr 13, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [fe40f7c199](https://linux-hardware.org/?probe=fe40f7c199) | Apr 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [11ca71a8e4](https://linux-hardware.org/?probe=11ca71a8e4) | Apr 13, 2022 |
| HP            | 3648h                       | [fef6cf4c12](https://linux-hardware.org/?probe=fef6cf4c12) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | [ce643cbdcd](https://linux-hardware.org/?probe=ce643cbdcd) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [5923be4543](https://linux-hardware.org/?probe=5923be4543) | Apr 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5aa4b5ec65](https://linux-hardware.org/?probe=5aa4b5ec65) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [dba21fb2d0](https://linux-hardware.org/?probe=dba21fb2d0) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [47267431ed](https://linux-hardware.org/?probe=47267431ed) | Apr 13, 2022 |
| Lenovo        | ThinkCentre M90p 5536A76    | [f594adac1d](https://linux-hardware.org/?probe=f594adac1d) | Apr 13, 2022 |
| Dell          | 0XCR8D A00                  | [d0f55067b0](https://linux-hardware.org/?probe=d0f55067b0) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [ace1daa3ff](https://linux-hardware.org/?probe=ace1daa3ff) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| ASUSTek       | Z87-PLUS                    | [01f7261143](https://linux-hardware.org/?probe=01f7261143) | Apr 13, 2022 |
| ASRock        | B550 Taichi                 | [28c58dfde0](https://linux-hardware.org/?probe=28c58dfde0) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [33cce38b5e](https://linux-hardware.org/?probe=33cce38b5e) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c77d1618d1](https://linux-hardware.org/?probe=c77d1618d1) | Apr 13, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| MSI           | X470 GAMING PRO             | [1ba8ee75be](https://linux-hardware.org/?probe=1ba8ee75be) | Apr 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [1f7a434559](https://linux-hardware.org/?probe=1f7a434559) | Apr 13, 2022 |
| ASUSTek       | H97-PLUS                    | [234fd15d56](https://linux-hardware.org/?probe=234fd15d56) | Apr 13, 2022 |
| Gigabyte      | Z97X-UD5H                   | [a4b25c87fa](https://linux-hardware.org/?probe=a4b25c87fa) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [18a9612e64](https://linux-hardware.org/?probe=18a9612e64) | Apr 13, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [68aa564b9f](https://linux-hardware.org/?probe=68aa564b9f) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| MSI           | Indio                       | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| Pegatron      | 2A99h                       | [0d208bc673](https://linux-hardware.org/?probe=0d208bc673) | Apr 13, 2022 |
| MSI           | MEG X570 ACE                | [0af514ea2b](https://linux-hardware.org/?probe=0af514ea2b) | Apr 13, 2022 |
| MSI           | 970 GAMING                  | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| Pegatron      | 2AD5                        | [3a1253ff97](https://linux-hardware.org/?probe=3a1253ff97) | Apr 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [71d793e054](https://linux-hardware.org/?probe=71d793e054) | Apr 13, 2022 |
| Pegatron      | 2A99h                       | [7a31392de4](https://linux-hardware.org/?probe=7a31392de4) | Apr 13, 2022 |
| HP            | 18E4                        | [83cf0afd92](https://linux-hardware.org/?probe=83cf0afd92) | Apr 13, 2022 |
| HP            | 18E4                        | [61a163f744](https://linux-hardware.org/?probe=61a163f744) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | [db6bf8f1b9](https://linux-hardware.org/?probe=db6bf8f1b9) | Apr 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [81ef10ca5d](https://linux-hardware.org/?probe=81ef10ca5d) | Apr 13, 2022 |
| MSI           | B450M PRO-VDH MAX           | [5792134e78](https://linux-hardware.org/?probe=5792134e78) | Apr 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [26a879283d](https://linux-hardware.org/?probe=26a879283d) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | [180b0efcf3](https://linux-hardware.org/?probe=180b0efcf3) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | [9d42acb7dc](https://linux-hardware.org/?probe=9d42acb7dc) | Apr 13, 2022 |
| ASUSTek       | P8Z77-V LX                  | [fcc2e4ef69](https://linux-hardware.org/?probe=fcc2e4ef69) | Apr 13, 2022 |
| MSI           | B360M PRO-VDH               | [33af7f8008](https://linux-hardware.org/?probe=33af7f8008) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [dc6799506a](https://linux-hardware.org/?probe=dc6799506a) | Apr 13, 2022 |
| Gigabyte      | Z77-D3H                     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| ASUSTek       | H97M-PLUS                   | [f420769b88](https://linux-hardware.org/?probe=f420769b88) | Apr 13, 2022 |
| Foxconn       | 2ABF                        | [6267f2f88d](https://linux-hardware.org/?probe=6267f2f88d) | Apr 13, 2022 |
| Gateway       | DS71                        | [3bd1ad84ce](https://linux-hardware.org/?probe=3bd1ad84ce) | Apr 13, 2022 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [5f4fac95df](https://linux-hardware.org/?probe=5f4fac95df) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4a91953dcb](https://linux-hardware.org/?probe=4a91953dcb) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| MSI           | B450M PRO-M2 MAX            | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| Gigabyte      | H87M-D3H                    | [f638f9b557](https://linux-hardware.org/?probe=f638f9b557) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| ASUSTek       | P9X79                       | [b7a035ea6b](https://linux-hardware.org/?probe=b7a035ea6b) | Apr 13, 2022 |
| Dell          | 0HY9JP A02                  | [ee1ec3e09d](https://linux-hardware.org/?probe=ee1ec3e09d) | Apr 13, 2022 |
| ASUSTek       | AM1M-A                      | [04fe7dc849](https://linux-hardware.org/?probe=04fe7dc849) | Apr 13, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [4bf977cb4d](https://linux-hardware.org/?probe=4bf977cb4d) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Dell          | 0YXT71 A01                  | [682a5bc6cc](https://linux-hardware.org/?probe=682a5bc6cc) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| ASRock        | H97M Anniversary            | [4a73af14bf](https://linux-hardware.org/?probe=4a73af14bf) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| Dell          | 042P49 A02                  | [f7b6132f34](https://linux-hardware.org/?probe=f7b6132f34) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [13a7544bd3](https://linux-hardware.org/?probe=13a7544bd3) | Apr 13, 2022 |
| ASUSTek       | PRIME A320M-K               | [7d0cde0bcd](https://linux-hardware.org/?probe=7d0cde0bcd) | Apr 13, 2022 |
| Intel         | X79 V1.3                    | [7f3431a44d](https://linux-hardware.org/?probe=7f3431a44d) | Apr 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [33b4ba0b02](https://linux-hardware.org/?probe=33b4ba0b02) | Apr 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [a37b2c860f](https://linux-hardware.org/?probe=a37b2c860f) | Apr 13, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [9a15614b1e](https://linux-hardware.org/?probe=9a15614b1e) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f75dc153d0](https://linux-hardware.org/?probe=f75dc153d0) | Apr 13, 2022 |
| System76      | Thelio thelio-r2            | [d2672b76fa](https://linux-hardware.org/?probe=d2672b76fa) | Apr 13, 2022 |
| MSI           | C847IS-P33                  | [1d421862e1](https://linux-hardware.org/?probe=1d421862e1) | Apr 13, 2022 |
| Unknown       | Unknown                     | [4d5c3fc937](https://linux-hardware.org/?probe=4d5c3fc937) | Apr 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | [243064550b](https://linux-hardware.org/?probe=243064550b) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | [46ce27bfa6](https://linux-hardware.org/?probe=46ce27bfa6) | Apr 13, 2022 |
| HP            | 805D                        | [56634964fb](https://linux-hardware.org/?probe=56634964fb) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [438f675016](https://linux-hardware.org/?probe=438f675016) | Apr 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | [e517f230fa](https://linux-hardware.org/?probe=e517f230fa) | Apr 13, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [123febbcd2](https://linux-hardware.org/?probe=123febbcd2) | Apr 13, 2022 |
| HP            | 2215                        | [5acea5fa0a](https://linux-hardware.org/?probe=5acea5fa0a) | Apr 13, 2022 |
| Gigabyte      | Z390 DESIGNARE-CF           | [b00858fa95](https://linux-hardware.org/?probe=b00858fa95) | Apr 13, 2022 |
| ASUSTek       | H87-PLUS                    | [8555858306](https://linux-hardware.org/?probe=8555858306) | Apr 13, 2022 |
| Dell          | 0JP3NX A00                  | [c76114b4b3](https://linux-hardware.org/?probe=c76114b4b3) | Apr 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ce4447422d](https://linux-hardware.org/?probe=ce4447422d) | Apr 13, 2022 |
| MSI           | 970A-G43 PLUS               | [5a0a8374bd](https://linux-hardware.org/?probe=5a0a8374bd) | Apr 12, 2022 |
| ASRock        | B560 Steel Legend           | [2b96c77aae](https://linux-hardware.org/?probe=2b96c77aae) | Apr 12, 2022 |
| MSI           | B250M PRO-VD                | [e5744a1f58](https://linux-hardware.org/?probe=e5744a1f58) | Apr 12, 2022 |
| Gigabyte      | H97-HD3                     | [9d1d134940](https://linux-hardware.org/?probe=9d1d134940) | Apr 12, 2022 |
| Dell          | 0Y5DDC A00                  | [2e9b09349a](https://linux-hardware.org/?probe=2e9b09349a) | Apr 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [8c88f1c50a](https://linux-hardware.org/?probe=8c88f1c50a) | Apr 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [5e30e0e56d](https://linux-hardware.org/?probe=5e30e0e56d) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [67175f0019](https://linux-hardware.org/?probe=67175f0019) | Apr 12, 2022 |
| Dell          | 0WR7PY A03                  | [221b65ebf0](https://linux-hardware.org/?probe=221b65ebf0) | Apr 12, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Foxconn       | 2AB7                        | [7a75548677](https://linux-hardware.org/?probe=7a75548677) | Apr 12, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [c5c12d6818](https://linux-hardware.org/?probe=c5c12d6818) | Apr 12, 2022 |
| Gigabyte      | H61M-DS2                    | [af56c63db4](https://linux-hardware.org/?probe=af56c63db4) | Apr 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [a0f5099126](https://linux-hardware.org/?probe=a0f5099126) | Apr 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [47404cf177](https://linux-hardware.org/?probe=47404cf177) | Apr 12, 2022 |
| Lenovo        | ThinkCentre M71e 5033A3U    | [9b0b83369e](https://linux-hardware.org/?probe=9b0b83369e) | Apr 12, 2022 |
| ASRock        | N68-VS3 UCC                 | [1ca06f94c7](https://linux-hardware.org/?probe=1ca06f94c7) | Apr 12, 2022 |
| Gigabyte      | B560M DS3H V2               | [175d1ee5ad](https://linux-hardware.org/?probe=175d1ee5ad) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| Dell          | 0M5DCD A00                  | [cabbac0657](https://linux-hardware.org/?probe=cabbac0657) | Apr 12, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [842cfcf606](https://linux-hardware.org/?probe=842cfcf606) | Apr 12, 2022 |
| Gigabyte      | X570 AORUS PRO              | [7819bdfd17](https://linux-hardware.org/?probe=7819bdfd17) | Apr 12, 2022 |
| ASUSTek       | PRIME Z490-P                | [c4aa65a809](https://linux-hardware.org/?probe=c4aa65a809) | Apr 12, 2022 |
| Gigabyte      | B150M-D3H-CF                | [1aee3c0b22](https://linux-hardware.org/?probe=1aee3c0b22) | Apr 12, 2022 |
| ASRock        | P67 Pro3                    | [a96f6cbac7](https://linux-hardware.org/?probe=a96f6cbac7) | Apr 12, 2022 |
| Intel         | DP43TF AAE34878-401         | [69a9b1705c](https://linux-hardware.org/?probe=69a9b1705c) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [3656e85663](https://linux-hardware.org/?probe=3656e85663) | Apr 12, 2022 |
| Lenovo        | MAHOBAY 31900005 STD        | [d82d73ba0a](https://linux-hardware.org/?probe=d82d73ba0a) | Apr 12, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| ASUSTek       | P5K Premium                 | [93ea12ef83](https://linux-hardware.org/?probe=93ea12ef83) | Apr 12, 2022 |
| ASUSTek       | H110M-R                     | [eaf3d1ac6f](https://linux-hardware.org/?probe=eaf3d1ac6f) | Apr 12, 2022 |
| Gigabyte      | B85M-D3H                    | [0622e51d45](https://linux-hardware.org/?probe=0622e51d45) | Apr 12, 2022 |
| Gigabyte      | H110M-S2-CF                 | [2ed1b1bd6f](https://linux-hardware.org/?probe=2ed1b1bd6f) | Apr 12, 2022 |
| ASUSTek       | P5G41T-M LX                 | [e7369dc30f](https://linux-hardware.org/?probe=e7369dc30f) | Apr 12, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [52828f419f](https://linux-hardware.org/?probe=52828f419f) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| MSI           | X570-A PRO                  | [5d33b64d12](https://linux-hardware.org/?probe=5d33b64d12) | Apr 12, 2022 |
| ASUSTek       | PRIME H510M-A               | [3cd8b545ab](https://linux-hardware.org/?probe=3cd8b545ab) | Apr 12, 2022 |
| Pegatron      | 2A86E01                     | [605526fdad](https://linux-hardware.org/?probe=605526fdad) | Apr 12, 2022 |
| ASUSTek       | SABERTOOTH 990FX R3.0       | [4f5a780267](https://linux-hardware.org/?probe=4f5a780267) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | [4c52c99ee9](https://linux-hardware.org/?probe=4c52c99ee9) | Apr 12, 2022 |
| MSI           | H510M PRO                   | [19dffc4e17](https://linux-hardware.org/?probe=19dffc4e17) | Apr 12, 2022 |
| Intel         | DN2820FYK H24582-201        | [401c412e61](https://linux-hardware.org/?probe=401c412e61) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| ASUSTek       | P8H61 PRO                   | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| MSI           | H510M PRO                   | [c4cd29bb7f](https://linux-hardware.org/?probe=c4cd29bb7f) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [a6d685f9c7](https://linux-hardware.org/?probe=a6d685f9c7) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [c11ab04912](https://linux-hardware.org/?probe=c11ab04912) | Apr 12, 2022 |
| Gigabyte      | B75M-D2V                    | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| MSI           | X99A SLI PLUS               | [eae6b5ed56](https://linux-hardware.org/?probe=eae6b5ed56) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [97bd95a7bb](https://linux-hardware.org/?probe=97bd95a7bb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [9f0b004c95](https://linux-hardware.org/?probe=9f0b004c95) | Apr 12, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [a8e2ef2c76](https://linux-hardware.org/?probe=a8e2ef2c76) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [68dd0c90a1](https://linux-hardware.org/?probe=68dd0c90a1) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| Dell          | 0N867P A01                  | [749dc04756](https://linux-hardware.org/?probe=749dc04756) | Apr 12, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [6b70f0a384](https://linux-hardware.org/?probe=6b70f0a384) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Dell          | 0Y5DDC A00                  | [8c932197a5](https://linux-hardware.org/?probe=8c932197a5) | Apr 12, 2022 |
| ASRock        | P67 Pro3                    | [633d0b6693](https://linux-hardware.org/?probe=633d0b6693) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | [284f85e2a2](https://linux-hardware.org/?probe=284f85e2a2) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Lenovo        | ThinkCentre A55 8982A48     | [8de4cd1654](https://linux-hardware.org/?probe=8de4cd1654) | Apr 12, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [be0d616e99](https://linux-hardware.org/?probe=be0d616e99) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| ASUSTek       | M4A88T-M                    | [934e06ad74](https://linux-hardware.org/?probe=934e06ad74) | Apr 12, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [6ad3d2d565](https://linux-hardware.org/?probe=6ad3d2d565) | Apr 12, 2022 |
| Foxconn       | 2AB1                        | [e43f2609cc](https://linux-hardware.org/?probe=e43f2609cc) | Apr 12, 2022 |
| ASRock        | B560 Pro4                   | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c6870d3a66](https://linux-hardware.org/?probe=c6870d3a66) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| Lenovo        | ThinkCentre M91P 7034A2U    | [a5b9a57a64](https://linux-hardware.org/?probe=a5b9a57a64) | Apr 12, 2022 |
| ASRock        | A320M-DVS R4.0              | [0025682d7d](https://linux-hardware.org/?probe=0025682d7d) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | [162850d6b3](https://linux-hardware.org/?probe=162850d6b3) | Apr 12, 2022 |
| Toshiba       | STI 010433                  | [9eb114e523](https://linux-hardware.org/?probe=9eb114e523) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ba5d8c783b](https://linux-hardware.org/?probe=ba5d8c783b) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [3930b32e77](https://linux-hardware.org/?probe=3930b32e77) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [1e302e1cce](https://linux-hardware.org/?probe=1e302e1cce) | Apr 12, 2022 |
| ASUSTek       | M3A78-CM                    | [8bfef0e6a5](https://linux-hardware.org/?probe=8bfef0e6a5) | Apr 12, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | [ceb55f32d7](https://linux-hardware.org/?probe=ceb55f32d7) | Apr 12, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| ASRock        | Z97E-ITX/ac                 | [082a102be9](https://linux-hardware.org/?probe=082a102be9) | Apr 12, 2022 |
| ASRockRack    | X470D4U                     | [69fbad2150](https://linux-hardware.org/?probe=69fbad2150) | Apr 12, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [b9f39d99ba](https://linux-hardware.org/?probe=b9f39d99ba) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | M61PME-S2P                  | [de22e15378](https://linux-hardware.org/?probe=de22e15378) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [f4cb39e804](https://linux-hardware.org/?probe=f4cb39e804) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [80c51dad27](https://linux-hardware.org/?probe=80c51dad27) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| ASUSTek       | M11BB                       | [6e0e26d007](https://linux-hardware.org/?probe=6e0e26d007) | Apr 12, 2022 |
| ASUSTek       | PRIME X470-PRO              | [40d527cfe8](https://linux-hardware.org/?probe=40d527cfe8) | Apr 12, 2022 |
| Gigabyte      | B450M DS3H-CF               | [d751a52423](https://linux-hardware.org/?probe=d751a52423) | Apr 11, 2022 |
| ASUSTek       | M11BB                       | [caf3596edc](https://linux-hardware.org/?probe=caf3596edc) | Apr 11, 2022 |
| Intel         | DN2820FYK H24582-201        | [9618216033](https://linux-hardware.org/?probe=9618216033) | Apr 11, 2022 |
| MSI           | G31TM-P21                   | [8879fa758a](https://linux-hardware.org/?probe=8879fa758a) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Dell          | 0HD5W2 A00                  | [ee2c10f4b2](https://linux-hardware.org/?probe=ee2c10f4b2) | Apr 11, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [a0ff638057](https://linux-hardware.org/?probe=a0ff638057) | Apr 11, 2022 |
| ASUSTek       | H81M-CS/BR                  | [e2452fa831](https://linux-hardware.org/?probe=e2452fa831) | Apr 11, 2022 |
| ASUSTek       | PRIME B450M-A               | [921b858e18](https://linux-hardware.org/?probe=921b858e18) | Apr 11, 2022 |
| ASRock        | EP2C602-4L/D16              | [938b601307](https://linux-hardware.org/?probe=938b601307) | Apr 11, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [3d3f67170e](https://linux-hardware.org/?probe=3d3f67170e) | Apr 11, 2022 |
| Intel         | DN2820FYK H24582-201        | [10d0131978](https://linux-hardware.org/?probe=10d0131978) | Apr 11, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [8c6cc15607](https://linux-hardware.org/?probe=8c6cc15607) | Apr 11, 2022 |
| Dell          | 0HJ054                      | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |
| ASUSTek       | P5B                         | [c8191103ef](https://linux-hardware.org/?probe=c8191103ef) | Apr 11, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| Intel         | DP43TF AAE34878-401         | [7ddb79a059](https://linux-hardware.org/?probe=7ddb79a059) | Apr 11, 2022 |
| MSI           | H510M-A PRO                 | [fdb4e581a9](https://linux-hardware.org/?probe=fdb4e581a9) | Apr 11, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| ASUSTek       | A88XM-PLUS                  | [54f7cac3d4](https://linux-hardware.org/?probe=54f7cac3d4) | Apr 11, 2022 |
| MSI           | Z390-A PRO                  | [259f72f743](https://linux-hardware.org/?probe=259f72f743) | Apr 11, 2022 |
| ASUSTek       | PRIME H270-PRO              | [5cc893af9c](https://linux-hardware.org/?probe=5cc893af9c) | Apr 11, 2022 |
| ASRock        | B450M Pro4-F                | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASUSTek       | PRIME Z270-A                | [c31ef29891](https://linux-hardware.org/?probe=c31ef29891) | Apr 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [285b194f70](https://linux-hardware.org/?probe=285b194f70) | Apr 11, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [816c91bfcd](https://linux-hardware.org/?probe=816c91bfcd) | Apr 11, 2022 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [7536bcd98d](https://linux-hardware.org/?probe=7536bcd98d) | Apr 11, 2022 |
| Intel         | Tiger Hill                  | [1fbea29754](https://linux-hardware.org/?probe=1fbea29754) | Apr 11, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [69eac21427](https://linux-hardware.org/?probe=69eac21427) | Apr 11, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [201076a42a](https://linux-hardware.org/?probe=201076a42a) | Apr 11, 2022 |
| ASUSTek       | Z87-K                       | [c80f104836](https://linux-hardware.org/?probe=c80f104836) | Apr 11, 2022 |
| MSI           | Z490-A PRO                  | [3e5dde6b49](https://linux-hardware.org/?probe=3e5dde6b49) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | [4f13d38f2e](https://linux-hardware.org/?probe=4f13d38f2e) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | GA-870A-UD3                 | [d43f5778b1](https://linux-hardware.org/?probe=d43f5778b1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | [0a89a1b47b](https://linux-hardware.org/?probe=0a89a1b47b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| Gigabyte      | GA-970A-DS3                 | [a52c5e98af](https://linux-hardware.org/?probe=a52c5e98af) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| PC Engines    | apu4                        | [601866ecaa](https://linux-hardware.org/?probe=601866ecaa) | Apr 11, 2022 |
| ASRock        | G41M-GS                     | [f3e24ea1c9](https://linux-hardware.org/?probe=f3e24ea1c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| ASUSTek       | F2A85-V                     | [4457cfd21d](https://linux-hardware.org/?probe=4457cfd21d) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [8c2362aa24](https://linux-hardware.org/?probe=8c2362aa24) | Apr 11, 2022 |
| PCWare        | IPMH61R1                    | [4f465b1b2d](https://linux-hardware.org/?probe=4f465b1b2d) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Gigabyte      | H77-DS3H                    | [cb60e697d1](https://linux-hardware.org/?probe=cb60e697d1) | Apr 11, 2022 |
| ASUSTek       | PRIME X370-PRO              | [1b2b5e921d](https://linux-hardware.org/?probe=1b2b5e921d) | Apr 11, 2022 |
| eMachines     | EL1850                      | [4c641c8e6a](https://linux-hardware.org/?probe=4c641c8e6a) | Apr 11, 2022 |
| ASUSTek       | B85M-E                      | [95ae38af4e](https://linux-hardware.org/?probe=95ae38af4e) | Apr 11, 2022 |
| Gigabyte      | 970A-DS3P                   | [eb62b9de81](https://linux-hardware.org/?probe=eb62b9de81) | Apr 11, 2022 |
| Gigabyte      | Z97-HD3                     | [0f28cbb37d](https://linux-hardware.org/?probe=0f28cbb37d) | Apr 11, 2022 |
| MSI           | Boston                      | [4dd70b97f5](https://linux-hardware.org/?probe=4dd70b97f5) | Apr 11, 2022 |
| MSI           | N3150I ECO                  | [afe5c622e2](https://linux-hardware.org/?probe=afe5c622e2) | Apr 11, 2022 |
| ASRock        | X99X Killer                 | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| Gigabyte      | Z390 UD                     | [ef0b36db62](https://linux-hardware.org/?probe=ef0b36db62) | Apr 11, 2022 |
| MSI           | H510M-A PRO                 | [a32957f98c](https://linux-hardware.org/?probe=a32957f98c) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| ASUSTek       | Z97-K                       | [ec0e275d27](https://linux-hardware.org/?probe=ec0e275d27) | Apr 11, 2022 |
| KLLISRE       | X99-B5 V1.1                 | [5c1d47d9c9](https://linux-hardware.org/?probe=5c1d47d9c9) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Unknown       | Unknown                     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| ASUSTek       | P8B75-M                     | [5d36c5b15f](https://linux-hardware.org/?probe=5d36c5b15f) | Apr 11, 2022 |
| ASUSTek       | H81M-R                      | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASRock        | A320M-DVS R4.0              | [5de4abca91](https://linux-hardware.org/?probe=5de4abca91) | Apr 11, 2022 |
| ASUSTek       | Amberine M                  | [e47a1f2886](https://linux-hardware.org/?probe=e47a1f2886) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| ASRock        | B250M Performance           | [3d9af3df5a](https://linux-hardware.org/?probe=3d9af3df5a) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| MSI           | 760GM-P34                   | [c346a58754](https://linux-hardware.org/?probe=c346a58754) | Apr 11, 2022 |
| ASUSTek       | PRIME X299-A                | [3cfaa62e07](https://linux-hardware.org/?probe=3cfaa62e07) | Apr 11, 2022 |
| Gigabyte      | G41MT-S2P                   | [67018740b8](https://linux-hardware.org/?probe=67018740b8) | Apr 11, 2022 |
| Positivo      | POS-MI945AA                 | [581272b7c1](https://linux-hardware.org/?probe=581272b7c1) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| MSI           | H170A PC MATE               | [404f32fc8a](https://linux-hardware.org/?probe=404f32fc8a) | Apr 11, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [9f5778e082](https://linux-hardware.org/?probe=9f5778e082) | Apr 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1a475ba1e6](https://linux-hardware.org/?probe=1a475ba1e6) | Apr 11, 2022 |
| MSI           | B460M PRO-VDH WIFI          | [27cb501628](https://linux-hardware.org/?probe=27cb501628) | Apr 11, 2022 |
| Acer          | Nitro N50-610               | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | [36e8e44760](https://linux-hardware.org/?probe=36e8e44760) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| MSI           | H81M-E33                    | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | [91037ebcec](https://linux-hardware.org/?probe=91037ebcec) | Apr 10, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [c3d5951840](https://linux-hardware.org/?probe=c3d5951840) | Apr 10, 2022 |
| Jetway        | 1.0                         | [dbfff94911](https://linux-hardware.org/?probe=dbfff94911) | Apr 10, 2022 |
| Dell          | 0N4YC8 A00                  | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| MSI           | Z370-A PRO                  | [94fccb48fd](https://linux-hardware.org/?probe=94fccb48fd) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [210b897284](https://linux-hardware.org/?probe=210b897284) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [f986565b6b](https://linux-hardware.org/?probe=f986565b6b) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [36b98241e2](https://linux-hardware.org/?probe=36b98241e2) | Apr 10, 2022 |
| Itautec       | ST 4265                     | [b2facb728e](https://linux-hardware.org/?probe=b2facb728e) | Apr 10, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Gigabyte      | B75-D3V                     | [ea939b5214](https://linux-hardware.org/?probe=ea939b5214) | Apr 10, 2022 |
| Intel         | DH67BL AAG10189-211         | [e664ba6c5a](https://linux-hardware.org/?probe=e664ba6c5a) | Apr 10, 2022 |
| Gigabyte      | Q67M-D2H                    | [c95352a142](https://linux-hardware.org/?probe=c95352a142) | Apr 10, 2022 |
| ASRock        | B450 Steel Legend           | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [335125845e](https://linux-hardware.org/?probe=335125845e) | Apr 10, 2022 |
| MSI           | A320M-A PRO MAX             | [c522f42e92](https://linux-hardware.org/?probe=c522f42e92) | Apr 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [76f3ee9c71](https://linux-hardware.org/?probe=76f3ee9c71) | Apr 10, 2022 |
| MSI           | Z170-A PRO                  | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell          | 08NPPY A00                  | [5c2b30a7e1](https://linux-hardware.org/?probe=5c2b30a7e1) | Apr 10, 2022 |
| MSI           | B350I PRO AC                | [8065d41c05](https://linux-hardware.org/?probe=8065d41c05) | Apr 10, 2022 |
| Dell          | 03NVJ6 A00                  | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| Dell          | 0200DY A00                  | [38488f5c3a](https://linux-hardware.org/?probe=38488f5c3a) | Apr 10, 2022 |
| Intel         | X99                         | [ecea2585e1](https://linux-hardware.org/?probe=ecea2585e1) | Apr 10, 2022 |
| ASUSTek       | Z87-WS                      | [7706049c53](https://linux-hardware.org/?probe=7706049c53) | Apr 10, 2022 |
| HP            | 0A64h                       | [45c89ff83d](https://linux-hardware.org/?probe=45c89ff83d) | Apr 10, 2022 |
| MSI           | H510M-A PRO                 | [d93ab23121](https://linux-hardware.org/?probe=d93ab23121) | Apr 10, 2022 |
| HP            | 21F5 0A                     | [516f2dbc9e](https://linux-hardware.org/?probe=516f2dbc9e) | Apr 10, 2022 |
| Dell          | 0T10XW A02                  | [01e9bf2cee](https://linux-hardware.org/?probe=01e9bf2cee) | Apr 10, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [5abfaa2b99](https://linux-hardware.org/?probe=5abfaa2b99) | Apr 10, 2022 |
| Dell          | 055H3G A01                  | [a41b7fbf00](https://linux-hardware.org/?probe=a41b7fbf00) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [e55b3bf73c](https://linux-hardware.org/?probe=e55b3bf73c) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| MSI           | B360-A PRO                  | [cb8b648eac](https://linux-hardware.org/?probe=cb8b648eac) | Apr 10, 2022 |
| HP            | 3048h                       | [c55f6bc20c](https://linux-hardware.org/?probe=c55f6bc20c) | Apr 10, 2022 |
| HP            | 1998                        | [28dcd611cc](https://linux-hardware.org/?probe=28dcd611cc) | Apr 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [71adeab793](https://linux-hardware.org/?probe=71adeab793) | Apr 10, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [071e82f576](https://linux-hardware.org/?probe=071e82f576) | Apr 10, 2022 |
| ASUSTek       | P6T                         | [579a4a7f83](https://linux-hardware.org/?probe=579a4a7f83) | Apr 10, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [73bbbb42c5](https://linux-hardware.org/?probe=73bbbb42c5) | Apr 10, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [d20c0a8797](https://linux-hardware.org/?probe=d20c0a8797) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Lenovo        | ThinkCentre M58p 7484ANU    | [2d7d0de436](https://linux-hardware.org/?probe=2d7d0de436) | Apr 10, 2022 |
| ASUSTek       | P5K Deluxe                  | [50d7c349cd](https://linux-hardware.org/?probe=50d7c349cd) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| Dell          | 0GY6Y8 A03                  | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | W480 VISION D               | [69e85ce80c](https://linux-hardware.org/?probe=69e85ce80c) | Apr 10, 2022 |
| ASRock        | H110M-ITX                   | [13dff6f000](https://linux-hardware.org/?probe=13dff6f000) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| Medion        | MS-7366                     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [22502631b3](https://linux-hardware.org/?probe=22502631b3) | Apr 10, 2022 |
| MSI           | MS-7360                     | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [e4fc7cc2cc](https://linux-hardware.org/?probe=e4fc7cc2cc) | Apr 10, 2022 |
| MSI           | A68HM-E33 V2                | [cfa5407b7f](https://linux-hardware.org/?probe=cfa5407b7f) | Apr 10, 2022 |
| Dell          | 0KC9NP A00                  | [7b3bb36e84](https://linux-hardware.org/?probe=7b3bb36e84) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| Gigabyte      | M61PME-S2P                  | [f4b5ca3229](https://linux-hardware.org/?probe=f4b5ca3229) | Apr 10, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [63aaae3d92](https://linux-hardware.org/?probe=63aaae3d92) | Apr 10, 2022 |
| Gigabyte      | 945GCM-S2L                  | [8737781637](https://linux-hardware.org/?probe=8737781637) | Apr 10, 2022 |
| ASRock        | A300M-STX                   | [6d3fe856b8](https://linux-hardware.org/?probe=6d3fe856b8) | Apr 10, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [9d20eaf1f2](https://linux-hardware.org/?probe=9d20eaf1f2) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [9971d706c5](https://linux-hardware.org/?probe=9971d706c5) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [9cc7cc23d6](https://linux-hardware.org/?probe=9cc7cc23d6) | Apr 10, 2022 |
| ASRock        | B560M Steel Legend          | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [3845180872](https://linux-hardware.org/?probe=3845180872) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| ASUSTek       | P8H77-V                     | [9014595f74](https://linux-hardware.org/?probe=9014595f74) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d03632cea9](https://linux-hardware.org/?probe=d03632cea9) | Apr 10, 2022 |
| Gigabyte      | H61M-S2PV                   | [8760e3254a](https://linux-hardware.org/?probe=8760e3254a) | Apr 10, 2022 |
| ASUSTek       | H87M-PRO                    | [0d2b6aaa56](https://linux-hardware.org/?probe=0d2b6aaa56) | Apr 10, 2022 |
| eMachines     | EL1850G                     | [cfa8d1c8d5](https://linux-hardware.org/?probe=cfa8d1c8d5) | Apr 10, 2022 |
| Gigabyte      | GA-MA770-UD3                | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Foxconn       | 2A92                        | [d7dc8e0a2b](https://linux-hardware.org/?probe=d7dc8e0a2b) | Apr 10, 2022 |
| Dell          | 0MN1TX A02                  | [cf2e65caf4](https://linux-hardware.org/?probe=cf2e65caf4) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | H61M-PRO                    | [c89c043120](https://linux-hardware.org/?probe=c89c043120) | Apr 10, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [63df7871b0](https://linux-hardware.org/?probe=63df7871b0) | Apr 10, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [6884809c79](https://linux-hardware.org/?probe=6884809c79) | Apr 10, 2022 |
| Dell          | 0DN075                      | [043e18273e](https://linux-hardware.org/?probe=043e18273e) | Apr 10, 2022 |
| Dell          | 0DN075                      | [759d8d5556](https://linux-hardware.org/?probe=759d8d5556) | Apr 10, 2022 |
| ASRock        | G31M-S                      | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [885cbd9d0c](https://linux-hardware.org/?probe=885cbd9d0c) | Apr 10, 2022 |
| Gigabyte      | H81M-S2PV                   | [4c37e32ae6](https://linux-hardware.org/?probe=4c37e32ae6) | Apr 10, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [28114b7924](https://linux-hardware.org/?probe=28114b7924) | Apr 10, 2022 |
| Acer          | Aspire TC-705               | [d3ad458c45](https://linux-hardware.org/?probe=d3ad458c45) | Apr 10, 2022 |
| Dell          | 0JP3NX A01                  | [058f6a25dd](https://linux-hardware.org/?probe=058f6a25dd) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [14b70a1c77](https://linux-hardware.org/?probe=14b70a1c77) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [117eded7f8](https://linux-hardware.org/?probe=117eded7f8) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [1009093226](https://linux-hardware.org/?probe=1009093226) | Apr 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6e993bc145](https://linux-hardware.org/?probe=6e993bc145) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [1638359c7b](https://linux-hardware.org/?probe=1638359c7b) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [c344a9c7b9](https://linux-hardware.org/?probe=c344a9c7b9) | Apr 10, 2022 |
| Intel         | DN2820FYB H24582-205        | [48e5060f20](https://linux-hardware.org/?probe=48e5060f20) | Apr 10, 2022 |
| ASRock        | Z270 Professional Gaming... | [9129317f19](https://linux-hardware.org/?probe=9129317f19) | Apr 10, 2022 |
| Dell          | 0WMJ54 A01                  | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [1345425e85](https://linux-hardware.org/?probe=1345425e85) | Apr 10, 2022 |
| ASUSTek       | M2N8L                       | [dc78c18c3f](https://linux-hardware.org/?probe=dc78c18c3f) | Apr 10, 2022 |
| Intel         | DN2820FYB H24582-205        | [c0fe31c3da](https://linux-hardware.org/?probe=c0fe31c3da) | Apr 10, 2022 |
| NCR           | Pocono BIOS.5.1             | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| ASUSTek       | PRIME Z390-A                | [9f3f45d840](https://linux-hardware.org/?probe=9f3f45d840) | Apr 09, 2022 |
| Gigabyte      | Z77-DS3H                    | [88fba1bae6](https://linux-hardware.org/?probe=88fba1bae6) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [0bac47f3e6](https://linux-hardware.org/?probe=0bac47f3e6) | Apr 09, 2022 |
| MSI           | H110M ECO                   | [c01d51d1f5](https://linux-hardware.org/?probe=c01d51d1f5) | Apr 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [645fb7bb30](https://linux-hardware.org/?probe=645fb7bb30) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [1c57ef464e](https://linux-hardware.org/?probe=1c57ef464e) | Apr 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [a56209b0c7](https://linux-hardware.org/?probe=a56209b0c7) | Apr 09, 2022 |
| Acer          | Aspire TC-705               | [bb62851ef3](https://linux-hardware.org/?probe=bb62851ef3) | Apr 09, 2022 |
| Dell          | 00V62H A01                  | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| HP            | 18E5                        | [5c24443112](https://linux-hardware.org/?probe=5c24443112) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [e641889a70](https://linux-hardware.org/?probe=e641889a70) | Apr 09, 2022 |
| ASUSTek       | Z87-K                       | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| Dell          | 0HY9JP A02                  | [84b46b3236](https://linux-hardware.org/?probe=84b46b3236) | Apr 09, 2022 |
| ASUSTek       | PRIME B250M-A               | [43c15ac73b](https://linux-hardware.org/?probe=43c15ac73b) | Apr 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [5a09d1fa57](https://linux-hardware.org/?probe=5a09d1fa57) | Apr 09, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [2ab0e2bf2d](https://linux-hardware.org/?probe=2ab0e2bf2d) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [3d91f855bc](https://linux-hardware.org/?probe=3d91f855bc) | Apr 09, 2022 |
| Alienware     | 0J560M A00                  | [a0b422480a](https://linux-hardware.org/?probe=a0b422480a) | Apr 09, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [50cfb4d530](https://linux-hardware.org/?probe=50cfb4d530) | Apr 09, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [b48b65867f](https://linux-hardware.org/?probe=b48b65867f) | Apr 09, 2022 |
| NZXT          | N7 B550                     | [838fd4244b](https://linux-hardware.org/?probe=838fd4244b) | Apr 09, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [6130d7e1e6](https://linux-hardware.org/?probe=6130d7e1e6) | Apr 09, 2022 |
| NZXT          | N7 B550                     | [e3f895a70b](https://linux-hardware.org/?probe=e3f895a70b) | Apr 09, 2022 |
| Acer          | Veriton M6660G V:1.0        | [a41ffdc22b](https://linux-hardware.org/?probe=a41ffdc22b) | Apr 09, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [cb4cca0ed4](https://linux-hardware.org/?probe=cb4cca0ed4) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| HP            | 81C9                        | [2eff1b8a02](https://linux-hardware.org/?probe=2eff1b8a02) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | [1bd70fbd59](https://linux-hardware.org/?probe=1bd70fbd59) | Apr 09, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [aa9de07827](https://linux-hardware.org/?probe=aa9de07827) | Apr 09, 2022 |
| ASRock        | Z87 Pro4                    | [03ee27c2ea](https://linux-hardware.org/?probe=03ee27c2ea) | Apr 09, 2022 |
| Gigabyte      | G41MT-S2PT                  | [7dde5fefd1](https://linux-hardware.org/?probe=7dde5fefd1) | Apr 09, 2022 |
| Unknown       | TIGD-CI4                    | [266aef8b2e](https://linux-hardware.org/?probe=266aef8b2e) | Apr 09, 2022 |
| MSI           | X79A-GD45 Plus              | [445e8fa4b8](https://linux-hardware.org/?probe=445e8fa4b8) | Apr 09, 2022 |
| Gigabyte      | Z590 VISION G               | [b160291e93](https://linux-hardware.org/?probe=b160291e93) | Apr 09, 2022 |
| ECS           | H61H2-M13                   | [d19ae9b1d5](https://linux-hardware.org/?probe=d19ae9b1d5) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [862e7ffc88](https://linux-hardware.org/?probe=862e7ffc88) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b0840dd295](https://linux-hardware.org/?probe=b0840dd295) | Apr 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [e20b365083](https://linux-hardware.org/?probe=e20b365083) | Apr 09, 2022 |
| ASUSTek       | H110M-C                     | [0326b913dd](https://linux-hardware.org/?probe=0326b913dd) | Apr 09, 2022 |
| ASUSTek       | PRIME X370-PRO              | [8984dcc316](https://linux-hardware.org/?probe=8984dcc316) | Apr 09, 2022 |
| ASRock        | P43DE3                      | [21eed63d16](https://linux-hardware.org/?probe=21eed63d16) | Apr 09, 2022 |
| Gigabyte      | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Intel         | DP35DP AAD81073-206         | [b257e3cf76](https://linux-hardware.org/?probe=b257e3cf76) | Apr 09, 2022 |
| MSI           | MS-7369                     | [0a32c9427a](https://linux-hardware.org/?probe=0a32c9427a) | Apr 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [272c9f107a](https://linux-hardware.org/?probe=272c9f107a) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| Gigabyte      | Z87P-D3                     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| ASUSTek       | P8H67-V                     | [a2ae5eb5b9](https://linux-hardware.org/?probe=a2ae5eb5b9) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [62c84ef4b4](https://linux-hardware.org/?probe=62c84ef4b4) | Apr 09, 2022 |
| ASUSTek       | PRIME B550M-K               | [acff685c08](https://linux-hardware.org/?probe=acff685c08) | Apr 09, 2022 |
| Foxconn       | A7DA 3 series               | [2fc0654e61](https://linux-hardware.org/?probe=2fc0654e61) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [07bde861ad](https://linux-hardware.org/?probe=07bde861ad) | Apr 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| MSI           | B550M PRO-VDH               | [9597b0a2d9](https://linux-hardware.org/?probe=9597b0a2d9) | Apr 09, 2022 |
| ASRock        | Z77 Pro4                    | [38eeb648af](https://linux-hardware.org/?probe=38eeb648af) | Apr 09, 2022 |
| Medion        | MS-7707                     | [fb95ae3a92](https://linux-hardware.org/?probe=fb95ae3a92) | Apr 09, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [cf308c090a](https://linux-hardware.org/?probe=cf308c090a) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [457adc950f](https://linux-hardware.org/?probe=457adc950f) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Medion        | MS-7366                     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| MSI           | 2AE0                        | [57e29c9110](https://linux-hardware.org/?probe=57e29c9110) | Apr 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [48c13b2a02](https://linux-hardware.org/?probe=48c13b2a02) | Apr 09, 2022 |
| MSI           | X99A SLI PLUS               | [f0045560de](https://linux-hardware.org/?probe=f0045560de) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [ea4da8fb23](https://linux-hardware.org/?probe=ea4da8fb23) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [08f79499bd](https://linux-hardware.org/?probe=08f79499bd) | Apr 09, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [bb210a31b5](https://linux-hardware.org/?probe=bb210a31b5) | Apr 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [09946e9edf](https://linux-hardware.org/?probe=09946e9edf) | Apr 09, 2022 |
| ASUSTek       | P7P55-M                     | [dd609f533b](https://linux-hardware.org/?probe=dd609f533b) | Apr 09, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [8d440b5da5](https://linux-hardware.org/?probe=8d440b5da5) | Apr 09, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [648d7a9a57](https://linux-hardware.org/?probe=648d7a9a57) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| ASUSTek       | P5QPL-AM                    | [1d0d38c7c8](https://linux-hardware.org/?probe=1d0d38c7c8) | Apr 09, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [387e498dfc](https://linux-hardware.org/?probe=387e498dfc) | Apr 09, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [799106d1e6](https://linux-hardware.org/?probe=799106d1e6) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| Biostar       | B550MH                      | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| ASRock        | X299 Gaming K6              | [86fc074c1f](https://linux-hardware.org/?probe=86fc074c1f) | Apr 09, 2022 |
| ASRock        | FM2A75 Pro4                 | [e6281eef7f](https://linux-hardware.org/?probe=e6281eef7f) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [14ae36ec3e](https://linux-hardware.org/?probe=14ae36ec3e) | Apr 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| Dell          | 0YXT71 A01                  | [ff682e31dc](https://linux-hardware.org/?probe=ff682e31dc) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Supermicro    | X9SRH-7F/7TF                | [ad534e1bb2](https://linux-hardware.org/?probe=ad534e1bb2) | Apr 09, 2022 |
| Gigabyte      | B360HD3PLM-CF               | [1c3d254151](https://linux-hardware.org/?probe=1c3d254151) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [525028a40b](https://linux-hardware.org/?probe=525028a40b) | Apr 09, 2022 |
| Dell          | 0HN7XN A01                  | [251b8049e2](https://linux-hardware.org/?probe=251b8049e2) | Apr 09, 2022 |
| Dell          | 033FF6 A00                  | [5a96e1cad1](https://linux-hardware.org/?probe=5a96e1cad1) | Apr 09, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| Gigabyte      | B360HD3PLM-CF               | [d966170231](https://linux-hardware.org/?probe=d966170231) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [f45b500a83](https://linux-hardware.org/?probe=f45b500a83) | Apr 09, 2022 |
| HP            | 0A64h                       | [1dda6c8ea9](https://linux-hardware.org/?probe=1dda6c8ea9) | Apr 09, 2022 |
| ASRock        | Z170 Extreme6               | [616ea06acb](https://linux-hardware.org/?probe=616ea06acb) | Apr 09, 2022 |
| Medion        | TJ4125                      | [4541511f38](https://linux-hardware.org/?probe=4541511f38) | Apr 08, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [8f7798d84a](https://linux-hardware.org/?probe=8f7798d84a) | Apr 08, 2022 |
| Unknown       | HX90                        | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| ASUSTek       | P8H61-M LE                  | [f2af37f520](https://linux-hardware.org/?probe=f2af37f520) | Apr 08, 2022 |
| Gigabyte      | B450M DS3H V2               | [32811d6cd7](https://linux-hardware.org/?probe=32811d6cd7) | Apr 08, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [d42f8f3535](https://linux-hardware.org/?probe=d42f8f3535) | Apr 08, 2022 |
| HP            | 1495                        | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| ASRock        | H61M-S                      | [7f0b28837f](https://linux-hardware.org/?probe=7f0b28837f) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [04e63d8b54](https://linux-hardware.org/?probe=04e63d8b54) | Apr 08, 2022 |
| Acer          | Veriton X6630G              | [69dfc9b91a](https://linux-hardware.org/?probe=69dfc9b91a) | Apr 08, 2022 |
| Gigabyte      | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| ASRock        | N68C-S UCC                  | [be7a7cb25f](https://linux-hardware.org/?probe=be7a7cb25f) | Apr 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [c0d7bcd89b](https://linux-hardware.org/?probe=c0d7bcd89b) | Apr 08, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [53afee4cf6](https://linux-hardware.org/?probe=53afee4cf6) | Apr 08, 2022 |
| EVGA          | 140-SS-E177                 | [4af369b993](https://linux-hardware.org/?probe=4af369b993) | Apr 08, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d973a4378b](https://linux-hardware.org/?probe=d973a4378b) | Apr 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [2db23c062e](https://linux-hardware.org/?probe=2db23c062e) | Apr 08, 2022 |
| ASRock        | B450 Pro4                   | [16ac7687a0](https://linux-hardware.org/?probe=16ac7687a0) | Apr 08, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [1a031845b1](https://linux-hardware.org/?probe=1a031845b1) | Apr 08, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [cdf784520e](https://linux-hardware.org/?probe=cdf784520e) | Apr 08, 2022 |
| ASUSTek       | P8H67-M LE                  | [f21e5ade5d](https://linux-hardware.org/?probe=f21e5ade5d) | Apr 08, 2022 |
| ASUSTek       | PRIME H510M-A               | [7a337eb0a8](https://linux-hardware.org/?probe=7a337eb0a8) | Apr 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7438fcdda2](https://linux-hardware.org/?probe=7438fcdda2) | Apr 08, 2022 |
| ASRockRack    | B565D4-V1L                  | [12f3bc72ea](https://linux-hardware.org/?probe=12f3bc72ea) | Apr 08, 2022 |
| AZW           | U59                         | [d84f7caf26](https://linux-hardware.org/?probe=d84f7caf26) | Apr 08, 2022 |
| MSI           | C847IS-P33                  | [fc21413487](https://linux-hardware.org/?probe=fc21413487) | Apr 08, 2022 |
| ASUSTek       | P5Q DELUXE                  | [8ab0db4e45](https://linux-hardware.org/?probe=8ab0db4e45) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fc6b27af99](https://linux-hardware.org/?probe=fc6b27af99) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Acer          | Batman A01                  | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Intel         | H81                         | [ffcfab5f12](https://linux-hardware.org/?probe=ffcfab5f12) | Apr 08, 2022 |
| Acer          | EG43M                       | [cf64046a46](https://linux-hardware.org/?probe=cf64046a46) | Apr 08, 2022 |
| ASUSTek       | B150M-C                     | [008522be3f](https://linux-hardware.org/?probe=008522be3f) | Apr 08, 2022 |
| ASUSTek       | H87M-PRO                    | [86b82467fd](https://linux-hardware.org/?probe=86b82467fd) | Apr 08, 2022 |
| ASUSTek       | B150M-C                     | [5c4348526d](https://linux-hardware.org/?probe=5c4348526d) | Apr 08, 2022 |
| Gigabyte      | B550M DS3H                  | [0291e8b387](https://linux-hardware.org/?probe=0291e8b387) | Apr 08, 2022 |
| Gigabyte      | B75M-D2V                    | [256fd58a92](https://linux-hardware.org/?probe=256fd58a92) | Apr 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7305c4d766](https://linux-hardware.org/?probe=7305c4d766) | Apr 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [8986d7abf1](https://linux-hardware.org/?probe=8986d7abf1) | Apr 08, 2022 |
| Gigabyte      | B550M S2H                   | [b90571d7db](https://linux-hardware.org/?probe=b90571d7db) | Apr 08, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [f4edf90f35](https://linux-hardware.org/?probe=f4edf90f35) | Apr 08, 2022 |
| Intel         | DH61SA AAG38870-201         | [6f45a55332](https://linux-hardware.org/?probe=6f45a55332) | Apr 08, 2022 |
| Intel         | DH61SA AAG38870-201         | [516d1a3e43](https://linux-hardware.org/?probe=516d1a3e43) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [3cfcaa0d11](https://linux-hardware.org/?probe=3cfcaa0d11) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [fa2e3ae8ee](https://linux-hardware.org/?probe=fa2e3ae8ee) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| Biostar       | TB250-BTC PRO               | [e06b543a59](https://linux-hardware.org/?probe=e06b543a59) | Apr 08, 2022 |
| MSI           | FM2-A75MA-E35               | [5d1a0661c9](https://linux-hardware.org/?probe=5d1a0661c9) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| HP            | 82F2 A01                    | [6eb23290be](https://linux-hardware.org/?probe=6eb23290be) | Apr 08, 2022 |
| HP            | 3397                        | [d22ff33b0e](https://linux-hardware.org/?probe=d22ff33b0e) | Apr 08, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [263621f796](https://linux-hardware.org/?probe=263621f796) | Apr 08, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [a2cb2571ee](https://linux-hardware.org/?probe=a2cb2571ee) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASUSTek       | H97M-PLUS                   | [b90df26c2a](https://linux-hardware.org/?probe=b90df26c2a) | Apr 08, 2022 |
| Lenovo        | ThinkStation S20 4157WC1    | [d64502fb70](https://linux-hardware.org/?probe=d64502fb70) | Apr 08, 2022 |
| ASUSTek       | B85M-G                      | [f812d0803f](https://linux-hardware.org/?probe=f812d0803f) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [40c5824930](https://linux-hardware.org/?probe=40c5824930) | Apr 08, 2022 |
| ASUSTek       | PRIME B450M-A II            | [3d20e0e751](https://linux-hardware.org/?probe=3d20e0e751) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [10458d0000](https://linux-hardware.org/?probe=10458d0000) | Apr 08, 2022 |
| MSI           | Z390-A PRO                  | [abd15de43e](https://linux-hardware.org/?probe=abd15de43e) | Apr 08, 2022 |
| Gigabyte      | Z77M-D3H-MVP                | [8ee23e0e96](https://linux-hardware.org/?probe=8ee23e0e96) | Apr 08, 2022 |
| ASRock        | Z77 Extreme4                | [3524c0ef61](https://linux-hardware.org/?probe=3524c0ef61) | Apr 08, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [21bef916af](https://linux-hardware.org/?probe=21bef916af) | Apr 08, 2022 |
| Unknown       | Unknown                     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| ASUSTek       | PRIME B450M-A II            | [61d0948083](https://linux-hardware.org/?probe=61d0948083) | Apr 08, 2022 |
| ASUSTek       | H170 PRO GAMING             | [88d231a24a](https://linux-hardware.org/?probe=88d231a24a) | Apr 08, 2022 |
| Gigabyte      | A320M-H-CF                  | [256bfd0a56](https://linux-hardware.org/?probe=256bfd0a56) | Apr 08, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f0bec097a1](https://linux-hardware.org/?probe=f0bec097a1) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ed6ff884fc](https://linux-hardware.org/?probe=ed6ff884fc) | Apr 08, 2022 |
| ASUSTek       | PRIME B550M-A               | [916ca76bb0](https://linux-hardware.org/?probe=916ca76bb0) | Apr 08, 2022 |
| HP            | 1998                        | [0ed4dbebcb](https://linux-hardware.org/?probe=0ed4dbebcb) | Apr 08, 2022 |
| ASRock        | N68-S3 FX                   | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| Intel         | Unknown                     | [28f0edef8f](https://linux-hardware.org/?probe=28f0edef8f) | Apr 08, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [ab08910014](https://linux-hardware.org/?probe=ab08910014) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d75f38ec35](https://linux-hardware.org/?probe=d75f38ec35) | Apr 08, 2022 |
| Biostar       | J3060NH                     | [33bc76917c](https://linux-hardware.org/?probe=33bc76917c) | Apr 08, 2022 |
| MSI           | 785GT-E63                   | [7e7ad6f032](https://linux-hardware.org/?probe=7e7ad6f032) | Apr 08, 2022 |
| ASRock        | 990FX Extreme3              | [74624f8363](https://linux-hardware.org/?probe=74624f8363) | Apr 08, 2022 |
| MSI           | A320M-HDV R4.0              | [b06f6f6879](https://linux-hardware.org/?probe=b06f6f6879) | Apr 08, 2022 |
| Unknown       | HX90                        | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| ASRock        | X470 Taichi                 | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| Gigabyte      | Z77-HD4                     | [6162b961f2](https://linux-hardware.org/?probe=6162b961f2) | Apr 07, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| MSI           | Z270 TOMAHAWK               | [4063e06462](https://linux-hardware.org/?probe=4063e06462) | Apr 07, 2022 |
| ASRock        | Z270 Extreme4               | [526a5a16bd](https://linux-hardware.org/?probe=526a5a16bd) | Apr 07, 2022 |
| ASRock        | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| MSI           | MAG B550 TORPEDO            | [ce26da001a](https://linux-hardware.org/?probe=ce26da001a) | Apr 07, 2022 |
| MSI           | B450M MORTAR MAX            | [bde8b0ab3c](https://linux-hardware.org/?probe=bde8b0ab3c) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| Unknown       | Unknown                     | [a78f13de9e](https://linux-hardware.org/?probe=a78f13de9e) | Apr 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ac05d8917](https://linux-hardware.org/?probe=8ac05d8917) | Apr 07, 2022 |
| Gigabyte      | B365M GAMING HD             | [94b6fc5131](https://linux-hardware.org/?probe=94b6fc5131) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| Biostar       | N68S3B                      | [9410ef1116](https://linux-hardware.org/?probe=9410ef1116) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [c5ea221f34](https://linux-hardware.org/?probe=c5ea221f34) | Apr 07, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| ECS           | Nettle2                     | [65cedbb00d](https://linux-hardware.org/?probe=65cedbb00d) | Apr 07, 2022 |
| MSI           | Z87-G41 PC Mate             | [f1f94d1273](https://linux-hardware.org/?probe=f1f94d1273) | Apr 07, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| HP            | 81C9                        | [80ec21f760](https://linux-hardware.org/?probe=80ec21f760) | Apr 07, 2022 |
| ASRock        | Z87 Extreme6                | [7d74be6897](https://linux-hardware.org/?probe=7d74be6897) | Apr 07, 2022 |
| ASRock        | P67 Pro3                    | [c427c69a65](https://linux-hardware.org/?probe=c427c69a65) | Apr 07, 2022 |
| ASUSTek       | P5G41T-M LX                 | [99867ab905](https://linux-hardware.org/?probe=99867ab905) | Apr 07, 2022 |
| MSI           | X370 GAMING PLUS            | [1c1830c301](https://linux-hardware.org/?probe=1c1830c301) | Apr 07, 2022 |
| Dell          | 042P49 A02                  | [527c75b918](https://linux-hardware.org/?probe=527c75b918) | Apr 07, 2022 |
| ASUSTek       | P5G41T-M LX                 | [d51c806d3e](https://linux-hardware.org/?probe=d51c806d3e) | Apr 07, 2022 |
| MSI           | Z370-A PRO                  | [52f833f67d](https://linux-hardware.org/?probe=52f833f67d) | Apr 07, 2022 |
| Gigabyte      | H310M H                     | [e392bf72e9](https://linux-hardware.org/?probe=e392bf72e9) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Intel         | DQ965GF AAD41676-601        | [61fca7acbc](https://linux-hardware.org/?probe=61fca7acbc) | Apr 07, 2022 |
| ASUSTek       | H110M-K                     | [5d846383e8](https://linux-hardware.org/?probe=5d846383e8) | Apr 07, 2022 |
| MSI           | MS-7365                     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| ASUSTek       | P8B75-M                     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [7d87907153](https://linux-hardware.org/?probe=7d87907153) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [41fc926d28](https://linux-hardware.org/?probe=41fc926d28) | Apr 07, 2022 |
| Intel         | STK2MV64CC H89290-502       | [b2cb31c994](https://linux-hardware.org/?probe=b2cb31c994) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [586edef1b9](https://linux-hardware.org/?probe=586edef1b9) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [bb881ed0ee](https://linux-hardware.org/?probe=bb881ed0ee) | Apr 07, 2022 |
| ECS           | IC55H-A                     | [932ee208e2](https://linux-hardware.org/?probe=932ee208e2) | Apr 07, 2022 |
| MSI           | FM2-A75MA-E35               | [b691235c0f](https://linux-hardware.org/?probe=b691235c0f) | Apr 07, 2022 |
| ASUSTek       | Z97-K                       | [6451bf5197](https://linux-hardware.org/?probe=6451bf5197) | Apr 07, 2022 |
| Gigabyte      | 970A-UD3P                   | [5b3b1df897](https://linux-hardware.org/?probe=5b3b1df897) | Apr 07, 2022 |
| Gigabyte      | GA-870A-UD3                 | [c049a4a3a5](https://linux-hardware.org/?probe=c049a4a3a5) | Apr 07, 2022 |
| MSI           | Z77A-GD65                   | [030e3f6ea9](https://linux-hardware.org/?probe=030e3f6ea9) | Apr 07, 2022 |
| ASUSTek       | B85M-G                      | [c58e24cff5](https://linux-hardware.org/?probe=c58e24cff5) | Apr 07, 2022 |
| Gigabyte      | H410M H V3                  | [1a1c86083e](https://linux-hardware.org/?probe=1a1c86083e) | Apr 07, 2022 |
| Gigabyte      | 945PL-S3                    | [ef7f30cc40](https://linux-hardware.org/?probe=ef7f30cc40) | Apr 07, 2022 |
| Unknown       | X79-P3                      | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| MSI           | H81M-P33                    | [2dc40369ce](https://linux-hardware.org/?probe=2dc40369ce) | Apr 07, 2022 |
| Alienware     | 0H869M A00                  | [f6a1c02c3e](https://linux-hardware.org/?probe=f6a1c02c3e) | Apr 07, 2022 |
| HP            | 18E7                        | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| Gigabyte      | B550M DS3H                  | [9f9fb57ade](https://linux-hardware.org/?probe=9f9fb57ade) | Apr 07, 2022 |
| Gigabyte      | W480 VISION D               | [da6d84cf89](https://linux-hardware.org/?probe=da6d84cf89) | Apr 07, 2022 |
| Dell          | 0TP406                      | [13fa76c1c5](https://linux-hardware.org/?probe=13fa76c1c5) | Apr 07, 2022 |
| ASUSTek       | PRIME H510M-K               | [3b8c5ecec8](https://linux-hardware.org/?probe=3b8c5ecec8) | Apr 07, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1b6a57154d](https://linux-hardware.org/?probe=1b6a57154d) | Apr 07, 2022 |
| ASRock        | H310CM-ITX/ac               | [60948d1473](https://linux-hardware.org/?probe=60948d1473) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | [c610098aac](https://linux-hardware.org/?probe=c610098aac) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [b9eb04d2d8](https://linux-hardware.org/?probe=b9eb04d2d8) | Apr 07, 2022 |
| ASRock        | H61M-VS                     | [92e741954d](https://linux-hardware.org/?probe=92e741954d) | Apr 07, 2022 |
| ASRock        | A520M Pro4                  | [28320f2e89](https://linux-hardware.org/?probe=28320f2e89) | Apr 07, 2022 |
| Dell          | 0VRWRC A00                  | [a9b44e63a1](https://linux-hardware.org/?probe=a9b44e63a1) | Apr 07, 2022 |
| Unknown       | Unknown                     | [d9aef69378](https://linux-hardware.org/?probe=d9aef69378) | Apr 07, 2022 |
| ASUSTek       | PRIME H510M-K               | [311f56085c](https://linux-hardware.org/?probe=311f56085c) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| ASRock        | A520M Pro4                  | [6d1749cb4b](https://linux-hardware.org/?probe=6d1749cb4b) | Apr 07, 2022 |
| ASRock        | A520M Pro4                  | [1eecc7b812](https://linux-hardware.org/?probe=1eecc7b812) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5370b9e906](https://linux-hardware.org/?probe=5370b9e906) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [b925472f54](https://linux-hardware.org/?probe=b925472f54) | Apr 07, 2022 |
| Dell          | 0VD5HY A04                  | [8672ef6c18](https://linux-hardware.org/?probe=8672ef6c18) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [686ef53bc5](https://linux-hardware.org/?probe=686ef53bc5) | Apr 07, 2022 |
| Acer          | Aspire TC-705               | [6f1264f62e](https://linux-hardware.org/?probe=6f1264f62e) | Apr 07, 2022 |
| ASUSTek       | Z10PG-D16 Series            | [9076954881](https://linux-hardware.org/?probe=9076954881) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [3cb9a7fe16](https://linux-hardware.org/?probe=3cb9a7fe16) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [43a479ebfa](https://linux-hardware.org/?probe=43a479ebfa) | Apr 07, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [9f6e1da5bd](https://linux-hardware.org/?probe=9f6e1da5bd) | Apr 07, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [91c32e3a92](https://linux-hardware.org/?probe=91c32e3a92) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS M                | [ff329f98b5](https://linux-hardware.org/?probe=ff329f98b5) | Apr 07, 2022 |
| ASUSTek       | P5BV-C/4L                   | [b1eba1811a](https://linux-hardware.org/?probe=b1eba1811a) | Apr 07, 2022 |
| Gigabyte      | H77N-WIFI                   | [e31d973f5e](https://linux-hardware.org/?probe=e31d973f5e) | Apr 07, 2022 |
| Unknown       | Unknown                     | [d1b6ca0f16](https://linux-hardware.org/?probe=d1b6ca0f16) | Apr 07, 2022 |
| ASUSTek       | P5G41C-M                    | [438a8f1001](https://linux-hardware.org/?probe=438a8f1001) | Apr 07, 2022 |
| Dell          | 0WG855                      | [17ad6cf614](https://linux-hardware.org/?probe=17ad6cf614) | Apr 07, 2022 |
| ASRock        | P67 Pro3                    | [74599c7684](https://linux-hardware.org/?probe=74599c7684) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fa9314716d](https://linux-hardware.org/?probe=fa9314716d) | Apr 07, 2022 |
| Unknown       | K8M800-8237                 | [791e4eeaae](https://linux-hardware.org/?probe=791e4eeaae) | Apr 07, 2022 |
| Unknown       | K8M800-8237                 | [3447b4c67a](https://linux-hardware.org/?probe=3447b4c67a) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| Dell          | 018D1Y A00                  | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ee828b2c8b](https://linux-hardware.org/?probe=ee828b2c8b) | Apr 07, 2022 |
| Unknown       | HX90                        | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| ASRock        | Z390 Phantom Gaming 4S/a... | [836d139ea0](https://linux-hardware.org/?probe=836d139ea0) | Apr 07, 2022 |
| Unknown       | HX90                        | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | [150570ed10](https://linux-hardware.org/?probe=150570ed10) | Apr 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ba327aee7](https://linux-hardware.org/?probe=8ba327aee7) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [761e954b86](https://linux-hardware.org/?probe=761e954b86) | Apr 07, 2022 |
| Dell          | 0RY007                      | [5ce0e84669](https://linux-hardware.org/?probe=5ce0e84669) | Apr 07, 2022 |
| ASUSTek       | P5Q-E                       | [224591ad3c](https://linux-hardware.org/?probe=224591ad3c) | Apr 07, 2022 |
| ASRock        | 990FX Extreme3              | [d7ca137052](https://linux-hardware.org/?probe=d7ca137052) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| MSI           | B450-A PRO                  | [682206ff84](https://linux-hardware.org/?probe=682206ff84) | Apr 07, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [111167cacb](https://linux-hardware.org/?probe=111167cacb) | Apr 07, 2022 |
| ASUSTek       | P5Q-E                       | [93aa02920a](https://linux-hardware.org/?probe=93aa02920a) | Apr 07, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [d1f213c4f0](https://linux-hardware.org/?probe=d1f213c4f0) | Apr 07, 2022 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [45c9919e96](https://linux-hardware.org/?probe=45c9919e96) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | [4440e8ed7c](https://linux-hardware.org/?probe=4440e8ed7c) | Apr 07, 2022 |
| Intel         | X99                         | [4b1591958f](https://linux-hardware.org/?probe=4b1591958f) | Apr 06, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [e50ab269b2](https://linux-hardware.org/?probe=e50ab269b2) | Apr 06, 2022 |
| Gigabyte      | B450M DS3H V2               | [c5b2bc51dc](https://linux-hardware.org/?probe=c5b2bc51dc) | Apr 06, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | [269e88405a](https://linux-hardware.org/?probe=269e88405a) | Apr 06, 2022 |
| ASRock        | H310CM-HDV/M.2              | [e5ab1a3e96](https://linux-hardware.org/?probe=e5ab1a3e96) | Apr 06, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [f76a15be2a](https://linux-hardware.org/?probe=f76a15be2a) | Apr 06, 2022 |
| Acer          | Aspire XC-605               | [201896f70b](https://linux-hardware.org/?probe=201896f70b) | Apr 06, 2022 |
| MSI           | B360-A PRO                  | [9db9a23b5d](https://linux-hardware.org/?probe=9db9a23b5d) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c1e66c6b66](https://linux-hardware.org/?probe=c1e66c6b66) | Apr 06, 2022 |
| Dell          | 0JP3NX A01                  | [159b7c81e0](https://linux-hardware.org/?probe=159b7c81e0) | Apr 06, 2022 |
| MSI           | Z87I GAMING AC              | [f9596aa625](https://linux-hardware.org/?probe=f9596aa625) | Apr 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| MSI           | Z370-A PRO                  | [c4f0f0573c](https://linux-hardware.org/?probe=c4f0f0573c) | Apr 06, 2022 |
| ASUSTek       | P9X79                       | [e42a83e13e](https://linux-hardware.org/?probe=e42a83e13e) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [56244d6def](https://linux-hardware.org/?probe=56244d6def) | Apr 06, 2022 |
| HP            | 0AA8h                       | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| Dell          | 0WG855                      | [e7d59a199c](https://linux-hardware.org/?probe=e7d59a199c) | Apr 06, 2022 |
| Gigabyte      | G41MT-S2PT                  | [d0a71a4c13](https://linux-hardware.org/?probe=d0a71a4c13) | Apr 06, 2022 |
| ASUSTek       | A88XM-A                     | [0f8ce13fb9](https://linux-hardware.org/?probe=0f8ce13fb9) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | G41M-P28                    | [b19249859b](https://linux-hardware.org/?probe=b19249859b) | Apr 06, 2022 |
| Gigabyte      | G41MT-S2PT                  | [17f2b9f011](https://linux-hardware.org/?probe=17f2b9f011) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Biostar       | A55ML2                      | [11d2b22b90](https://linux-hardware.org/?probe=11d2b22b90) | Apr 06, 2022 |
| BESSTAR Te... | HM90                        | [202fc7c2a2](https://linux-hardware.org/?probe=202fc7c2a2) | Apr 06, 2022 |
| Biostar       | H61MHV2                     | [c14aa9ce1a](https://linux-hardware.org/?probe=c14aa9ce1a) | Apr 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [55568ec828](https://linux-hardware.org/?probe=55568ec828) | Apr 06, 2022 |
| ASUSTek       | Z97-K                       | [605aa4f068](https://linux-hardware.org/?probe=605aa4f068) | Apr 06, 2022 |
| Dell          | 0VNP2H A01                  | [ce01d1704a](https://linux-hardware.org/?probe=ce01d1704a) | Apr 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Dell          | 0U880P A01                  | [584ec9a64f](https://linux-hardware.org/?probe=584ec9a64f) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| Dell          | 0U880P A01                  | [54c8306a14](https://linux-hardware.org/?probe=54c8306a14) | Apr 06, 2022 |
| MSI           | Z390-A PRO                  | [4e232c446f](https://linux-hardware.org/?probe=4e232c446f) | Apr 06, 2022 |
| HP            | 1588h                       | [0729a9b12d](https://linux-hardware.org/?probe=0729a9b12d) | Apr 06, 2022 |
| Dell          | 0TP406                      | [28425b209c](https://linux-hardware.org/?probe=28425b209c) | Apr 06, 2022 |
| Dell          | 0TP406                      | [8805b80b73](https://linux-hardware.org/?probe=8805b80b73) | Apr 06, 2022 |
| MSI           | MS-7358 Fab D               | [1867be94e3](https://linux-hardware.org/?probe=1867be94e3) | Apr 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [a3d3ff5ac5](https://linux-hardware.org/?probe=a3d3ff5ac5) | Apr 06, 2022 |
| ASRock        | H310CM-HDV/M.2              | [58802c5c79](https://linux-hardware.org/?probe=58802c5c79) | Apr 06, 2022 |
| Unknown       | H510I                       | [ff0188e03f](https://linux-hardware.org/?probe=ff0188e03f) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [eff608a49e](https://linux-hardware.org/?probe=eff608a49e) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [a2cbf77c20](https://linux-hardware.org/?probe=a2cbf77c20) | Apr 06, 2022 |
| Dell          | 0Y2MRG A00                  | [d764d51af9](https://linux-hardware.org/?probe=d764d51af9) | Apr 06, 2022 |
| ECS           | Livermore                   | [afafdb72a7](https://linux-hardware.org/?probe=afafdb72a7) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [281a36cc7d](https://linux-hardware.org/?probe=281a36cc7d) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [b498ef386c](https://linux-hardware.org/?probe=b498ef386c) | Apr 06, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [fe9a1fff55](https://linux-hardware.org/?probe=fe9a1fff55) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [5f0fbae656](https://linux-hardware.org/?probe=5f0fbae656) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [e543d9b013](https://linux-hardware.org/?probe=e543d9b013) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [0bfc08cf7d](https://linux-hardware.org/?probe=0bfc08cf7d) | Apr 06, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [05e3166f60](https://linux-hardware.org/?probe=05e3166f60) | Apr 06, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6e2067ac48](https://linux-hardware.org/?probe=6e2067ac48) | Apr 06, 2022 |
| MSI           | H110M PRO-VH PLUS           | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| ASUSTek       | K8N-VM                      | [ec2a4f7170](https://linux-hardware.org/?probe=ec2a4f7170) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [9e22b32d6b](https://linux-hardware.org/?probe=9e22b32d6b) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [d11fa87811](https://linux-hardware.org/?probe=d11fa87811) | Apr 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| Dell          | 0M5DCD A00                  | [209a69c333](https://linux-hardware.org/?probe=209a69c333) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [01f4e56f26](https://linux-hardware.org/?probe=01f4e56f26) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [360473d244](https://linux-hardware.org/?probe=360473d244) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [7154fae7e4](https://linux-hardware.org/?probe=7154fae7e4) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [b5dcbdd4b0](https://linux-hardware.org/?probe=b5dcbdd4b0) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | [22e3c6f830](https://linux-hardware.org/?probe=22e3c6f830) | Apr 06, 2022 |
| SYWZ          | S200 Series                 | [8c4c52cd9b](https://linux-hardware.org/?probe=8c4c52cd9b) | Apr 06, 2022 |
| ASUSTek       | PRIME H370M-PLUS            | [efae0e63ab](https://linux-hardware.org/?probe=efae0e63ab) | Apr 06, 2022 |
| ASUSTek       | P8B75-M                     | [39ab6f56fb](https://linux-hardware.org/?probe=39ab6f56fb) | Apr 06, 2022 |
| Unknown       | Unknown                     | [c8049ac14a](https://linux-hardware.org/?probe=c8049ac14a) | Apr 06, 2022 |
| ASUSTek       | Z170M-PLUS                  | [2ab4d273c1](https://linux-hardware.org/?probe=2ab4d273c1) | Apr 06, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [203b65a3f5](https://linux-hardware.org/?probe=203b65a3f5) | Apr 06, 2022 |
| ASRock        | 970 Pro3 R2.0               | [59479b59ec](https://linux-hardware.org/?probe=59479b59ec) | Apr 06, 2022 |
| ASUSTek       | Z87-K                       | [41f654dc20](https://linux-hardware.org/?probe=41f654dc20) | Apr 06, 2022 |
| Gigabyte      | B360M D2V                   | [87f55ffa54](https://linux-hardware.org/?probe=87f55ffa54) | Apr 06, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [257046178c](https://linux-hardware.org/?probe=257046178c) | Apr 06, 2022 |
| ASUSTek       | A68HM-E                     | [af6b7df94c](https://linux-hardware.org/?probe=af6b7df94c) | Apr 06, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [ef16b5252f](https://linux-hardware.org/?probe=ef16b5252f) | Apr 06, 2022 |
| Gigabyte      | H410M H V3                  | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [8aad15d96c](https://linux-hardware.org/?probe=8aad15d96c) | Apr 06, 2022 |
| Foxconn       | H61MD/H61MD-V               | [7bb124e322](https://linux-hardware.org/?probe=7bb124e322) | Apr 06, 2022 |
| ASUSTek       | P5GC-MX                     | [ce2aaa12ab](https://linux-hardware.org/?probe=ce2aaa12ab) | Apr 06, 2022 |
| HP            | 0A08h                       | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [aad4b24a04](https://linux-hardware.org/?probe=aad4b24a04) | Apr 06, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [dff8141976](https://linux-hardware.org/?probe=dff8141976) | Apr 06, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [cc10884386](https://linux-hardware.org/?probe=cc10884386) | Apr 06, 2022 |
| MSI           | X79A-GD45 Plus              | [557106dcd8](https://linux-hardware.org/?probe=557106dcd8) | Apr 06, 2022 |
| Unknown       | P4M800CE-8237               | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [e20e2247c0](https://linux-hardware.org/?probe=e20e2247c0) | Apr 06, 2022 |
| ASRock        | FM2A78M-ITX+                | [63799d0adb](https://linux-hardware.org/?probe=63799d0adb) | Apr 06, 2022 |
| Alienware     | 04VWF2 A02                  | [1637810ad2](https://linux-hardware.org/?probe=1637810ad2) | Apr 06, 2022 |
| HP            | 2129                        | [bb9c98d729](https://linux-hardware.org/?probe=bb9c98d729) | Apr 06, 2022 |
| Gigabyte      | B450 AORUS M                | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [53e59cf805](https://linux-hardware.org/?probe=53e59cf805) | Apr 06, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [802551fe50](https://linux-hardware.org/?probe=802551fe50) | Apr 06, 2022 |
| ASUSTek       | P8B75-M LE                  | [e5cdfad4e6](https://linux-hardware.org/?probe=e5cdfad4e6) | Apr 06, 2022 |
| Dell          | 0N4YC8 A00                  | [97c87cecd7](https://linux-hardware.org/?probe=97c87cecd7) | Apr 06, 2022 |
| Dell          | 0D24M8 A00                  | [4f81a4a54a](https://linux-hardware.org/?probe=4f81a4a54a) | Apr 06, 2022 |
| ASRock        | Z97 Pro3                    | [68397184cf](https://linux-hardware.org/?probe=68397184cf) | Apr 06, 2022 |
| MSI           | FM2-A75MA-E35               | [231d07274a](https://linux-hardware.org/?probe=231d07274a) | Apr 06, 2022 |
| ASUSTek       | A8N-VM CSM                  | [eac824e348](https://linux-hardware.org/?probe=eac824e348) | Apr 06, 2022 |
| HP            | 18E5                        | [b79c804a6a](https://linux-hardware.org/?probe=b79c804a6a) | Apr 05, 2022 |
| Gigabyte      | B550M DS3H                  | [0cca11beab](https://linux-hardware.org/?probe=0cca11beab) | Apr 05, 2022 |
| MSI           | Z97 PC Mate                 | [0e99e2c6cb](https://linux-hardware.org/?probe=0e99e2c6cb) | Apr 05, 2022 |
| Gigabyte      | H470M DS3H                  | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| Unknown       | RS690-SB600                 | [19ae42107e](https://linux-hardware.org/?probe=19ae42107e) | Apr 05, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| Biostar       | H110MHC                     | [09715fbaf2](https://linux-hardware.org/?probe=09715fbaf2) | Apr 05, 2022 |
| MSI           | X58M                        | [d4146d0724](https://linux-hardware.org/?probe=d4146d0724) | Apr 05, 2022 |
| Intel         | DH55TC AAE70932-204         | [336fcaa613](https://linux-hardware.org/?probe=336fcaa613) | Apr 05, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f5106f79ee](https://linux-hardware.org/?probe=f5106f79ee) | Apr 05, 2022 |
| MSI           | 2A9C                        | [d56d880fd1](https://linux-hardware.org/?probe=d56d880fd1) | Apr 05, 2022 |
| Gigabyte      | GA-970A-DS3                 | [200d7fafb9](https://linux-hardware.org/?probe=200d7fafb9) | Apr 05, 2022 |
| ASRock        | B365M-HDV                   | [55622262b1](https://linux-hardware.org/?probe=55622262b1) | Apr 05, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [b1050b51ec](https://linux-hardware.org/?probe=b1050b51ec) | Apr 05, 2022 |
| MSI           | Eclipse SLI                 | [e488b9407a](https://linux-hardware.org/?probe=e488b9407a) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| ASRock        | B365M-HDV                   | [9dda2b0575](https://linux-hardware.org/?probe=9dda2b0575) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| Biostar       | TB250-BTC                   | [d6ef15453d](https://linux-hardware.org/?probe=d6ef15453d) | Apr 05, 2022 |
| Gigabyte      | 970A-DS3P                   | [1a090182c2](https://linux-hardware.org/?probe=1a090182c2) | Apr 05, 2022 |
| ASUSTek       | Z170-A                      | [68512f2b49](https://linux-hardware.org/?probe=68512f2b49) | Apr 05, 2022 |
| ASUSTek       | M5A78L-M LX3                | [b642303f8e](https://linux-hardware.org/?probe=b642303f8e) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [30591629c3](https://linux-hardware.org/?probe=30591629c3) | Apr 05, 2022 |
| ASUSTek       | PRIME H510M-E               | [77b4a03b19](https://linux-hardware.org/?probe=77b4a03b19) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [8181b0cd19](https://linux-hardware.org/?probe=8181b0cd19) | Apr 05, 2022 |
| MSI           | Eclipse SLI                 | [aebfec44b2](https://linux-hardware.org/?probe=aebfec44b2) | Apr 05, 2022 |
| ASUSTek       | Z170-A                      | [a3d0521e54](https://linux-hardware.org/?probe=a3d0521e54) | Apr 05, 2022 |
| MSI           | G41M-P33 Combo              | [2290edabe7](https://linux-hardware.org/?probe=2290edabe7) | Apr 05, 2022 |
| ASUSTek       | B560M-A PRIME               | [1aff04b3de](https://linux-hardware.org/?probe=1aff04b3de) | Apr 05, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [939722b6a7](https://linux-hardware.org/?probe=939722b6a7) | Apr 05, 2022 |
| Dell          | 0GY6Y8 A03                  | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | 0DR845                      | [d7fc0864f8](https://linux-hardware.org/?probe=d7fc0864f8) | Apr 05, 2022 |
| HP            | 3047h                       | [6766d428ef](https://linux-hardware.org/?probe=6766d428ef) | Apr 05, 2022 |
| ASRock        | B450 Pro4                   | [65e855a6a5](https://linux-hardware.org/?probe=65e855a6a5) | Apr 05, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | [6c25d1250d](https://linux-hardware.org/?probe=6c25d1250d) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [dd1fef9175](https://linux-hardware.org/?probe=dd1fef9175) | Apr 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3c27532090](https://linux-hardware.org/?probe=3c27532090) | Apr 05, 2022 |
| Gigabyte      | B450M DS3H-CF               | [adf960d914](https://linux-hardware.org/?probe=adf960d914) | Apr 05, 2022 |
| ASUSTek       | K8N-VM                      | [d914bc84e9](https://linux-hardware.org/?probe=d914bc84e9) | Apr 05, 2022 |
| ASUSTek       | VM62                        | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| Gigabyte      | H270N-WIFI-CF               | [fe6d2db0dd](https://linux-hardware.org/?probe=fe6d2db0dd) | Apr 05, 2022 |
| MSI           | Z590 PRO WIFI               | [e7576083a0](https://linux-hardware.org/?probe=e7576083a0) | Apr 05, 2022 |
| Dell          | 0HY9JP A02                  | [ed1cda9998](https://linux-hardware.org/?probe=ed1cda9998) | Apr 05, 2022 |
| Unknown       | Unknown                     | [d57ec60736](https://linux-hardware.org/?probe=d57ec60736) | Apr 05, 2022 |
| Dell          | 09D2HH A00                  | [ed5450f496](https://linux-hardware.org/?probe=ed5450f496) | Apr 05, 2022 |
| Gigabyte      | H87M-HD3                    | [76eb57cf5e](https://linux-hardware.org/?probe=76eb57cf5e) | Apr 05, 2022 |
| Gigabyte      | H410M S2H                   | [0cf5e3004f](https://linux-hardware.org/?probe=0cf5e3004f) | Apr 05, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| ASRock        | Z97X Killer                 | [628d137846](https://linux-hardware.org/?probe=628d137846) | Apr 05, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c95df20756](https://linux-hardware.org/?probe=c95df20756) | Apr 05, 2022 |
| ASUSTek       | PRIME H510M-A               | [1737ff348a](https://linux-hardware.org/?probe=1737ff348a) | Apr 05, 2022 |
| HP            | 1494                        | [5d81c1dd3c](https://linux-hardware.org/?probe=5d81c1dd3c) | Apr 05, 2022 |
| Intel         | D945GCF AAD73937-203        | [e9a0b1b355](https://linux-hardware.org/?probe=e9a0b1b355) | Apr 05, 2022 |
| Gigabyte      | X570 AORUS PRO              | [fe22c5530c](https://linux-hardware.org/?probe=fe22c5530c) | Apr 05, 2022 |
| Gigabyte      | G31M-S2L                    | [7842a96018](https://linux-hardware.org/?probe=7842a96018) | Apr 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f98a0cf73b](https://linux-hardware.org/?probe=f98a0cf73b) | Apr 05, 2022 |
| ASUSTek       | P9X79                       | [d82eb40c27](https://linux-hardware.org/?probe=d82eb40c27) | Apr 05, 2022 |
| HP            | 0A9Ch                       | [5a415a150f](https://linux-hardware.org/?probe=5a415a150f) | Apr 05, 2022 |
| ECS           | CMLU-MINI                   | [742c0da37b](https://linux-hardware.org/?probe=742c0da37b) | Apr 05, 2022 |
| Gigabyte      | B450M S2H                   | [046d0eb6c8](https://linux-hardware.org/?probe=046d0eb6c8) | Apr 05, 2022 |
| Gigabyte      | H97M-HD3                    | [fc7b16c289](https://linux-hardware.org/?probe=fc7b16c289) | Apr 05, 2022 |
| Dell          | 09KPNV A00                  | [0a06779a5a](https://linux-hardware.org/?probe=0a06779a5a) | Apr 05, 2022 |
| ASUSTek       | P8B75-M                     | [bc01cf4afc](https://linux-hardware.org/?probe=bc01cf4afc) | Apr 05, 2022 |
| ASUSTek       | H87-PRO                     | [0d18744bdf](https://linux-hardware.org/?probe=0d18744bdf) | Apr 05, 2022 |
| Lenovo        | MAHOBAY                     | [ad714d63bc](https://linux-hardware.org/?probe=ad714d63bc) | Apr 05, 2022 |
| ASUSTek       | P5Q SE PLUS                 | [bb16122030](https://linux-hardware.org/?probe=bb16122030) | Apr 05, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [65c7660b74](https://linux-hardware.org/?probe=65c7660b74) | Apr 05, 2022 |
| Gigabyte      | F2A68HM-HD2                 | [cb0794850f](https://linux-hardware.org/?probe=cb0794850f) | Apr 05, 2022 |
| ASUSTek       | M3A78-EH                    | [4298b6c9dc](https://linux-hardware.org/?probe=4298b6c9dc) | Apr 05, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [5600c7649a](https://linux-hardware.org/?probe=5600c7649a) | Apr 05, 2022 |
| Gigabyte      | B75M-D3H                    | [79aee125b7](https://linux-hardware.org/?probe=79aee125b7) | Apr 05, 2022 |
| ASRock        | P67 Pro3                    | [12aa7e9d62](https://linux-hardware.org/?probe=12aa7e9d62) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d2f9498bd2](https://linux-hardware.org/?probe=d2f9498bd2) | Apr 05, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Foxconn       | 2A92                        | [dd802e925f](https://linux-hardware.org/?probe=dd802e925f) | Apr 05, 2022 |
| HP            | 0B48h                       | [7cd0cbb7b7](https://linux-hardware.org/?probe=7cd0cbb7b7) | Apr 05, 2022 |
| ASUSTek       | X99-DELUXE II               | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | [770088302a](https://linux-hardware.org/?probe=770088302a) | Apr 05, 2022 |
| Gigabyte      | H81M-S2H                    | [ac5d29c839](https://linux-hardware.org/?probe=ac5d29c839) | Apr 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ac84af49ea](https://linux-hardware.org/?probe=ac84af49ea) | Apr 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8a3966d71c](https://linux-hardware.org/?probe=8a3966d71c) | Apr 05, 2022 |
| Intel         | DN2820FYB H24582-205        | [a19db5a006](https://linux-hardware.org/?probe=a19db5a006) | Apr 05, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [f3bc34e630](https://linux-hardware.org/?probe=f3bc34e630) | Apr 05, 2022 |
| ASUSTek       | M3A78-CM                    | [718536ba53](https://linux-hardware.org/?probe=718536ba53) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [db18e71352](https://linux-hardware.org/?probe=db18e71352) | Apr 05, 2022 |
| MSI           | B360-A PRO                  | [aa22c203eb](https://linux-hardware.org/?probe=aa22c203eb) | Apr 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | [d7bf7b48a1](https://linux-hardware.org/?probe=d7bf7b48a1) | Apr 05, 2022 |
| ASUSTek       | Z97-A-USB31                 | [cd6f73403e](https://linux-hardware.org/?probe=cd6f73403e) | Apr 05, 2022 |
| Unknown       | Unknown                     | [8f491b9fc2](https://linux-hardware.org/?probe=8f491b9fc2) | Apr 05, 2022 |
| MSI           | MS-7204                     | [e04077c3ac](https://linux-hardware.org/?probe=e04077c3ac) | Apr 05, 2022 |
| Intel         | H61                         | [d378493561](https://linux-hardware.org/?probe=d378493561) | Apr 05, 2022 |
| MSI           | MS-7204                     | [817c6f06bf](https://linux-hardware.org/?probe=817c6f06bf) | Apr 05, 2022 |
| Acer          | Aspire XC-603               | [ef344607ad](https://linux-hardware.org/?probe=ef344607ad) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| Gigabyte      | G41MT-S2PT                  | [1a54aa07e3](https://linux-hardware.org/?probe=1a54aa07e3) | Apr 04, 2022 |
| ASUSTek       | Z87-PRO                     | [ca1d842423](https://linux-hardware.org/?probe=ca1d842423) | Apr 04, 2022 |
| Dell          | 0T656F A02                  | [260c2183c2](https://linux-hardware.org/?probe=260c2183c2) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [fe7fdad91b](https://linux-hardware.org/?probe=fe7fdad91b) | Apr 04, 2022 |
| MSI           | H510M PRO                   | [0874882b3f](https://linux-hardware.org/?probe=0874882b3f) | Apr 04, 2022 |
| ASUSTek       | P5Q DELUXE                  | [1c37d5b9ed](https://linux-hardware.org/?probe=1c37d5b9ed) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [a26b03795a](https://linux-hardware.org/?probe=a26b03795a) | Apr 04, 2022 |
| ASUSTek       | M4A78LT-M                   | [ea53fbbc2a](https://linux-hardware.org/?probe=ea53fbbc2a) | Apr 04, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [7e44cf1d2c](https://linux-hardware.org/?probe=7e44cf1d2c) | Apr 04, 2022 |
| Dell          | 0DR845                      | [26a919fc82](https://linux-hardware.org/?probe=26a919fc82) | Apr 04, 2022 |
| ASRock        | B85M                        | [5e03e9532d](https://linux-hardware.org/?probe=5e03e9532d) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [d467a8e89f](https://linux-hardware.org/?probe=d467a8e89f) | Apr 04, 2022 |
| ASRock        | B450 Pro4                   | [47ff657a18](https://linux-hardware.org/?probe=47ff657a18) | Apr 04, 2022 |
| Packard Be... | IMEDIA S2110A               | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| Foxconn       | 2A8C                        | [e4d8c4ccf0](https://linux-hardware.org/?probe=e4d8c4ccf0) | Apr 04, 2022 |
| Dell          | 02YRK5 A03                  | [8f30fb0a3f](https://linux-hardware.org/?probe=8f30fb0a3f) | Apr 04, 2022 |
| Dell          | 0CT017                      | [27bdeec11d](https://linux-hardware.org/?probe=27bdeec11d) | Apr 04, 2022 |
| ASUSTek       | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Dell          | 02YRK5 A03                  | [4014bf184c](https://linux-hardware.org/?probe=4014bf184c) | Apr 04, 2022 |
| Dell          | 0WR7PY A02                  | [3086c641fb](https://linux-hardware.org/?probe=3086c641fb) | Apr 04, 2022 |
| Gigabyte      | G41MT-S2PT                  | [9d1398934f](https://linux-hardware.org/?probe=9d1398934f) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [26032ef606](https://linux-hardware.org/?probe=26032ef606) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [fed309fdf1](https://linux-hardware.org/?probe=fed309fdf1) | Apr 04, 2022 |
| MSI           | H510M PRO                   | [ee05ef80b8](https://linux-hardware.org/?probe=ee05ef80b8) | Apr 04, 2022 |
| HP            | 3048h                       | [2987081733](https://linux-hardware.org/?probe=2987081733) | Apr 04, 2022 |
| ASRock        | Z270 Killer SLI/ac          | [cd29715a0d](https://linux-hardware.org/?probe=cd29715a0d) | Apr 04, 2022 |
| ASUSTek       | H61M-D                      | [d22d7d52dc](https://linux-hardware.org/?probe=d22d7d52dc) | Apr 04, 2022 |
| ASRock        | G31M-VS2                    | [e618635f7e](https://linux-hardware.org/?probe=e618635f7e) | Apr 04, 2022 |
| ASRock        | P67 Pro3                    | [0b85e0a11b](https://linux-hardware.org/?probe=0b85e0a11b) | Apr 04, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [bc5ffea6a3](https://linux-hardware.org/?probe=bc5ffea6a3) | Apr 04, 2022 |
| Acer          | Aspire M1470                | [6612952747](https://linux-hardware.org/?probe=6612952747) | Apr 04, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [65a5442605](https://linux-hardware.org/?probe=65a5442605) | Apr 04, 2022 |
| Biostar       | B350GT5                     | [b8aba828d1](https://linux-hardware.org/?probe=b8aba828d1) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | [1e78710d6e](https://linux-hardware.org/?probe=1e78710d6e) | Apr 04, 2022 |
| ASUSTek       | P8H61-M LE                  | [1167744ae0](https://linux-hardware.org/?probe=1167744ae0) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [5cfb35fb9e](https://linux-hardware.org/?probe=5cfb35fb9e) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | [5712d63047](https://linux-hardware.org/?probe=5712d63047) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [42084c0823](https://linux-hardware.org/?probe=42084c0823) | Apr 04, 2022 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [2553eb95aa](https://linux-hardware.org/?probe=2553eb95aa) | Apr 04, 2022 |
| MSI           | X570-A PRO                  | [2af47af588](https://linux-hardware.org/?probe=2af47af588) | Apr 04, 2022 |
| ASUSTek       | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| MSI           | H97 PC Mate                 | [8e47753650](https://linux-hardware.org/?probe=8e47753650) | Apr 04, 2022 |
| Acer          | Aspire M3910                | [bb407c8963](https://linux-hardware.org/?probe=bb407c8963) | Apr 04, 2022 |
| MSI           | H97 PC Mate                 | [98788451c4](https://linux-hardware.org/?probe=98788451c4) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [02c8690b96](https://linux-hardware.org/?probe=02c8690b96) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [52cdca6be2](https://linux-hardware.org/?probe=52cdca6be2) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [04078826f9](https://linux-hardware.org/?probe=04078826f9) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [beff3d022a](https://linux-hardware.org/?probe=beff3d022a) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [b50bb2ee16](https://linux-hardware.org/?probe=b50bb2ee16) | Apr 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASUSTek       | P8H67-M                     | [e49282700d](https://linux-hardware.org/?probe=e49282700d) | Apr 04, 2022 |
| Dell          | 0C522T A00                  | [4a42777634](https://linux-hardware.org/?probe=4a42777634) | Apr 04, 2022 |
| ECS           | IC55H-A                     | [a0287a7cca](https://linux-hardware.org/?probe=a0287a7cca) | Apr 04, 2022 |
| MSI           | H510M PRO                   | [e11c2453c5](https://linux-hardware.org/?probe=e11c2453c5) | Apr 04, 2022 |
| HP            | 8643 SMVB                   | [f6e3225172](https://linux-hardware.org/?probe=f6e3225172) | Apr 04, 2022 |
| ASUSTek       | H81M-E                      | [2659a11330](https://linux-hardware.org/?probe=2659a11330) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [b78fd6db36](https://linux-hardware.org/?probe=b78fd6db36) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [7482990555](https://linux-hardware.org/?probe=7482990555) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [8b9056398a](https://linux-hardware.org/?probe=8b9056398a) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [6243da846e](https://linux-hardware.org/?probe=6243da846e) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [42553daa02](https://linux-hardware.org/?probe=42553daa02) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [f8fa4a854a](https://linux-hardware.org/?probe=f8fa4a854a) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [5e53b0911d](https://linux-hardware.org/?probe=5e53b0911d) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [1029c094d5](https://linux-hardware.org/?probe=1029c094d5) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [fcc9bc2d30](https://linux-hardware.org/?probe=fcc9bc2d30) | Apr 04, 2022 |
| Acer          | Aspire M1470                | [d32d46984e](https://linux-hardware.org/?probe=d32d46984e) | Apr 04, 2022 |
| Gigabyte      | H67A-UD3H-B3                | [5ccef6f1fe](https://linux-hardware.org/?probe=5ccef6f1fe) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | [a88a724049](https://linux-hardware.org/?probe=a88a724049) | Apr 04, 2022 |
| Gigabyte      | H410M H V3                  | [afc10b77f7](https://linux-hardware.org/?probe=afc10b77f7) | Apr 04, 2022 |
| ASRock        | N68C-GS FX                  | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| HP            | 2AFB                        | [5d4114c272](https://linux-hardware.org/?probe=5d4114c272) | Apr 04, 2022 |
| HP            | 2AFB                        | [6e8e6bb327](https://linux-hardware.org/?probe=6e8e6bb327) | Apr 04, 2022 |
| HP            | 2820h                       | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| HP            | 805D                        | [198cff1b8e](https://linux-hardware.org/?probe=198cff1b8e) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | [e7083be036](https://linux-hardware.org/?probe=e7083be036) | Apr 04, 2022 |
| ASUSTek       | P5B                         | [fd9454ab7a](https://linux-hardware.org/?probe=fd9454ab7a) | Apr 04, 2022 |
| Foxconn       | 2A8Ch                       | [6354cfe078](https://linux-hardware.org/?probe=6354cfe078) | Apr 04, 2022 |
| Acer          | Revo RL80                   | [414f1870b3](https://linux-hardware.org/?probe=414f1870b3) | Apr 04, 2022 |
| Shuttle       | FS35V4                      | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| Gigabyte      | G41M-ES2L                   | [864d69baab](https://linux-hardware.org/?probe=864d69baab) | Apr 04, 2022 |
| ASRock        | X470 Master SLI             | [255ce25970](https://linux-hardware.org/?probe=255ce25970) | Apr 04, 2022 |
| Gigabyte      | H55M-S2HP                   | [5079856030](https://linux-hardware.org/?probe=5079856030) | Apr 04, 2022 |
| Gigabyte      | Z590 UD AC                  | [ddd9e641ee](https://linux-hardware.org/?probe=ddd9e641ee) | Apr 04, 2022 |
| MSI           | P45 Neo-F                   | [8f1c621674](https://linux-hardware.org/?probe=8f1c621674) | Apr 04, 2022 |
| Intel         | D945GCF AAD73937-203        | [6409bdc542](https://linux-hardware.org/?probe=6409bdc542) | Apr 04, 2022 |
| MSI           | G41M-P28                    | [afb7898d63](https://linux-hardware.org/?probe=afb7898d63) | Apr 04, 2022 |
| Unknown       | Unknown                     | [214ae5185b](https://linux-hardware.org/?probe=214ae5185b) | Apr 04, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [eae759532b](https://linux-hardware.org/?probe=eae759532b) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Gigabyte      | F2A68HM-H                   | [bd5be9b918](https://linux-hardware.org/?probe=bd5be9b918) | Apr 04, 2022 |
| ASUSTek       | M5A78L-M LX                 | [2bbc147beb](https://linux-hardware.org/?probe=2bbc147beb) | Apr 04, 2022 |
| Dell          | 0Y5DDC A00                  | [71fb489ab7](https://linux-hardware.org/?probe=71fb489ab7) | Apr 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [73ecbc62b1](https://linux-hardware.org/?probe=73ecbc62b1) | Apr 04, 2022 |
| ASRock        | P67 Pro3                    | [65b4903fb8](https://linux-hardware.org/?probe=65b4903fb8) | Apr 04, 2022 |
| ASUSTek       | Z87-K                       | [8d1d44d764](https://linux-hardware.org/?probe=8d1d44d764) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [5bcff46ee9](https://linux-hardware.org/?probe=5bcff46ee9) | Apr 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | [2759f18a1f](https://linux-hardware.org/?probe=2759f18a1f) | Apr 04, 2022 |
| Gigabyte      | B75M-D3V                    | [16d1981053](https://linux-hardware.org/?probe=16d1981053) | Apr 04, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [2c39a577ac](https://linux-hardware.org/?probe=2c39a577ac) | Apr 04, 2022 |
| Gigabyte      | H110M-H-CF                  | [9ca082be16](https://linux-hardware.org/?probe=9ca082be16) | Apr 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e12e7fdd89](https://linux-hardware.org/?probe=e12e7fdd89) | Apr 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ca26fd54e1](https://linux-hardware.org/?probe=ca26fd54e1) | Apr 04, 2022 |
| ASUSTek       | WS Z390 PRO                 | [9aea13fa1b](https://linux-hardware.org/?probe=9aea13fa1b) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| MSI           | B450 TOMAHAWK               | [4008f4f114](https://linux-hardware.org/?probe=4008f4f114) | Apr 04, 2022 |
| ASUSTek       | Maximus V EXTREME           | [01ef29c80a](https://linux-hardware.org/?probe=01ef29c80a) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| MSI           | B75A-G41                    | [80ec6aed14](https://linux-hardware.org/?probe=80ec6aed14) | Apr 04, 2022 |
| HP            | 1998                        | [d30791d695](https://linux-hardware.org/?probe=d30791d695) | Apr 04, 2022 |
| Gigabyte      | H61M-DS2                    | [10ccb633ee](https://linux-hardware.org/?probe=10ccb633ee) | Apr 04, 2022 |
| HP            | 1998                        | [74f1744dce](https://linux-hardware.org/?probe=74f1744dce) | Apr 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7a354d771f](https://linux-hardware.org/?probe=7a354d771f) | Apr 04, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f067a2d929](https://linux-hardware.org/?probe=f067a2d929) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| HP            | 1790                        | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| ASUSTek       | Maximus V EXTREME           | [6e91f5c899](https://linux-hardware.org/?probe=6e91f5c899) | Apr 03, 2022 |
| ASUSTek       | PRIME B250M-K               | [cc6c7d17d9](https://linux-hardware.org/?probe=cc6c7d17d9) | Apr 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5348103896](https://linux-hardware.org/?probe=5348103896) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b13db55f03](https://linux-hardware.org/?probe=b13db55f03) | Apr 03, 2022 |
| Dell          | 0NDYHG A01                  | [26629406de](https://linux-hardware.org/?probe=26629406de) | Apr 03, 2022 |
| HP            | 8433 11                     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [df1549bb3b](https://linux-hardware.org/?probe=df1549bb3b) | Apr 03, 2022 |
| Gigabyte      | GA-990FX-GAMING             | [46756b95b5](https://linux-hardware.org/?probe=46756b95b5) | Apr 03, 2022 |
| Dell          | 06X1TJ A00                  | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
| ASUSTek       | H61M-D                      | [b9c2af0976](https://linux-hardware.org/?probe=b9c2af0976) | Apr 03, 2022 |
| Packard Be... | Cuba MS-7301                | [1a89e021cd](https://linux-hardware.org/?probe=1a89e021cd) | Apr 03, 2022 |
| EPoX Compu... | NF550/570 DDR2: AF550/57... | [2ad5eecadc](https://linux-hardware.org/?probe=2ad5eecadc) | Apr 03, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [fa6cd54c20](https://linux-hardware.org/?probe=fa6cd54c20) | Apr 03, 2022 |
| ASUSTek       | A55BM-K                     | [c0832d15d0](https://linux-hardware.org/?probe=c0832d15d0) | Apr 03, 2022 |
| HP            | 1905                        | [6a3aaab7b9](https://linux-hardware.org/?probe=6a3aaab7b9) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| ASRock        | C2750D4I                    | [b328ff82c5](https://linux-hardware.org/?probe=b328ff82c5) | Apr 03, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [d268200bd2](https://linux-hardware.org/?probe=d268200bd2) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A                | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9493efcabe](https://linux-hardware.org/?probe=9493efcabe) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| Gigabyte      | B450M S2H V2                | [f3fde51c72](https://linux-hardware.org/?probe=f3fde51c72) | Apr 03, 2022 |
| HP            | 0AA8h                       | [f599c9dc5b](https://linux-hardware.org/?probe=f599c9dc5b) | Apr 03, 2022 |
| ASUSTek       | PRIME B450M-A               | [15f71ef2b6](https://linux-hardware.org/?probe=15f71ef2b6) | Apr 03, 2022 |
| ASRock        | 970 Extreme4                | [cc65547e82](https://linux-hardware.org/?probe=cc65547e82) | Apr 03, 2022 |
| Dell          | OptiPlex 760                | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| ASUSTek       | PRIME B450M-A               | [4368fb5c23](https://linux-hardware.org/?probe=4368fb5c23) | Apr 03, 2022 |
| Dell          | 0427JK A00                  | [9349950b11](https://linux-hardware.org/?probe=9349950b11) | Apr 03, 2022 |
| ASUSTek       | PRIME H570-PLUS             | [4a9be0ab22](https://linux-hardware.org/?probe=4a9be0ab22) | Apr 03, 2022 |
| Dell          | 0427JK A00                  | [47980a5b52](https://linux-hardware.org/?probe=47980a5b52) | Apr 03, 2022 |
| ASRock        | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASRock        | H670M-ITX/ax                | [d4dc39b64e](https://linux-hardware.org/?probe=d4dc39b64e) | Apr 03, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Intel         | DH67BL AAG10189-207         | [2daa6a85f4](https://linux-hardware.org/?probe=2daa6a85f4) | Apr 03, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [bf97b221d8](https://linux-hardware.org/?probe=bf97b221d8) | Apr 03, 2022 |
| MSI           | X58M                        | [7484dce6ce](https://linux-hardware.org/?probe=7484dce6ce) | Apr 03, 2022 |
| Gigabyte      | P35C-DS3R                   | [e8ed38bd3d](https://linux-hardware.org/?probe=e8ed38bd3d) | Apr 03, 2022 |
| Acer          | Aspire X1700                | [dd39a6a660](https://linux-hardware.org/?probe=dd39a6a660) | Apr 03, 2022 |
| ASUSTek       | P5G41T-M LX                 | [2de94117ab](https://linux-hardware.org/?probe=2de94117ab) | Apr 03, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [01c14c16ca](https://linux-hardware.org/?probe=01c14c16ca) | Apr 03, 2022 |
| Acer          | Predator G3-605             | [7e8eef4976](https://linux-hardware.org/?probe=7e8eef4976) | Apr 03, 2022 |
| ASUSTek       | P7P55D-E PRO                | [3e01b6fb25](https://linux-hardware.org/?probe=3e01b6fb25) | Apr 03, 2022 |
| ASUSTek       | P9X79                       | [bb18f1eb8f](https://linux-hardware.org/?probe=bb18f1eb8f) | Apr 03, 2022 |
| Gigabyte      | H310M S2H x.x               | [d2abd78cfc](https://linux-hardware.org/?probe=d2abd78cfc) | Apr 03, 2022 |
| HP            | 1790                        | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| Unknown       | Unknown                     | [aac8a6f7e4](https://linux-hardware.org/?probe=aac8a6f7e4) | Apr 03, 2022 |
| Packard Be... | M2N-NM                      | [7231602b33](https://linux-hardware.org/?probe=7231602b33) | Apr 03, 2022 |
| Gigabyte      | H61M-D2-B3                  | [d95c37955a](https://linux-hardware.org/?probe=d95c37955a) | Apr 03, 2022 |
| Gigabyte      | P41-ES3G                    | [3db559b0cb](https://linux-hardware.org/?probe=3db559b0cb) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| ASUSTek       | B85M-G                      | [c6cb4c0d83](https://linux-hardware.org/?probe=c6cb4c0d83) | Apr 03, 2022 |
| ASRock        | H61M-VS                     | [e000b33b40](https://linux-hardware.org/?probe=e000b33b40) | Apr 03, 2022 |
| Gigabyte      | P41-ES3G                    | [ba5297b664](https://linux-hardware.org/?probe=ba5297b664) | Apr 03, 2022 |
| ASRock        | B450M Pro4-F                | [45f577da9e](https://linux-hardware.org/?probe=45f577da9e) | Apr 03, 2022 |
| Intel         | DH61WW AAG23116-204         | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| Dell          | 0FPP7F A00                  | [8e8bee474f](https://linux-hardware.org/?probe=8e8bee474f) | Apr 03, 2022 |
| Biostar       | B450MH                      | [13317b700c](https://linux-hardware.org/?probe=13317b700c) | Apr 03, 2022 |
| Gigabyte      | Z590 VISION G               | [3aef96b298](https://linux-hardware.org/?probe=3aef96b298) | Apr 03, 2022 |
| ASRock        | H670M-ITX/ax                | [d97f9a02fe](https://linux-hardware.org/?probe=d97f9a02fe) | Apr 03, 2022 |
| Medion        | Z370H4-EM                   | [0f9b0bf367](https://linux-hardware.org/?probe=0f9b0bf367) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Medion        | Z370H4-EM                   | [64df85bce8](https://linux-hardware.org/?probe=64df85bce8) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Gigabyte      | H61M-S2PV                   | [eebc95dcb6](https://linux-hardware.org/?probe=eebc95dcb6) | Apr 03, 2022 |
| MSI           | B360M PRO-VDH               | [b2da2d7cc2](https://linux-hardware.org/?probe=b2da2d7cc2) | Apr 03, 2022 |
| Acer          | WMCP78M                     | [7c9d2a802f](https://linux-hardware.org/?probe=7c9d2a802f) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| HP            | 1998                        | [4b6628b734](https://linux-hardware.org/?probe=4b6628b734) | Apr 03, 2022 |
| MSI           | A88XM-E35 V2                | [2366707e2c](https://linux-hardware.org/?probe=2366707e2c) | Apr 03, 2022 |
| ASUSTek       | B560M-P                     | [d696143851](https://linux-hardware.org/?probe=d696143851) | Apr 03, 2022 |
| Alienware     | 07W25T A01                  | [e7280e6116](https://linux-hardware.org/?probe=e7280e6116) | Apr 03, 2022 |
| ASUSTek       | Maximus VI HERO             | [bf16aedd75](https://linux-hardware.org/?probe=bf16aedd75) | Apr 03, 2022 |
| MSI           | H81M-E34                    | [fad24f9efc](https://linux-hardware.org/?probe=fad24f9efc) | Apr 03, 2022 |
| Unknown       | Unknown                     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| HP            | 87D6 SMVB                   | [57d44d9705](https://linux-hardware.org/?probe=57d44d9705) | Apr 03, 2022 |
| Gigabyte      | H61M-S1                     | [a10a00d2f1](https://linux-hardware.org/?probe=a10a00d2f1) | Apr 03, 2022 |
| HP            | 87D6 SMVB                   | [e70c6e6d89](https://linux-hardware.org/?probe=e70c6e6d89) | Apr 03, 2022 |
| Pegatron      | 2AC2                        | [f6d4a4c17e](https://linux-hardware.org/?probe=f6d4a4c17e) | Apr 03, 2022 |
| ASUSTek       | H170 PRO GAMING             | [f7bc6dd5a3](https://linux-hardware.org/?probe=f7bc6dd5a3) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [0d5d7d117b](https://linux-hardware.org/?probe=0d5d7d117b) | Apr 03, 2022 |
| MSI           | Z590-A PRO                  | [229ed42b3d](https://linux-hardware.org/?probe=229ed42b3d) | Apr 03, 2022 |
| ASUSTek       | M51AC                       | [0b15974e5c](https://linux-hardware.org/?probe=0b15974e5c) | Apr 03, 2022 |
| ASUSTek       | M51AC                       | [1943dbe3b7](https://linux-hardware.org/?probe=1943dbe3b7) | Apr 03, 2022 |
| MSI           | X470 GAMING PLUS            | [b7cf273d03](https://linux-hardware.org/?probe=b7cf273d03) | Apr 03, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [53df2c9f1a](https://linux-hardware.org/?probe=53df2c9f1a) | Apr 03, 2022 |
| Apple         | Mac-F221BEC8                | [e72fc44e1d](https://linux-hardware.org/?probe=e72fc44e1d) | Apr 03, 2022 |
| MSI           | MEG X570 ACE                | [62b7931f9b](https://linux-hardware.org/?probe=62b7931f9b) | Apr 03, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| ASUSTek       | WS Z390 PRO                 | [ec2fb21c00](https://linux-hardware.org/?probe=ec2fb21c00) | Apr 03, 2022 |
| Gigabyte      | P55M-UD2                    | [e6d82a83c3](https://linux-hardware.org/?probe=e6d82a83c3) | Apr 03, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [40077b3761](https://linux-hardware.org/?probe=40077b3761) | Apr 03, 2022 |
| MSI           | MEG X570 UNIFY              | [0c57600526](https://linux-hardware.org/?probe=0c57600526) | Apr 03, 2022 |
| MSI           | B350 TOMAHAWK               | [f531f62c1b](https://linux-hardware.org/?probe=f531f62c1b) | Apr 03, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [348af6c202](https://linux-hardware.org/?probe=348af6c202) | Apr 02, 2022 |
| ASRock        | X370 Killer SLI             | [ffb866117c](https://linux-hardware.org/?probe=ffb866117c) | Apr 02, 2022 |
| MSI           | H510M-A PRO                 | [b3dfc0ae31](https://linux-hardware.org/?probe=b3dfc0ae31) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | [cf80b64dad](https://linux-hardware.org/?probe=cf80b64dad) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | [50c200ee58](https://linux-hardware.org/?probe=50c200ee58) | Apr 02, 2022 |
| ASUSTek       | B75M-A                      | [06415c4f91](https://linux-hardware.org/?probe=06415c4f91) | Apr 02, 2022 |
| ASUSTek       | PRIME X570-P                | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| ASUSTek       | H81M-PLUS                   | [bd717d57c2](https://linux-hardware.org/?probe=bd717d57c2) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| ECS           | Livermore                   | [d801396140](https://linux-hardware.org/?probe=d801396140) | Apr 02, 2022 |
| Dell          | 0K240Y A03                  | [7e3ad9ce02](https://linux-hardware.org/?probe=7e3ad9ce02) | Apr 02, 2022 |
| ASUSTek       | P5P41T-LE                   | [1ccfd166ec](https://linux-hardware.org/?probe=1ccfd166ec) | Apr 02, 2022 |
| Minix         | NEO Z83-4 V1.1              | [81925864d4](https://linux-hardware.org/?probe=81925864d4) | Apr 02, 2022 |
| ASUSTek       | Maximus VI HERO             | [3c0ef3960c](https://linux-hardware.org/?probe=3c0ef3960c) | Apr 02, 2022 |
| Dell          | 088DT1 A01                  | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M91p 7033HS8    | [0fab8669e0](https://linux-hardware.org/?probe=0fab8669e0) | Apr 02, 2022 |
| MSI           | Z97 GAMING 5                | [8bd2b269ff](https://linux-hardware.org/?probe=8bd2b269ff) | Apr 02, 2022 |
| Lenovo        | BRASWELL SDK0J40705 WIN ... | [7901a70a76](https://linux-hardware.org/?probe=7901a70a76) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a4228141cb](https://linux-hardware.org/?probe=a4228141cb) | Apr 02, 2022 |
| ASRock        | B75M-GL                     | [087381b93e](https://linux-hardware.org/?probe=087381b93e) | Apr 02, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [dfcfb79dcb](https://linux-hardware.org/?probe=dfcfb79dcb) | Apr 02, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [78665d8f57](https://linux-hardware.org/?probe=78665d8f57) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [9919bf1e95](https://linux-hardware.org/?probe=9919bf1e95) | Apr 02, 2022 |
| Intel         | D2500CC AAG81477-401        | [5beb419727](https://linux-hardware.org/?probe=5beb419727) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [35f6caff42](https://linux-hardware.org/?probe=35f6caff42) | Apr 02, 2022 |
| Acer          | Aspire M1920                | [00d3df045a](https://linux-hardware.org/?probe=00d3df045a) | Apr 02, 2022 |
| Gigabyte      | H410M H V3                  | [48f0951752](https://linux-hardware.org/?probe=48f0951752) | Apr 02, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| Gigabyte      | H61M-S1                     | [4a26394306](https://linux-hardware.org/?probe=4a26394306) | Apr 02, 2022 |
| ASUSTek       | F2A55-M                     | [62b4ad0ce3](https://linux-hardware.org/?probe=62b4ad0ce3) | Apr 02, 2022 |
| ASUSTek       | F2A85-V                     | [6056351804](https://linux-hardware.org/?probe=6056351804) | Apr 02, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [77e2c60730](https://linux-hardware.org/?probe=77e2c60730) | Apr 02, 2022 |
| Dell          | 09KPNV A00                  | [fad7c9dda0](https://linux-hardware.org/?probe=fad7c9dda0) | Apr 02, 2022 |
| ASUSTek       | M5A99X EVO                  | [9bc98bf38e](https://linux-hardware.org/?probe=9bc98bf38e) | Apr 02, 2022 |
| HP            | 18E5                        | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [376ed7f486](https://linux-hardware.org/?probe=376ed7f486) | Apr 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | [63408907f1](https://linux-hardware.org/?probe=63408907f1) | Apr 02, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a8425c2df8](https://linux-hardware.org/?probe=a8425c2df8) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | [6655399773](https://linux-hardware.org/?probe=6655399773) | Apr 02, 2022 |
| MSI           | H81M-P33                    | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| Gigabyte      | H87-HD3                     | [0a4247912e](https://linux-hardware.org/?probe=0a4247912e) | Apr 02, 2022 |
| ASUSTek       | M5A78L-M LE                 | [2054f135d4](https://linux-hardware.org/?probe=2054f135d4) | Apr 02, 2022 |
| ASRock        | B85M Pro3                   | [8d14068c4b](https://linux-hardware.org/?probe=8d14068c4b) | Apr 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [1de292a85c](https://linux-hardware.org/?probe=1de292a85c) | Apr 02, 2022 |
| ASUSTek       | P8Z68-V LX                  | [ece77d7f2f](https://linux-hardware.org/?probe=ece77d7f2f) | Apr 02, 2022 |
| ASUSTek       | PB50                        | [32ab9e7da2](https://linux-hardware.org/?probe=32ab9e7da2) | Apr 02, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [0d1d941941](https://linux-hardware.org/?probe=0d1d941941) | Apr 02, 2022 |
| ASRock        | B85M-HDS R2.0               | [9a446ac5fd](https://linux-hardware.org/?probe=9a446ac5fd) | Apr 02, 2022 |
| Dell          | 0WK833                      | [efee7c0ec6](https://linux-hardware.org/?probe=efee7c0ec6) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [68483bc13a](https://linux-hardware.org/?probe=68483bc13a) | Apr 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | [37394c9815](https://linux-hardware.org/?probe=37394c9815) | Apr 02, 2022 |
| Acer          | Aspire TC-120               | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| Lenovo        | 32E9 SDK0T76479 WIN 3423... | [d8dbd14b3e](https://linux-hardware.org/?probe=d8dbd14b3e) | Apr 02, 2022 |
| MSI           | P55M-SD40                   | [3232f9fb77](https://linux-hardware.org/?probe=3232f9fb77) | Apr 02, 2022 |
| ASRock        | B560M Pro4                  | [5a4174b74d](https://linux-hardware.org/?probe=5a4174b74d) | Apr 02, 2022 |
| Gigabyte      | Z690 UD AX                  | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| ASUSTek       | P8H67-M LE                  | [01a521b3d1](https://linux-hardware.org/?probe=01a521b3d1) | Apr 02, 2022 |
| Dell          | 0M017G A00                  | [a7ee814f3a](https://linux-hardware.org/?probe=a7ee814f3a) | Apr 02, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [a1bd9b5b35](https://linux-hardware.org/?probe=a1bd9b5b35) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fc477a4cb4](https://linux-hardware.org/?probe=fc477a4cb4) | Apr 02, 2022 |
| ASUSTek       | M5A99X EVO                  | [f5a5374d7f](https://linux-hardware.org/?probe=f5a5374d7f) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [23b384fa80](https://linux-hardware.org/?probe=23b384fa80) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [eedbf6a10e](https://linux-hardware.org/?probe=eedbf6a10e) | Apr 02, 2022 |
| ASUSTek       | P7P55D                      | [626d7d9cf9](https://linux-hardware.org/?probe=626d7d9cf9) | Apr 02, 2022 |
| MSI           | Z77A-GD65                   | [d7e7b28b04](https://linux-hardware.org/?probe=d7e7b28b04) | Apr 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ba7b7abd34](https://linux-hardware.org/?probe=ba7b7abd34) | Apr 02, 2022 |
| ECS           | G31T-M7                     | [c6f5fbd8ff](https://linux-hardware.org/?probe=c6f5fbd8ff) | Apr 02, 2022 |
| Unknown       | Unknown                     | [9ea14bf201](https://linux-hardware.org/?probe=9ea14bf201) | Apr 02, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [61e5bd5c41](https://linux-hardware.org/?probe=61e5bd5c41) | Apr 02, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3bcc5c9790](https://linux-hardware.org/?probe=3bcc5c9790) | Apr 02, 2022 |
| ASRock        | H61M-VS                     | [609849a9e7](https://linux-hardware.org/?probe=609849a9e7) | Apr 02, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [3807eeb187](https://linux-hardware.org/?probe=3807eeb187) | Apr 02, 2022 |
| ASRock        | P67 Pro3                    | [f8a2c24557](https://linux-hardware.org/?probe=f8a2c24557) | Apr 02, 2022 |
| ASUSTek       | PRIME H270-PRO              | [80007d3994](https://linux-hardware.org/?probe=80007d3994) | Apr 02, 2022 |
| Dell          | 0HHV7N A00                  | [4589c59d45](https://linux-hardware.org/?probe=4589c59d45) | Apr 02, 2022 |
| Gigabyte      | Q77M-D2H                    | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [42038ab400](https://linux-hardware.org/?probe=42038ab400) | Apr 02, 2022 |
| ASUSTek       | Z97-A-USB31                 | [6f40a4ebce](https://linux-hardware.org/?probe=6f40a4ebce) | Apr 02, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [6b2cbca4b2](https://linux-hardware.org/?probe=6b2cbca4b2) | Apr 02, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [62bdba9365](https://linux-hardware.org/?probe=62bdba9365) | Apr 02, 2022 |
| Dell          | 0WK833                      | [a8703c7598](https://linux-hardware.org/?probe=a8703c7598) | Apr 02, 2022 |
| ASUSTek       | PRIME B550M-A               | [d196a2f784](https://linux-hardware.org/?probe=d196a2f784) | Apr 02, 2022 |
| Gigabyte      | H97M-D3H                    | [72d527b649](https://linux-hardware.org/?probe=72d527b649) | Apr 02, 2022 |
| Lenovo        | QiTianM7150                 | [a6a37565b7](https://linux-hardware.org/?probe=a6a37565b7) | Apr 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [18b9815ff5](https://linux-hardware.org/?probe=18b9815ff5) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [5d3d268c96](https://linux-hardware.org/?probe=5d3d268c96) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [3dac9f017e](https://linux-hardware.org/?probe=3dac9f017e) | Apr 02, 2022 |
| Gigabyte      | H410M S2H V3                | [0c9c9dd7e9](https://linux-hardware.org/?probe=0c9c9dd7e9) | Apr 02, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [981ddceae1](https://linux-hardware.org/?probe=981ddceae1) | Apr 02, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b88c7aef34](https://linux-hardware.org/?probe=b88c7aef34) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [ba7a9c106a](https://linux-hardware.org/?probe=ba7a9c106a) | Apr 02, 2022 |
| ASRock        | X399 Taichi                 | [4696339b4e](https://linux-hardware.org/?probe=4696339b4e) | Apr 02, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [a8331ec187](https://linux-hardware.org/?probe=a8331ec187) | Apr 02, 2022 |
| Pegatron      | 2A73h                       | [1aff91c424](https://linux-hardware.org/?probe=1aff91c424) | Apr 02, 2022 |
| Unknown       | Unknown                     | [a773d8dfef](https://linux-hardware.org/?probe=a773d8dfef) | Apr 02, 2022 |
| MSI           | H81M-E35 V2                 | [a3aea1cbf5](https://linux-hardware.org/?probe=a3aea1cbf5) | Apr 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [2d4957c88f](https://linux-hardware.org/?probe=2d4957c88f) | Apr 02, 2022 |
| Gigabyte      | B450M H                     | [ae5976d302](https://linux-hardware.org/?probe=ae5976d302) | Apr 01, 2022 |
| Intel         | H61                         | [47b28b972b](https://linux-hardware.org/?probe=47b28b972b) | Apr 01, 2022 |
| Unknown       | HX90                        | [9cb3335bb0](https://linux-hardware.org/?probe=9cb3335bb0) | Apr 01, 2022 |
| ASRock        | B85M-ITX                    | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| Unknown       | HX90                        | [cd18483c45](https://linux-hardware.org/?probe=cd18483c45) | Apr 01, 2022 |
| Toshiba       | STI 010433                  | [daa5ae86bc](https://linux-hardware.org/?probe=daa5ae86bc) | Apr 01, 2022 |
| MSI           | B450-A PRO MAX              | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [c6f1665499](https://linux-hardware.org/?probe=c6f1665499) | Apr 01, 2022 |
| ECS           | G31T-M7                     | [48d0830c85](https://linux-hardware.org/?probe=48d0830c85) | Apr 01, 2022 |
| Wistron       | ProLiant ML110 G5           | [ccea23c3b5](https://linux-hardware.org/?probe=ccea23c3b5) | Apr 01, 2022 |
| Wistron       | ProLiant ML110 G5           | [4c01aec65d](https://linux-hardware.org/?probe=4c01aec65d) | Apr 01, 2022 |
| Dell          | 07PR60 A00                  | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| Gigabyte      | X570 UD                     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Gigabyte      | AX370-Gaming K7             | [0b410c35cf](https://linux-hardware.org/?probe=0b410c35cf) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| ASRock        | B450M Pro4                  | [fe5fe3040c](https://linux-hardware.org/?probe=fe5fe3040c) | Apr 01, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [66db4f71eb](https://linux-hardware.org/?probe=66db4f71eb) | Apr 01, 2022 |
| Gigabyte      | GA-A55M-S2HP                | [6655b05056](https://linux-hardware.org/?probe=6655b05056) | Apr 01, 2022 |
| Unknown       | Unknown                     | [13f524030b](https://linux-hardware.org/?probe=13f524030b) | Apr 01, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [2671214482](https://linux-hardware.org/?probe=2671214482) | Apr 01, 2022 |
| Dell          | 0N867P A02                  | [aaf4c4cf2b](https://linux-hardware.org/?probe=aaf4c4cf2b) | Apr 01, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| Gigabyte      | H81M-S1                     | [08db8019f3](https://linux-hardware.org/?probe=08db8019f3) | Apr 01, 2022 |
| Gigabyte      | B75M-D3V                    | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Shuttle       | FG41 V20                    | [2db99e0b09](https://linux-hardware.org/?probe=2db99e0b09) | Apr 01, 2022 |
| HP            | 212B                        | [ee85431891](https://linux-hardware.org/?probe=ee85431891) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d685d62203](https://linux-hardware.org/?probe=d685d62203) | Apr 01, 2022 |
| ASUSTek       | P5GD1 PRO                   | [9156c67116](https://linux-hardware.org/?probe=9156c67116) | Apr 01, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [66fd90660b](https://linux-hardware.org/?probe=66fd90660b) | Apr 01, 2022 |
| HP            | ProLiant ML150 Gen9         | [50114897cc](https://linux-hardware.org/?probe=50114897cc) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4e2f534de0](https://linux-hardware.org/?probe=4e2f534de0) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [625d6cc105](https://linux-hardware.org/?probe=625d6cc105) | Apr 01, 2022 |
| Intel         | DG45ID AAE27729-310         | [4a15651672](https://linux-hardware.org/?probe=4a15651672) | Apr 01, 2022 |
| ASUSTek       | A68HM-K                     | [482d5e9c62](https://linux-hardware.org/?probe=482d5e9c62) | Apr 01, 2022 |
| ASUSTek       | M4A77TD PRO                 | [3049a1dd96](https://linux-hardware.org/?probe=3049a1dd96) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [198fed544f](https://linux-hardware.org/?probe=198fed544f) | Apr 01, 2022 |
| HP            | 3047h                       | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | [348ccc5750](https://linux-hardware.org/?probe=348ccc5750) | Apr 01, 2022 |
| Dell          | 09M8Y8 A01                  | [d2e5eda16f](https://linux-hardware.org/?probe=d2e5eda16f) | Apr 01, 2022 |
| Gigabyte      | B250M-D3H-CF                | [cb91874b26](https://linux-hardware.org/?probe=cb91874b26) | Apr 01, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [86b685b176](https://linux-hardware.org/?probe=86b685b176) | Apr 01, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [07d499a6f9](https://linux-hardware.org/?probe=07d499a6f9) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [3ac2dfc728](https://linux-hardware.org/?probe=3ac2dfc728) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| ASRock        | 775Dual-VSTA                | [f5aea8ce64](https://linux-hardware.org/?probe=f5aea8ce64) | Apr 01, 2022 |
| ASUSTek       | PRIME B550M-A               | [3f302cd582](https://linux-hardware.org/?probe=3f302cd582) | Apr 01, 2022 |
| Unknown       | Unknown                     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | [32eabd9ac8](https://linux-hardware.org/?probe=32eabd9ac8) | Apr 01, 2022 |
| ASUSTek       | PRIME Z370-P                | [490eb434c1](https://linux-hardware.org/?probe=490eb434c1) | Apr 01, 2022 |
| MSI           | Z590-A PRO                  | [cafa6713f0](https://linux-hardware.org/?probe=cafa6713f0) | Apr 01, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [ee8cf37d90](https://linux-hardware.org/?probe=ee8cf37d90) | Apr 01, 2022 |
| Dell          | 06JWJY A01                  | [afe97da13d](https://linux-hardware.org/?probe=afe97da13d) | Apr 01, 2022 |
| ASUSTek       | M3A78-EMH HDMI              | [4462ffed73](https://linux-hardware.org/?probe=4462ffed73) | Apr 01, 2022 |
| Shuttle       | FH61V                       | [05c1b046da](https://linux-hardware.org/?probe=05c1b046da) | Apr 01, 2022 |
| ASUSTek       | PRIME H270-PRO              | [c0f39b75b9](https://linux-hardware.org/?probe=c0f39b75b9) | Apr 01, 2022 |
| Shuttle       | FH61V                       | [b89bd4d737](https://linux-hardware.org/?probe=b89bd4d737) | Apr 01, 2022 |
| Shuttle       | FH61V                       | [ef7c5cdb4c](https://linux-hardware.org/?probe=ef7c5cdb4c) | Apr 01, 2022 |
| Shuttle       | FH61V                       | [61383d9bd0](https://linux-hardware.org/?probe=61383d9bd0) | Apr 01, 2022 |
| Shuttle       | FH61V                       | [65009176b4](https://linux-hardware.org/?probe=65009176b4) | Apr 01, 2022 |
| Gigabyte      | B460M D3H                   | [7c159eefd8](https://linux-hardware.org/?probe=7c159eefd8) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| ASRock        | P67 Pro3                    | [ff19736e64](https://linux-hardware.org/?probe=ff19736e64) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| ASRock        | H55M-LE                     | [6284bd7200](https://linux-hardware.org/?probe=6284bd7200) | Apr 01, 2022 |
| ASUSTek       | B85M-E                      | [b81a77ca49](https://linux-hardware.org/?probe=b81a77ca49) | Apr 01, 2022 |
| ASUSTek       | PRIME H270-PRO              | [7c61bf8ce7](https://linux-hardware.org/?probe=7c61bf8ce7) | Apr 01, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [7cba7f428a](https://linux-hardware.org/?probe=7cba7f428a) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | [d3f3139ac2](https://linux-hardware.org/?probe=d3f3139ac2) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | [647fd89862](https://linux-hardware.org/?probe=647fd89862) | Apr 01, 2022 |
| ASUSTek       | Z87-K                       | [616258c6a5](https://linux-hardware.org/?probe=616258c6a5) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [b39bf0ec05](https://linux-hardware.org/?probe=b39bf0ec05) | Apr 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0b849ce682](https://linux-hardware.org/?probe=0b849ce682) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [c7cd058399](https://linux-hardware.org/?probe=c7cd058399) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| Unknown       | G41 Series                  | [e5276074c9](https://linux-hardware.org/?probe=e5276074c9) | Apr 01, 2022 |
| MSI           | X79A-GD45 Plus              | [c83e53c056](https://linux-hardware.org/?probe=c83e53c056) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | [8e507ac560](https://linux-hardware.org/?probe=8e507ac560) | Apr 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d0f35d0a4](https://linux-hardware.org/?probe=8d0f35d0a4) | Apr 01, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [47e2449cf5](https://linux-hardware.org/?probe=47e2449cf5) | Apr 01, 2022 |
| ASUSTek       | P5K                         | [544e656548](https://linux-hardware.org/?probe=544e656548) | Apr 01, 2022 |
| HP            | 1998                        | [23ca5d6703](https://linux-hardware.org/?probe=23ca5d6703) | Apr 01, 2022 |
| ASUSTek       | P5KPL-AM                    | [0190cbbd27](https://linux-hardware.org/?probe=0190cbbd27) | Apr 01, 2022 |
| ASRock        | G31M-S                      | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| HP            | 2129                        | [a49e4cbced](https://linux-hardware.org/?probe=a49e4cbced) | Apr 01, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [7633664f7f](https://linux-hardware.org/?probe=7633664f7f) | Apr 01, 2022 |
| ASUSTek       | P5KPL/1600                  | [4da992cdb7](https://linux-hardware.org/?probe=4da992cdb7) | Apr 01, 2022 |
| MSI           | B450-A PRO MAX              | [254b38e98f](https://linux-hardware.org/?probe=254b38e98f) | Apr 01, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| ASUSTek       | M3A78-CM                    | [477f340ef4](https://linux-hardware.org/?probe=477f340ef4) | Mar 31, 2022 |
| MSI           | B85-G43 GAMING              | [70574c396b](https://linux-hardware.org/?probe=70574c396b) | Mar 31, 2022 |
| Medion        | H81H3-EM2                   | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| HP            | 0A64h                       | [732f81838c](https://linux-hardware.org/?probe=732f81838c) | Mar 31, 2022 |
| Acer          | Aspire X3400                | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b08e7d8589](https://linux-hardware.org/?probe=b08e7d8589) | Mar 31, 2022 |
| ASRock        | X570 Taichi                 | [1247f2f024](https://linux-hardware.org/?probe=1247f2f024) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | [069ce7ef8f](https://linux-hardware.org/?probe=069ce7ef8f) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| ASRock        | X99 Extreme4                | [112e437f5d](https://linux-hardware.org/?probe=112e437f5d) | Mar 31, 2022 |
| ASRock        | X99 Extreme4                | [293958c009](https://linux-hardware.org/?probe=293958c009) | Mar 31, 2022 |
| ASUSTek       | PRIME Z490-P                | [667310c4b8](https://linux-hardware.org/?probe=667310c4b8) | Mar 31, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | [f74de3797f](https://linux-hardware.org/?probe=f74de3797f) | Mar 31, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [45e05e692e](https://linux-hardware.org/?probe=45e05e692e) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| ASUSTek       | A68HM-PLUS                  | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [ec4c49e5b2](https://linux-hardware.org/?probe=ec4c49e5b2) | Mar 31, 2022 |
| MSI           | P67A-C45                    | [5ec0cd08a4](https://linux-hardware.org/?probe=5ec0cd08a4) | Mar 31, 2022 |
| ASRock        | H510M-HVS R2.0              | [a4ad860e3d](https://linux-hardware.org/?probe=a4ad860e3d) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| HP            | 805D                        | [709488e1da](https://linux-hardware.org/?probe=709488e1da) | Mar 31, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [44eafd5b02](https://linux-hardware.org/?probe=44eafd5b02) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| MSI           | B350 PC MATE                | [09a8208d01](https://linux-hardware.org/?probe=09a8208d01) | Mar 31, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| BESSTAR Te... | JB9                         | [ad56d40441](https://linux-hardware.org/?probe=ad56d40441) | Mar 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | [986a42ba64](https://linux-hardware.org/?probe=986a42ba64) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [09c3268643](https://linux-hardware.org/?probe=09c3268643) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [90aa422ea2](https://linux-hardware.org/?probe=90aa422ea2) | Mar 31, 2022 |
| Gigabyte      | H110M-S2V-CF                | [fe17eb0fec](https://linux-hardware.org/?probe=fe17eb0fec) | Mar 31, 2022 |
| ASRock        | B75 Pro3                    | [01c8b92976](https://linux-hardware.org/?probe=01c8b92976) | Mar 31, 2022 |
| MSI           | 990FXA-GD65                 | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| ASUSTek       | P8H61-M PRO                 | [a30091eb45](https://linux-hardware.org/?probe=a30091eb45) | Mar 31, 2022 |
| ASRock        | B450M Pro4-F                | [96487ebeb0](https://linux-hardware.org/?probe=96487ebeb0) | Mar 31, 2022 |
| ASRock        | Z170A-X1                    | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| ASUSTek       | M5A97 EVO                   | [96cd3f3a03](https://linux-hardware.org/?probe=96cd3f3a03) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [a8c1be0abd](https://linux-hardware.org/?probe=a8c1be0abd) | Mar 31, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [ff4a7768d2](https://linux-hardware.org/?probe=ff4a7768d2) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| Gigabyte      | H87-HD3                     | [e8f29093f9](https://linux-hardware.org/?probe=e8f29093f9) | Mar 31, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [efae9a6cb7](https://linux-hardware.org/?probe=efae9a6cb7) | Mar 31, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31a9cc6d7f](https://linux-hardware.org/?probe=31a9cc6d7f) | Mar 31, 2022 |
| Intel         | DH55TC AAE70932-204         | [5b54f9a1e1](https://linux-hardware.org/?probe=5b54f9a1e1) | Mar 31, 2022 |
| ASRock        | Z170 Pro4/D3                | [275edd1533](https://linux-hardware.org/?probe=275edd1533) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [101c38851b](https://linux-hardware.org/?probe=101c38851b) | Mar 31, 2022 |
| Gigabyte      | H110M-S2-CF                 | [a4d2271eaa](https://linux-hardware.org/?probe=a4d2271eaa) | Mar 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [6c25b53900](https://linux-hardware.org/?probe=6c25b53900) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [c338f4ffd4](https://linux-hardware.org/?probe=c338f4ffd4) | Mar 31, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [0236d370e9](https://linux-hardware.org/?probe=0236d370e9) | Mar 31, 2022 |
| Positivo      | POS-PIG41BO                 | [865f71148c](https://linux-hardware.org/?probe=865f71148c) | Mar 31, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [f265f5e3b1](https://linux-hardware.org/?probe=f265f5e3b1) | Mar 31, 2022 |
| Gigabyte      | B360M H                     | [c6d64363b9](https://linux-hardware.org/?probe=c6d64363b9) | Mar 31, 2022 |
| ASRock        | H97 Pro4                    | [f4ca737c25](https://linux-hardware.org/?probe=f4ca737c25) | Mar 31, 2022 |
| MSI           | H410M PRO-VH                | [e4ef535529](https://linux-hardware.org/?probe=e4ef535529) | Mar 31, 2022 |
| Biostar       | X370GT5                     | [efe58d6ab1](https://linux-hardware.org/?probe=efe58d6ab1) | Mar 31, 2022 |
| Intel         | D33217GKE G76540-201        | [04874b84db](https://linux-hardware.org/?probe=04874b84db) | Mar 31, 2022 |
| Gigabyte      | GA-E6010N                   | [0ab26a135d](https://linux-hardware.org/?probe=0ab26a135d) | Mar 31, 2022 |
| Gigabyte      | H81M-S2V                    | [f2dc785121](https://linux-hardware.org/?probe=f2dc785121) | Mar 31, 2022 |
| HP            | 2AA6 PVT                    | [7fbf6dadb4](https://linux-hardware.org/?probe=7fbf6dadb4) | Mar 31, 2022 |
| ASRock        | 960GM-GS3 FX                | [2c9c93fcb5](https://linux-hardware.org/?probe=2c9c93fcb5) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| ASUSTek       | PRIME H270-PRO              | [fd66ebbeee](https://linux-hardware.org/?probe=fd66ebbeee) | Mar 31, 2022 |
| Pegatron      | 2AD5                        | [0e27c2feb0](https://linux-hardware.org/?probe=0e27c2feb0) | Mar 31, 2022 |
| MSI           | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| ECS           | A55F-M4                     | [0d29bdddde](https://linux-hardware.org/?probe=0d29bdddde) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5f25594023](https://linux-hardware.org/?probe=5f25594023) | Mar 31, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [a33c598546](https://linux-hardware.org/?probe=a33c598546) | Mar 31, 2022 |
| Gigabyte      | H61M-DS2V                   | [830357fbc8](https://linux-hardware.org/?probe=830357fbc8) | Mar 31, 2022 |
| ASRock        | P67 Pro3                    | [599a17bae2](https://linux-hardware.org/?probe=599a17bae2) | Mar 31, 2022 |
| ASUSTek       | PRIME B450M-A               | [8781d04da2](https://linux-hardware.org/?probe=8781d04da2) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| MSI           | B450M GAMING PLUS           | [bd60416a2f](https://linux-hardware.org/?probe=bd60416a2f) | Mar 31, 2022 |
| Gigabyte      | AX370-Gaming K7             | [20aac26c6d](https://linux-hardware.org/?probe=20aac26c6d) | Mar 31, 2022 |
| Intel         | Unknown                     | [4689fbf7e1](https://linux-hardware.org/?probe=4689fbf7e1) | Mar 31, 2022 |
| Gigabyte      | AX370-Gaming K3             | [63f7d865d3](https://linux-hardware.org/?probe=63f7d865d3) | Mar 31, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [4fdbbcf1f5](https://linux-hardware.org/?probe=4fdbbcf1f5) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4146e027d3](https://linux-hardware.org/?probe=4146e027d3) | Mar 31, 2022 |
| Dell          | 0MN1TX A02                  | [f9be94fa9b](https://linux-hardware.org/?probe=f9be94fa9b) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [cc57bcd7a9](https://linux-hardware.org/?probe=cc57bcd7a9) | Mar 31, 2022 |
| Acer          | EG43M                       | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| ASRock        | P67 Pro3                    | [4a4493ce71](https://linux-hardware.org/?probe=4a4493ce71) | Mar 31, 2022 |
| Dell          | OptiPlex 7010               | [f1167c797e](https://linux-hardware.org/?probe=f1167c797e) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| ASUSTek       | M5A78L/USB3                 | [92eae45686](https://linux-hardware.org/?probe=92eae45686) | Mar 30, 2022 |
| ASUSTek       | M5A97 R2.0                  | [1cab31778a](https://linux-hardware.org/?probe=1cab31778a) | Mar 30, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [e6273d0bd9](https://linux-hardware.org/?probe=e6273d0bd9) | Mar 30, 2022 |
| Acer          | Veriton M4610G              | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [edf21d564c](https://linux-hardware.org/?probe=edf21d564c) | Mar 30, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| MSI           | 770-C45                     | [f77be5fea4](https://linux-hardware.org/?probe=f77be5fea4) | Mar 30, 2022 |
| HP            | 843B                        | [9c9f43770f](https://linux-hardware.org/?probe=9c9f43770f) | Mar 30, 2022 |
| Gigabyte      | M68MT-S2P                   | [c2daebfd60](https://linux-hardware.org/?probe=c2daebfd60) | Mar 30, 2022 |
| Gigabyte      | EP45-DS3L                   | [7879818528](https://linux-hardware.org/?probe=7879818528) | Mar 30, 2022 |
| Unknown       | Unknown                     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [abacf8ed50](https://linux-hardware.org/?probe=abacf8ed50) | Mar 30, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [42e098223b](https://linux-hardware.org/?probe=42e098223b) | Mar 30, 2022 |
| HP            | 843B                        | [84ae0f086f](https://linux-hardware.org/?probe=84ae0f086f) | Mar 30, 2022 |
| ASUSTek       | PRIME Z270-A                | [e8bc504167](https://linux-hardware.org/?probe=e8bc504167) | Mar 30, 2022 |
| Acer          | Predator G3-710             | [d8d0331e9e](https://linux-hardware.org/?probe=d8d0331e9e) | Mar 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3cd8bdb60c](https://linux-hardware.org/?probe=3cd8bdb60c) | Mar 30, 2022 |
| ASRock        | H61MV-ITX                   | [da935498ad](https://linux-hardware.org/?probe=da935498ad) | Mar 30, 2022 |
| ASUSTek       | P5Q-PRO                     | [75a190fb7c](https://linux-hardware.org/?probe=75a190fb7c) | Mar 30, 2022 |
| ASUSTek       | P5Q-PRO                     | [d09e4f35fa](https://linux-hardware.org/?probe=d09e4f35fa) | Mar 30, 2022 |
| MSI           | Z390-A PRO                  | [e2261987eb](https://linux-hardware.org/?probe=e2261987eb) | Mar 30, 2022 |
| MSI           | H110M PRO-VD                | [e299a5abe8](https://linux-hardware.org/?probe=e299a5abe8) | Mar 30, 2022 |
| ASUSTek       | H81M-K                      | [cefeb9762e](https://linux-hardware.org/?probe=cefeb9762e) | Mar 30, 2022 |
| Dell          | 0F642F A00                  | [b3ae697cd6](https://linux-hardware.org/?probe=b3ae697cd6) | Mar 30, 2022 |
| ASUSTek       | P5K                         | [c62991184f](https://linux-hardware.org/?probe=c62991184f) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | [b916133743](https://linux-hardware.org/?probe=b916133743) | Mar 30, 2022 |
| MSI           | MS-7388                     | [d5eabb8266](https://linux-hardware.org/?probe=d5eabb8266) | Mar 30, 2022 |
| Dell          | 0PC5F7 A03                  | [3d76ab6a14](https://linux-hardware.org/?probe=3d76ab6a14) | Mar 30, 2022 |
| Gigabyte      | B75M-D2V                    | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [e205dc3177](https://linux-hardware.org/?probe=e205dc3177) | Mar 30, 2022 |
| HP            | 18E7                        | [4503b657fe](https://linux-hardware.org/?probe=4503b657fe) | Mar 30, 2022 |
| ASUSTek       | M2N                         | [1d11c3c0f9](https://linux-hardware.org/?probe=1d11c3c0f9) | Mar 30, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [caa021af45](https://linux-hardware.org/?probe=caa021af45) | Mar 30, 2022 |
| ASRock        | B75M R2.0                   | [ee7a1d8721](https://linux-hardware.org/?probe=ee7a1d8721) | Mar 30, 2022 |
| Dell          | 0KV3RP A00                  | [7b36bbe047](https://linux-hardware.org/?probe=7b36bbe047) | Mar 30, 2022 |
| Gigabyte      | X99-UD4-CF                  | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Pegatron      | SM 3322                     | [5f56bb615a](https://linux-hardware.org/?probe=5f56bb615a) | Mar 30, 2022 |
| ASUSTek       | Z97-K                       | [34c82e4845](https://linux-hardware.org/?probe=34c82e4845) | Mar 30, 2022 |
| MSI           | MS-7346                     | [207eda5f34](https://linux-hardware.org/?probe=207eda5f34) | Mar 30, 2022 |
| HP            | 3641h                       | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [69e5ad3c75](https://linux-hardware.org/?probe=69e5ad3c75) | Mar 30, 2022 |
| Gigabyte      | P35-DS3L                    | [8167ee62f2](https://linux-hardware.org/?probe=8167ee62f2) | Mar 30, 2022 |
| ASUSTek       | Z170-K                      | [d783ed375d](https://linux-hardware.org/?probe=d783ed375d) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Biostar       | J3060NH                     | [3770e096dd](https://linux-hardware.org/?probe=3770e096dd) | Mar 30, 2022 |
| Gigabyte      | Z270-Gaming K3              | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| ASUSTek       | H81M-K                      | [4374d376e6](https://linux-hardware.org/?probe=4374d376e6) | Mar 30, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d5b2536b95](https://linux-hardware.org/?probe=d5b2536b95) | Mar 30, 2022 |
| ASUSTek       | NCL-DS                      | [e078564242](https://linux-hardware.org/?probe=e078564242) | Mar 30, 2022 |
| MouseCompu... | B85H3-M4/2.0                | [3b58b2a122](https://linux-hardware.org/?probe=3b58b2a122) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| Pegatron      | IPMSB-GS                    | [57ed5ec512](https://linux-hardware.org/?probe=57ed5ec512) | Mar 30, 2022 |
| ASUSTek       | P8Z77-V                     | [0fa8cd8737](https://linux-hardware.org/?probe=0fa8cd8737) | Mar 30, 2022 |
| Dell          | 0Y2YM6 A01                  | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| ASUSTek       | M2R-FVM                     | [94beabac6e](https://linux-hardware.org/?probe=94beabac6e) | Mar 30, 2022 |
| Dell          | 0HHV7N A00                  | [2d6f6c72fa](https://linux-hardware.org/?probe=2d6f6c72fa) | Mar 30, 2022 |
| ASRock        | P67 Pro3                    | [bacc30fa55](https://linux-hardware.org/?probe=bacc30fa55) | Mar 30, 2022 |
| HP            | 2129                        | [0a2cac4bdb](https://linux-hardware.org/?probe=0a2cac4bdb) | Mar 30, 2022 |
| ASUSTek       | P8H67-M LX                  | [a30f5893f6](https://linux-hardware.org/?probe=a30f5893f6) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [078946745f](https://linux-hardware.org/?probe=078946745f) | Mar 30, 2022 |
| ASUSTek       | Amberine M                  | [767946408c](https://linux-hardware.org/?probe=767946408c) | Mar 30, 2022 |
| HP            | 2129                        | [b6db1efd0c](https://linux-hardware.org/?probe=b6db1efd0c) | Mar 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d8c91051f3](https://linux-hardware.org/?probe=d8c91051f3) | Mar 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [066fb2b2b9](https://linux-hardware.org/?probe=066fb2b2b9) | Mar 30, 2022 |
| ASUSTek       | PRIME B550M-A               | [a52eb1411c](https://linux-hardware.org/?probe=a52eb1411c) | Mar 30, 2022 |
| Dell          | 0KWVT8 A02                  | [2a2e308343](https://linux-hardware.org/?probe=2a2e308343) | Mar 30, 2022 |
| Dell          | 07N90W A02                  | [4fd59735d6](https://linux-hardware.org/?probe=4fd59735d6) | Mar 30, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0deba367b9](https://linux-hardware.org/?probe=0deba367b9) | Mar 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [412577fc74](https://linux-hardware.org/?probe=412577fc74) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [2491111c9d](https://linux-hardware.org/?probe=2491111c9d) | Mar 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [759b8d297d](https://linux-hardware.org/?probe=759b8d297d) | Mar 30, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [3e182ccdbe](https://linux-hardware.org/?probe=3e182ccdbe) | Mar 30, 2022 |
| ASUSTek       | PRIME X570-P                | [eeef359646](https://linux-hardware.org/?probe=eeef359646) | Mar 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5cdca2d9b2](https://linux-hardware.org/?probe=5cdca2d9b2) | Mar 30, 2022 |
| ASUSTek       | PRIME Z390-A                | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Dell          | 0FR6WH A01                  | [3ebf09bc41](https://linux-hardware.org/?probe=3ebf09bc41) | Mar 30, 2022 |
| Maita         | NUCCF01                     | [ef888d0be5](https://linux-hardware.org/?probe=ef888d0be5) | Mar 29, 2022 |
| SiS Techno... | 741                         | [fe2c3a2118](https://linux-hardware.org/?probe=fe2c3a2118) | Mar 29, 2022 |
| Maita         | NUCCF01                     | [c3c283c0f6](https://linux-hardware.org/?probe=c3c283c0f6) | Mar 29, 2022 |
| Dell          | 0478VN A00                  | [7d745ddc67](https://linux-hardware.org/?probe=7d745ddc67) | Mar 29, 2022 |
| HP            | 0AA8h                       | [374efb9d66](https://linux-hardware.org/?probe=374efb9d66) | Mar 29, 2022 |
| ASRock        | B75M-GL R2.0                | [b951c3cc48](https://linux-hardware.org/?probe=b951c3cc48) | Mar 29, 2022 |
| ASUSTek       | P5Q-PRO                     | [a220b7b7cc](https://linux-hardware.org/?probe=a220b7b7cc) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [c0d1cdbeaf](https://linux-hardware.org/?probe=c0d1cdbeaf) | Mar 29, 2022 |
| ASUSTek       | Z170-K                      | [1b4b237c62](https://linux-hardware.org/?probe=1b4b237c62) | Mar 29, 2022 |
| Dell          | 0X75JG A00                  | [b108b6d817](https://linux-hardware.org/?probe=b108b6d817) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [464e58f41f](https://linux-hardware.org/?probe=464e58f41f) | Mar 29, 2022 |
| ASRock        | B450 Pro4                   | [c879b8be1c](https://linux-hardware.org/?probe=c879b8be1c) | Mar 29, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [137477b9ef](https://linux-hardware.org/?probe=137477b9ef) | Mar 29, 2022 |
| Intel         | D33217GKE G76540-203        | [d178add858](https://linux-hardware.org/?probe=d178add858) | Mar 29, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2955e87822](https://linux-hardware.org/?probe=2955e87822) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [79a7adfb69](https://linux-hardware.org/?probe=79a7adfb69) | Mar 29, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [641cb912c4](https://linux-hardware.org/?probe=641cb912c4) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [5a75a3f121](https://linux-hardware.org/?probe=5a75a3f121) | Mar 29, 2022 |
| ASUSTek       | AM1M-A                      | [29e10859da](https://linux-hardware.org/?probe=29e10859da) | Mar 29, 2022 |
| ASRock        | P67 Pro3                    | [13e0979200](https://linux-hardware.org/?probe=13e0979200) | Mar 29, 2022 |
| Dell          | OptiPlex 760                | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| ASUSTek       | P8H67-M LE                  | [3a33018680](https://linux-hardware.org/?probe=3a33018680) | Mar 29, 2022 |
| ASUSTek       | PRIME B460M-A               | [519c65be70](https://linux-hardware.org/?probe=519c65be70) | Mar 29, 2022 |
| Acer          | Nitro N50-610               | [17f97e88c0](https://linux-hardware.org/?probe=17f97e88c0) | Mar 29, 2022 |
| Dell          | 0478VN A00                  | [a7eacc9559](https://linux-hardware.org/?probe=a7eacc9559) | Mar 29, 2022 |
| ASUSTek       | PRIME B460M-A               | [f21f3af1ca](https://linux-hardware.org/?probe=f21f3af1ca) | Mar 29, 2022 |
| Gigabyte      | B250M-D3H-CF                | [8b6f847c8e](https://linux-hardware.org/?probe=8b6f847c8e) | Mar 29, 2022 |
| MSI           | H81M-P33                    | [853b5b2236](https://linux-hardware.org/?probe=853b5b2236) | Mar 29, 2022 |
| HP            | 0A54h                       | [0efed10555](https://linux-hardware.org/?probe=0efed10555) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| System76      | Thelio thelio-r2            | [426cd0671d](https://linux-hardware.org/?probe=426cd0671d) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5c10e8ed7d](https://linux-hardware.org/?probe=5c10e8ed7d) | Mar 29, 2022 |
| ASUSTek       | P5K                         | [0ba62d4144](https://linux-hardware.org/?probe=0ba62d4144) | Mar 29, 2022 |
| Gigabyte      | X99-UD4-CF                  | [2a9a30b011](https://linux-hardware.org/?probe=2a9a30b011) | Mar 29, 2022 |
| Gigabyte      | G1.Sniper 5                 | [918167d1e1](https://linux-hardware.org/?probe=918167d1e1) | Mar 29, 2022 |
| Foxconn       | H61MXL-K                    | [50b743dab8](https://linux-hardware.org/?probe=50b743dab8) | Mar 29, 2022 |
| ASRock        | B365M-HDV                   | [ce8992d4dd](https://linux-hardware.org/?probe=ce8992d4dd) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [567627010e](https://linux-hardware.org/?probe=567627010e) | Mar 29, 2022 |
| ASRock        | Z77 Extreme4                | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [85a3c0a47e](https://linux-hardware.org/?probe=85a3c0a47e) | Mar 29, 2022 |
| ASRock        | H470M-HDV                   | [19ee7b1fbc](https://linux-hardware.org/?probe=19ee7b1fbc) | Mar 29, 2022 |
| ASUSTek       | ET2700I                     | [8379cf3a4a](https://linux-hardware.org/?probe=8379cf3a4a) | Mar 29, 2022 |
| Gigabyte      | Z87MX-D3H-CF                | [0401591ebc](https://linux-hardware.org/?probe=0401591ebc) | Mar 29, 2022 |
| ASRock        | B450 Pro4                   | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| Gigabyte      | EX58-UD4P                   | [b3a7b518b6](https://linux-hardware.org/?probe=b3a7b518b6) | Mar 29, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [0ff3da859e](https://linux-hardware.org/?probe=0ff3da859e) | Mar 29, 2022 |
| ASUSTek       | P6T                         | [00868ae20c](https://linux-hardware.org/?probe=00868ae20c) | Mar 29, 2022 |
| ASRock        | P67 Pro3                    | [4df5971e89](https://linux-hardware.org/?probe=4df5971e89) | Mar 29, 2022 |
| ASRock        | B550M Pro4                  | [6755915c96](https://linux-hardware.org/?probe=6755915c96) | Mar 29, 2022 |
| HP            | 18E7                        | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| Dell          | 0GWHMW A00                  | [3c0907dc45](https://linux-hardware.org/?probe=3c0907dc45) | Mar 29, 2022 |
| Lenovo        | ThinkCentre M81 5049E7F     | [cfb0af9c1b](https://linux-hardware.org/?probe=cfb0af9c1b) | Mar 29, 2022 |
| HP            | 1998                        | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [8696148b4a](https://linux-hardware.org/?probe=8696148b4a) | Mar 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cfaa52d13e](https://linux-hardware.org/?probe=cfaa52d13e) | Mar 29, 2022 |
| Dell          | 0K83V0 A00                  | [0428ae1966](https://linux-hardware.org/?probe=0428ae1966) | Mar 29, 2022 |
| ASRock        | X470 Taichi                 | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| Dell          | 0K83V0 A00                  | [ef509c5553](https://linux-hardware.org/?probe=ef509c5553) | Mar 29, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [2da8f96ad8](https://linux-hardware.org/?probe=2da8f96ad8) | Mar 29, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [5d3604d4cc](https://linux-hardware.org/?probe=5d3604d4cc) | Mar 29, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [d435cef05e](https://linux-hardware.org/?probe=d435cef05e) | Mar 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | [1c58a58ead](https://linux-hardware.org/?probe=1c58a58ead) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | [2541e3be0e](https://linux-hardware.org/?probe=2541e3be0e) | Mar 29, 2022 |
| MSI           | Z270 PC MATE                | [8193ff7289](https://linux-hardware.org/?probe=8193ff7289) | Mar 29, 2022 |
| ASUSTek       | P8H61-I                     | [2e1b862b8b](https://linux-hardware.org/?probe=2e1b862b8b) | Mar 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [de17fecb09](https://linux-hardware.org/?probe=de17fecb09) | Mar 28, 2022 |
| ASUSTek       | A88X-GAMER                  | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [405fedcff9](https://linux-hardware.org/?probe=405fedcff9) | Mar 28, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [a10bdc00e2](https://linux-hardware.org/?probe=a10bdc00e2) | Mar 28, 2022 |
| ASUSTek       | PRIME B250M-K               | [2812792752](https://linux-hardware.org/?probe=2812792752) | Mar 28, 2022 |
| Dell          | 0F3KHR A00                  | [edee0670e3](https://linux-hardware.org/?probe=edee0670e3) | Mar 28, 2022 |
| Dell          | 0478VN A00                  | [3907b39fde](https://linux-hardware.org/?probe=3907b39fde) | Mar 28, 2022 |
| MSI           | H110M PRO-VD                | [54f0933a0a](https://linux-hardware.org/?probe=54f0933a0a) | Mar 28, 2022 |
| ASUSTek       | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| ECS           | H67H2-M3                    | [d6abbba502](https://linux-hardware.org/?probe=d6abbba502) | Mar 28, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [6a14049259](https://linux-hardware.org/?probe=6a14049259) | Mar 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0bcee9c78e](https://linux-hardware.org/?probe=0bcee9c78e) | Mar 28, 2022 |
| MSI           | H81M-E34                    | [42ff46ca6c](https://linux-hardware.org/?probe=42ff46ca6c) | Mar 28, 2022 |
| ASRock        | B365M Pro4                  | [6920de7907](https://linux-hardware.org/?probe=6920de7907) | Mar 28, 2022 |
| Intel         | DQ77MK AAG39642-400         | [29e7a23412](https://linux-hardware.org/?probe=29e7a23412) | Mar 28, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [bb7fa2ac4b](https://linux-hardware.org/?probe=bb7fa2ac4b) | Mar 28, 2022 |
| Gateway       | SX2185                      | [3d1d72a3c1](https://linux-hardware.org/?probe=3d1d72a3c1) | Mar 28, 2022 |
| ASRock        | H110M-DGS R3.0              | [c785b6b54b](https://linux-hardware.org/?probe=c785b6b54b) | Mar 28, 2022 |
| Gigabyte      | GA-770T-USB3                | [787cb334c2](https://linux-hardware.org/?probe=787cb334c2) | Mar 28, 2022 |
| Intel         | DH61BF AAG81311-101         | [126de118c4](https://linux-hardware.org/?probe=126de118c4) | Mar 28, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [9aa5a3401d](https://linux-hardware.org/?probe=9aa5a3401d) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| Biostar       | J3060NH                     | [2f5c39da5a](https://linux-hardware.org/?probe=2f5c39da5a) | Mar 28, 2022 |
| Intel         | DP965LT AAD41694-206        | [b6f8d31fa5](https://linux-hardware.org/?probe=b6f8d31fa5) | Mar 28, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [9cd4056356](https://linux-hardware.org/?probe=9cd4056356) | Mar 28, 2022 |
| Intel         | D2500HN AAG34776-402        | [990923b5a7](https://linux-hardware.org/?probe=990923b5a7) | Mar 28, 2022 |
| Gigabyte      | H97M-HD3                    | [9027088a52](https://linux-hardware.org/?probe=9027088a52) | Mar 28, 2022 |
| Dell          | 0C27VV A04                  | [168c917da8](https://linux-hardware.org/?probe=168c917da8) | Mar 28, 2022 |
| Google        | Guado                       | [b9e3791c3d](https://linux-hardware.org/?probe=b9e3791c3d) | Mar 28, 2022 |
| Gigabyte      | H97M-HD3                    | [fce2591fbd](https://linux-hardware.org/?probe=fce2591fbd) | Mar 28, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [7fe672d3a9](https://linux-hardware.org/?probe=7fe672d3a9) | Mar 28, 2022 |
| ASRock        | B560M Steel Legend          | [8caaa96b19](https://linux-hardware.org/?probe=8caaa96b19) | Mar 28, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [9688bbdb3f](https://linux-hardware.org/?probe=9688bbdb3f) | Mar 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [2b900adf8e](https://linux-hardware.org/?probe=2b900adf8e) | Mar 28, 2022 |
| Lenovo        | 0C48431 PRO                 | [5376a37772](https://linux-hardware.org/?probe=5376a37772) | Mar 28, 2022 |
| ASRock        | P43DE3                      | [8207158d85](https://linux-hardware.org/?probe=8207158d85) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [3d9b292e29](https://linux-hardware.org/?probe=3d9b292e29) | Mar 28, 2022 |
| Gigabyte      | B450M GAMING                | [6cff18109b](https://linux-hardware.org/?probe=6cff18109b) | Mar 28, 2022 |
| ASUSTek       | H110M-K                     | [4e238835bd](https://linux-hardware.org/?probe=4e238835bd) | Mar 28, 2022 |
| ECS           | G41T-M7                     | [9bd8c1ef5a](https://linux-hardware.org/?probe=9bd8c1ef5a) | Mar 28, 2022 |
| Gigabyte      | B450M GAMING                | [b650c90413](https://linux-hardware.org/?probe=b650c90413) | Mar 28, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [973087697b](https://linux-hardware.org/?probe=973087697b) | Mar 28, 2022 |
| Gigabyte      | M68MT-D3P                   | [8d596570ed](https://linux-hardware.org/?probe=8d596570ed) | Mar 28, 2022 |
| ASUSTek       | P9X79                       | [7ec3f97491](https://linux-hardware.org/?probe=7ec3f97491) | Mar 28, 2022 |
| ASUSTek       | M4A88T-M                    | [4cfedd9c7a](https://linux-hardware.org/?probe=4cfedd9c7a) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [5dae1dd2a5](https://linux-hardware.org/?probe=5dae1dd2a5) | Mar 28, 2022 |
| Dell          | 084J0R A00                  | [a44c1d3cc6](https://linux-hardware.org/?probe=a44c1d3cc6) | Mar 28, 2022 |
| HP            | 339A                        | [e3c5312cd4](https://linux-hardware.org/?probe=e3c5312cd4) | Mar 28, 2022 |
| Lenovo        | H420                        | [3da1375d85](https://linux-hardware.org/?probe=3da1375d85) | Mar 28, 2022 |
| HP            | 82A2                        | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| ASUSTek       | H97M-PLUS                   | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [6f66a7137f](https://linux-hardware.org/?probe=6f66a7137f) | Mar 28, 2022 |
| Acer          | FMP55                       | [3464cd398f](https://linux-hardware.org/?probe=3464cd398f) | Mar 28, 2022 |
| ASUSTek       | D940MX                      | [bdc8831182](https://linux-hardware.org/?probe=bdc8831182) | Mar 28, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [45513b120d](https://linux-hardware.org/?probe=45513b120d) | Mar 28, 2022 |
| Gigabyte      | A520M S2H                   | [eb0a725911](https://linux-hardware.org/?probe=eb0a725911) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [cfd10c0239](https://linux-hardware.org/?probe=cfd10c0239) | Mar 28, 2022 |
| Gigabyte      | F2A78M-HD2                  | [1991a3f990](https://linux-hardware.org/?probe=1991a3f990) | Mar 28, 2022 |
| Dell          | 0VD92X A00                  | [304f31d5a7](https://linux-hardware.org/?probe=304f31d5a7) | Mar 28, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [e60363109b](https://linux-hardware.org/?probe=e60363109b) | Mar 28, 2022 |
| ASUSTek       | P8H61-M PRO                 | [870dc37754](https://linux-hardware.org/?probe=870dc37754) | Mar 28, 2022 |
| Gigabyte      | 945GCM-S2L                  | [c9cc022a93](https://linux-hardware.org/?probe=c9cc022a93) | Mar 28, 2022 |
| HP            | 18E7                        | [5dc3eea8b5](https://linux-hardware.org/?probe=5dc3eea8b5) | Mar 28, 2022 |
| MSI           | P67A-C43                    | [fb5d1f7bc1](https://linux-hardware.org/?probe=fb5d1f7bc1) | Mar 28, 2022 |
| Gigabyte      | Z490 AORUS ELITE            | [f8c03d6697](https://linux-hardware.org/?probe=f8c03d6697) | Mar 28, 2022 |
| ASRock        | AB350M-HDV R3.0             | [7024cc263a](https://linux-hardware.org/?probe=7024cc263a) | Mar 28, 2022 |
| Unknown       | G41 Series                  | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| MSI           | B450-A PRO                  | [e33537863b](https://linux-hardware.org/?probe=e33537863b) | Mar 28, 2022 |
| Gigabyte      | EP31-DS3L                   | [7a4dfc156e](https://linux-hardware.org/?probe=7a4dfc156e) | Mar 28, 2022 |
| HP            | 21B4 A01                    | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9464f8c81e](https://linux-hardware.org/?probe=9464f8c81e) | Mar 28, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [6f2a0d378d](https://linux-hardware.org/?probe=6f2a0d378d) | Mar 28, 2022 |
| ASUSTek       | PRIME H410M-E               | [e02f2032f1](https://linux-hardware.org/?probe=e02f2032f1) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | [acb42fe25a](https://linux-hardware.org/?probe=acb42fe25a) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | [d39c4f7d2b](https://linux-hardware.org/?probe=d39c4f7d2b) | Mar 28, 2022 |
| MSI           | P67A-C43                    | [dac91a1c12](https://linux-hardware.org/?probe=dac91a1c12) | Mar 28, 2022 |
| MSI           | 970A-G46                    | [2e74d95856](https://linux-hardware.org/?probe=2e74d95856) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [11d32dddf9](https://linux-hardware.org/?probe=11d32dddf9) | Mar 28, 2022 |
| Gigabyte      | Z370P D3-CF                 | [0ba5c7464c](https://linux-hardware.org/?probe=0ba5c7464c) | Mar 28, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [656413f7e6](https://linux-hardware.org/?probe=656413f7e6) | Mar 28, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| Lenovo        | SDK0E50510 WIN              | [996a5d269c](https://linux-hardware.org/?probe=996a5d269c) | Mar 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [bc999f46f9](https://linux-hardware.org/?probe=bc999f46f9) | Mar 28, 2022 |
| ASRock        | G41C-GS R2.0                | [7829bdde58](https://linux-hardware.org/?probe=7829bdde58) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| ASUSTek       | PRIME X570-P                | [d72468b304](https://linux-hardware.org/?probe=d72468b304) | Mar 27, 2022 |
| ECS           | G41T-M7                     | [cdeda3b238](https://linux-hardware.org/?probe=cdeda3b238) | Mar 27, 2022 |
| ASUSTek       | M2N32-SLI PREMIUM           | [bf03850686](https://linux-hardware.org/?probe=bf03850686) | Mar 27, 2022 |
| ASUSTek       | H81M-R                      | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| ASUSTek       | B85-PRO GAMER               | [44913af0e4](https://linux-hardware.org/?probe=44913af0e4) | Mar 27, 2022 |
| ASUSTek       | H81M-R                      | [0d4d2c1358](https://linux-hardware.org/?probe=0d4d2c1358) | Mar 27, 2022 |
| MSI           | B450I GAMING PLUS AC        | [a06ee5ea23](https://linux-hardware.org/?probe=a06ee5ea23) | Mar 27, 2022 |
| ASRock        | A785GXH/128M                | [e644d9e545](https://linux-hardware.org/?probe=e644d9e545) | Mar 27, 2022 |
| Dell          | 0VD92X A00                  | [1d704a72e1](https://linux-hardware.org/?probe=1d704a72e1) | Mar 27, 2022 |
| Dell          | 0F3KHR A00                  | [17a15d4648](https://linux-hardware.org/?probe=17a15d4648) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | [c5d26f3dc7](https://linux-hardware.org/?probe=c5d26f3dc7) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | [53da8c0cdf](https://linux-hardware.org/?probe=53da8c0cdf) | Mar 27, 2022 |
| MSI           | 970A-G46                    | [c1543a34cf](https://linux-hardware.org/?probe=c1543a34cf) | Mar 27, 2022 |
| ASUSTek       | AM1M-A                      | [2f7bece339](https://linux-hardware.org/?probe=2f7bece339) | Mar 27, 2022 |
| ASUSTek       | PRIME B550M-A               | [3739a38d8e](https://linux-hardware.org/?probe=3739a38d8e) | Mar 27, 2022 |
| HP            | 1791                        | [dbde5293e1](https://linux-hardware.org/?probe=dbde5293e1) | Mar 27, 2022 |
| ASRock        | B250 Pro4                   | [052897615f](https://linux-hardware.org/?probe=052897615f) | Mar 27, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Dell          | 084J0R A00                  | [8016c351c8](https://linux-hardware.org/?probe=8016c351c8) | Mar 27, 2022 |
| Dell          | 0D6H9T A00                  | [48ab5aae1e](https://linux-hardware.org/?probe=48ab5aae1e) | Mar 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [b2884ac582](https://linux-hardware.org/?probe=b2884ac582) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B350-I GAMING     | [36e8a83674](https://linux-hardware.org/?probe=36e8a83674) | Mar 27, 2022 |
| MSI           | Z170A PC MATE               | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| ASUSTek       | P7H55                       | [12a9db8849](https://linux-hardware.org/?probe=12a9db8849) | Mar 27, 2022 |
| ASUSTek       | PRIME H410M-E               | [a8ba9467c8](https://linux-hardware.org/?probe=a8ba9467c8) | Mar 27, 2022 |
| HP            | 1791                        | [23e62d94fc](https://linux-hardware.org/?probe=23e62d94fc) | Mar 27, 2022 |
| Pegatron      | Benicia                     | [cd70e5d6f6](https://linux-hardware.org/?probe=cd70e5d6f6) | Mar 27, 2022 |
| Lenovo        | 361A SDK0K17763 WIN         | [334c4c0ff2](https://linux-hardware.org/?probe=334c4c0ff2) | Mar 27, 2022 |
| Gigabyte      | B450M S2H                   | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| Intel         | D945GCCR AAD78647-300       | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| MSI           | X79A-GD45 Plus              | [e12c979369](https://linux-hardware.org/?probe=e12c979369) | Mar 27, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [1727b6bd44](https://linux-hardware.org/?probe=1727b6bd44) | Mar 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | [7a70776029](https://linux-hardware.org/?probe=7a70776029) | Mar 27, 2022 |
| ASUSTek       | PRIME B250M-A               | [1260b540e7](https://linux-hardware.org/?probe=1260b540e7) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | [51c0f63296](https://linux-hardware.org/?probe=51c0f63296) | Mar 27, 2022 |
| HP            | 09F8h                       | [dbfc9b9f29](https://linux-hardware.org/?probe=dbfc9b9f29) | Mar 27, 2022 |
| MSI           | X79A-GD45 Plus              | [23eab958e6](https://linux-hardware.org/?probe=23eab958e6) | Mar 27, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [a96405351a](https://linux-hardware.org/?probe=a96405351a) | Mar 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3ed10cce06](https://linux-hardware.org/?probe=3ed10cce06) | Mar 27, 2022 |
| Koloe         | X58                         | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| ASUSTek       | Amberine M                  | [cf54d7e964](https://linux-hardware.org/?probe=cf54d7e964) | Mar 27, 2022 |
| Gigabyte      | P55-USB3                    | [a79e7dc9c5](https://linux-hardware.org/?probe=a79e7dc9c5) | Mar 27, 2022 |
| HP            | 18E7                        | [18decc1420](https://linux-hardware.org/?probe=18decc1420) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [9c0577803f](https://linux-hardware.org/?probe=9c0577803f) | Mar 27, 2022 |
| Gigabyte      | Z77X-D3H                    | [6ca9c192ee](https://linux-hardware.org/?probe=6ca9c192ee) | Mar 27, 2022 |
| Acer          | Veriton X490G               | [d8283d82c4](https://linux-hardware.org/?probe=d8283d82c4) | Mar 27, 2022 |
| Dell          | 0HY9JP A02                  | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Dell          | 0VD92X A00                  | [0e1e24ffe0](https://linux-hardware.org/?probe=0e1e24ffe0) | Mar 27, 2022 |
| Unknown       | G41 Series                  | [e11644e5c8](https://linux-hardware.org/?probe=e11644e5c8) | Mar 27, 2022 |
| MSI           | Z390-A PRO                  | [1f36f7eada](https://linux-hardware.org/?probe=1f36f7eada) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [a296d4597c](https://linux-hardware.org/?probe=a296d4597c) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [0a94255553](https://linux-hardware.org/?probe=0a94255553) | Mar 27, 2022 |
| ASUSTek       | P5K                         | [6e11e7348c](https://linux-hardware.org/?probe=6e11e7348c) | Mar 27, 2022 |
| ASUSTek       | P8P67 LE                    | [f7eb22bcfc](https://linux-hardware.org/?probe=f7eb22bcfc) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| ASUSTek       | P8Z77 WS                    | [069d2c186e](https://linux-hardware.org/?probe=069d2c186e) | Mar 27, 2022 |
| ASRock        | AMCP7AION-HT                | [23f929c975](https://linux-hardware.org/?probe=23f929c975) | Mar 27, 2022 |
| HP            | 339A                        | [8795c4a222](https://linux-hardware.org/?probe=8795c4a222) | Mar 27, 2022 |
| Gigabyte      | Q57M-S2H                    | [6f2b606477](https://linux-hardware.org/?probe=6f2b606477) | Mar 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [756231c2f0](https://linux-hardware.org/?probe=756231c2f0) | Mar 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [4d4d8a247d](https://linux-hardware.org/?probe=4d4d8a247d) | Mar 27, 2022 |
| Lenovo        | NO DPK                      | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | [e7211c8a24](https://linux-hardware.org/?probe=e7211c8a24) | Mar 27, 2022 |
| Medion        | MS-7848                     | [8d6108a1a8](https://linux-hardware.org/?probe=8d6108a1a8) | Mar 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [c5dac7978e](https://linux-hardware.org/?probe=c5dac7978e) | Mar 27, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [5d62943116](https://linux-hardware.org/?probe=5d62943116) | Mar 27, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [68bf78ae9d](https://linux-hardware.org/?probe=68bf78ae9d) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [7c852d78e1](https://linux-hardware.org/?probe=7c852d78e1) | Mar 27, 2022 |
| Gigabyte      | Z370M D3H-CF                | [ab14b95970](https://linux-hardware.org/?probe=ab14b95970) | Mar 27, 2022 |
| MSI           | MS-B1711                    | [29b3da3fb7](https://linux-hardware.org/?probe=29b3da3fb7) | Mar 27, 2022 |
| Lenovo        | 30D9 NOK                    | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Lenovo        | ThinkServer TS440           | [a356a33d0a](https://linux-hardware.org/?probe=a356a33d0a) | Mar 27, 2022 |
| ECS           | H61H2-M2                    | [b055956ef9](https://linux-hardware.org/?probe=b055956ef9) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [1e0f6a4a04](https://linux-hardware.org/?probe=1e0f6a4a04) | Mar 27, 2022 |
| MSI           | B450M PRO-M2                | [e269e3b44e](https://linux-hardware.org/?probe=e269e3b44e) | Mar 27, 2022 |
| HP            | 1850                        | [297472c5f0](https://linux-hardware.org/?probe=297472c5f0) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a8f5aed110](https://linux-hardware.org/?probe=a8f5aed110) | Mar 27, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Gigabyte      | M61VME-S2                   | [4e68853105](https://linux-hardware.org/?probe=4e68853105) | Mar 27, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | [986e01838e](https://linux-hardware.org/?probe=986e01838e) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [db1c53597b](https://linux-hardware.org/?probe=db1c53597b) | Mar 27, 2022 |
| HP            | 1495                        | [19569ad62b](https://linux-hardware.org/?probe=19569ad62b) | Mar 27, 2022 |
| HP            | 2B38                        | [99fd9bb200](https://linux-hardware.org/?probe=99fd9bb200) | Mar 27, 2022 |
| HP            | 843B                        | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| ASRock        | B550M Pro4                  | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| Gigabyte      | H110M-M2-CF                 | [0afecafd79](https://linux-hardware.org/?probe=0afecafd79) | Mar 27, 2022 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [5efb11c731](https://linux-hardware.org/?probe=5efb11c731) | Mar 27, 2022 |
| ASUSTek       | Z87-K                       | [d0d493d449](https://linux-hardware.org/?probe=d0d493d449) | Mar 27, 2022 |
| ECS           | Nettle2                     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| Gigabyte      | H110M-M2-CF                 | [1e41d02a44](https://linux-hardware.org/?probe=1e41d02a44) | Mar 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [26a2540713](https://linux-hardware.org/?probe=26a2540713) | Mar 27, 2022 |
| Unknown       | G41 Series                  | [5064d12f0b](https://linux-hardware.org/?probe=5064d12f0b) | Mar 27, 2022 |
| Dell          | 0M6C7G A00                  | [d214df0c57](https://linux-hardware.org/?probe=d214df0c57) | Mar 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8cdf89a270](https://linux-hardware.org/?probe=8cdf89a270) | Mar 27, 2022 |
| Gigabyte      | GA-E6010N                   | [92e299d57a](https://linux-hardware.org/?probe=92e299d57a) | Mar 27, 2022 |
| MSI           | B360-A PRO                  | [f3eb3387fb](https://linux-hardware.org/?probe=f3eb3387fb) | Mar 27, 2022 |
| ASUSTek       | PRIME B350M-A               | [3839ca9677](https://linux-hardware.org/?probe=3839ca9677) | Mar 27, 2022 |
| ASUSTek       | H81M-C/BR                   | [4d07e31cee](https://linux-hardware.org/?probe=4d07e31cee) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | [9e095340f3](https://linux-hardware.org/?probe=9e095340f3) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [8252c302e2](https://linux-hardware.org/?probe=8252c302e2) | Mar 27, 2022 |
| ASRock        | B550M-ITX/ac                | [8766d8c04e](https://linux-hardware.org/?probe=8766d8c04e) | Mar 27, 2022 |
| MSI           | PRO Z690-A WIFI             | [f4e7cba010](https://linux-hardware.org/?probe=f4e7cba010) | Mar 27, 2022 |
| Dell          | 0PC5F7 A03                  | [aeb87f174c](https://linux-hardware.org/?probe=aeb87f174c) | Mar 27, 2022 |
| Lenovo        | ThinkStation S20 4157V4A    | [b5b78f62fc](https://linux-hardware.org/?probe=b5b78f62fc) | Mar 27, 2022 |
| AMD           | 970A-D3                     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| Dell          | 0F3KHR A00                  | [5019c3645d](https://linux-hardware.org/?probe=5019c3645d) | Mar 26, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ce82ab584b](https://linux-hardware.org/?probe=ce82ab584b) | Mar 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b1645fed59](https://linux-hardware.org/?probe=b1645fed59) | Mar 26, 2022 |
| MSI           | PRO Z690-P DDR4             | [7aac216113](https://linux-hardware.org/?probe=7aac216113) | Mar 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b02c880a8a](https://linux-hardware.org/?probe=b02c880a8a) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [fb365f1b1e](https://linux-hardware.org/?probe=fb365f1b1e) | Mar 26, 2022 |
| MSI           | B450M PRO-M2 V2             | [f7daea6e27](https://linux-hardware.org/?probe=f7daea6e27) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | [91b7f328b1](https://linux-hardware.org/?probe=91b7f328b1) | Mar 26, 2022 |
| Le Cube 1     | Unknown                     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | [48ce1c3bd8](https://linux-hardware.org/?probe=48ce1c3bd8) | Mar 26, 2022 |
| Gigabyte      | B450 GAMING X               | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [029e0a790e](https://linux-hardware.org/?probe=029e0a790e) | Mar 26, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d1b78f5eb8](https://linux-hardware.org/?probe=d1b78f5eb8) | Mar 26, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [bd913c7613](https://linux-hardware.org/?probe=bd913c7613) | Mar 26, 2022 |
| Gigabyte      | H61M-USB3H                  | [f852a0cb0d](https://linux-hardware.org/?probe=f852a0cb0d) | Mar 26, 2022 |
| ASUSTek       | PRIME B550M-A               | [fcfc39253c](https://linux-hardware.org/?probe=fcfc39253c) | Mar 26, 2022 |
| HP            | 0A98h                       | [4b9c0556af](https://linux-hardware.org/?probe=4b9c0556af) | Mar 26, 2022 |
| ASRock        | FM2A88X-ITX+                | [dc35b742d2](https://linux-hardware.org/?probe=dc35b742d2) | Mar 26, 2022 |
| Gigabyte      | H61M-D2-B3                  | [e807733708](https://linux-hardware.org/?probe=e807733708) | Mar 26, 2022 |
| ASUSTek       | Z97-P                       | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| ASRock        | B550M-ITX/ac                | [156a0ab630](https://linux-hardware.org/?probe=156a0ab630) | Mar 26, 2022 |
| Gigabyte      | H61M-D2-B3                  | [59df12dc12](https://linux-hardware.org/?probe=59df12dc12) | Mar 26, 2022 |
| Dell          | 0PC5F7 A03                  | [e143ea2c3d](https://linux-hardware.org/?probe=e143ea2c3d) | Mar 26, 2022 |
| Gigabyte      | P41T-D3P                    | [3952f72348](https://linux-hardware.org/?probe=3952f72348) | Mar 26, 2022 |
| HP            | 18E7                        | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [b31460778c](https://linux-hardware.org/?probe=b31460778c) | Mar 26, 2022 |
| ASUSTek       | H110M-K                     | [14f509aa32](https://linux-hardware.org/?probe=14f509aa32) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [7e1b536f6b](https://linux-hardware.org/?probe=7e1b536f6b) | Mar 26, 2022 |
| ASUSTek       | H110M-K                     | [31098e4c80](https://linux-hardware.org/?probe=31098e4c80) | Mar 26, 2022 |
| ASRock        | B560M Pro4                  | [0e02af9ab7](https://linux-hardware.org/?probe=0e02af9ab7) | Mar 26, 2022 |
| MSI           | B450 GAMING PLUS            | [31106ba339](https://linux-hardware.org/?probe=31106ba339) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Biostar       | H81MLV3                     | [140139f958](https://linux-hardware.org/?probe=140139f958) | Mar 26, 2022 |
| ASRock        | 970 Pro3                    | [1b877e6f7a](https://linux-hardware.org/?probe=1b877e6f7a) | Mar 26, 2022 |
| MSI           | Z390-A PRO                  | [bd6bc4d5d4](https://linux-hardware.org/?probe=bd6bc4d5d4) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| ASRock        | N68C-S UCC                  | [80db7a4eb7](https://linux-hardware.org/?probe=80db7a4eb7) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [fd041828d0](https://linux-hardware.org/?probe=fd041828d0) | Mar 26, 2022 |
| Acer          | Predator G3-605             | [9a26fde0c3](https://linux-hardware.org/?probe=9a26fde0c3) | Mar 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6ebd5ce185](https://linux-hardware.org/?probe=6ebd5ce185) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [e4526228cd](https://linux-hardware.org/?probe=e4526228cd) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [402c4d5758](https://linux-hardware.org/?probe=402c4d5758) | Mar 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [79c9d66395](https://linux-hardware.org/?probe=79c9d66395) | Mar 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8341d3f6f9](https://linux-hardware.org/?probe=8341d3f6f9) | Mar 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [e1ce096233](https://linux-hardware.org/?probe=e1ce096233) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [c53b2decec](https://linux-hardware.org/?probe=c53b2decec) | Mar 26, 2022 |
| ASRock        | P67 Pro3                    | [515f03c954](https://linux-hardware.org/?probe=515f03c954) | Mar 26, 2022 |
| MSI           | B350I PRO AC                | [9d5ead8832](https://linux-hardware.org/?probe=9d5ead8832) | Mar 26, 2022 |
| ASUSTek       | M2R-FVM                     | [76ec39764b](https://linux-hardware.org/?probe=76ec39764b) | Mar 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [02a3f1feaf](https://linux-hardware.org/?probe=02a3f1feaf) | Mar 26, 2022 |
| Gigabyte      | EP45-DS3L                   | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| ASRock        | 970M Pro3                   | [5baa3973a9](https://linux-hardware.org/?probe=5baa3973a9) | Mar 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [a1b46c124a](https://linux-hardware.org/?probe=a1b46c124a) | Mar 26, 2022 |
| ECS           | G31T-M7                     | [6ae60fc846](https://linux-hardware.org/?probe=6ae60fc846) | Mar 26, 2022 |
| Unknown       | T3 MRD                      | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| Gigabyte      | EP31-DS3L                   | [349383626b](https://linux-hardware.org/?probe=349383626b) | Mar 26, 2022 |
| Dell          | 0Y3R3K A03                  | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [296d97246f](https://linux-hardware.org/?probe=296d97246f) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1272ec27ff](https://linux-hardware.org/?probe=1272ec27ff) | Mar 26, 2022 |
| Inspur        | NF5270M3                    | [053fcd58fc](https://linux-hardware.org/?probe=053fcd58fc) | Mar 26, 2022 |
| MSI           | Z390-A PRO                  | [61f204d151](https://linux-hardware.org/?probe=61f204d151) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1de7956cf2](https://linux-hardware.org/?probe=1de7956cf2) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [85f4e6ff91](https://linux-hardware.org/?probe=85f4e6ff91) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b2d35dc269](https://linux-hardware.org/?probe=b2d35dc269) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [e6a885c5df](https://linux-hardware.org/?probe=e6a885c5df) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b625abc938](https://linux-hardware.org/?probe=b625abc938) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| ASUSTek       | B360M-D3H                   | [bf6e46cd01](https://linux-hardware.org/?probe=bf6e46cd01) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LE/BR               | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [c8acfed97a](https://linux-hardware.org/?probe=c8acfed97a) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Biostar       | J3060NH                     | [7bfd914743](https://linux-hardware.org/?probe=7bfd914743) | Mar 26, 2022 |
| ASUSTek       | B85M-G                      | [1d78876e0c](https://linux-hardware.org/?probe=1d78876e0c) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [3825c4904e](https://linux-hardware.org/?probe=3825c4904e) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [a68ce8edaf](https://linux-hardware.org/?probe=a68ce8edaf) | Mar 26, 2022 |
| Dell          | 088DT1 A01                  | [abcfa0354f](https://linux-hardware.org/?probe=abcfa0354f) | Mar 26, 2022 |
| Dell          | 0D24M8 A01                  | [60b0ea7dd1](https://linux-hardware.org/?probe=60b0ea7dd1) | Mar 26, 2022 |
| ASUSTek       | P8H61-MX USB3               | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [90299bc344](https://linux-hardware.org/?probe=90299bc344) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [27f565aeca](https://linux-hardware.org/?probe=27f565aeca) | Mar 26, 2022 |
| Biostar       | B450MH                      | [9152345747](https://linux-hardware.org/?probe=9152345747) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [d8b099aefa](https://linux-hardware.org/?probe=d8b099aefa) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| ASUSTek       | P5G41T-M LX3                | [10b27986c9](https://linux-hardware.org/?probe=10b27986c9) | Mar 26, 2022 |
| Lanix         | EQ45M-S2 LNXACT             | [ab78b9c7a6](https://linux-hardware.org/?probe=ab78b9c7a6) | Mar 25, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [c8a76eb9ae](https://linux-hardware.org/?probe=c8a76eb9ae) | Mar 25, 2022 |
| Dell          | 0TDG4V A01                  | [4df00a11b0](https://linux-hardware.org/?probe=4df00a11b0) | Mar 25, 2022 |
| Alienware     | 0R3FWM A00                  | [46a5c111c3](https://linux-hardware.org/?probe=46a5c111c3) | Mar 25, 2022 |
| Gigabyte      | Z87P-D3                     | [3313178485](https://linux-hardware.org/?probe=3313178485) | Mar 25, 2022 |
| Intel         | DN2820FYB H24582-205        | [87a81b14f0](https://linux-hardware.org/?probe=87a81b14f0) | Mar 25, 2022 |
| ASRock        | H110M-HDS                   | [4d571e07cc](https://linux-hardware.org/?probe=4d571e07cc) | Mar 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c4986f3f81](https://linux-hardware.org/?probe=c4986f3f81) | Mar 25, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [9e60987b3d](https://linux-hardware.org/?probe=9e60987b3d) | Mar 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [243d5352ef](https://linux-hardware.org/?probe=243d5352ef) | Mar 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [88c6d60a0b](https://linux-hardware.org/?probe=88c6d60a0b) | Mar 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6690115e22](https://linux-hardware.org/?probe=6690115e22) | Mar 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [dc2a2c1054](https://linux-hardware.org/?probe=dc2a2c1054) | Mar 25, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [aae529497f](https://linux-hardware.org/?probe=aae529497f) | Mar 25, 2022 |
| MSI           | H61M-P31                    | [0b50659b44](https://linux-hardware.org/?probe=0b50659b44) | Mar 25, 2022 |
| MSI           | IONA                        | [1a625c0505](https://linux-hardware.org/?probe=1a625c0505) | Mar 25, 2022 |
| ASUSTek       | M5A78L-M LX                 | [b5ee1f293e](https://linux-hardware.org/?probe=b5ee1f293e) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| MSI           | H170 GAMING M3              | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| ASUSTek       | SABERTOOTH P67              | [27099d48f9](https://linux-hardware.org/?probe=27099d48f9) | Mar 25, 2022 |
| ASUSTek       | F2A55-M LE                  | [e027562517](https://linux-hardware.org/?probe=e027562517) | Mar 25, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [023e66a08d](https://linux-hardware.org/?probe=023e66a08d) | Mar 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte      | 990FXA-UD5                  | [9fb63e991c](https://linux-hardware.org/?probe=9fb63e991c) | Mar 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [d1e5c0bc9f](https://linux-hardware.org/?probe=d1e5c0bc9f) | Mar 25, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [d975f1b581](https://linux-hardware.org/?probe=d975f1b581) | Mar 25, 2022 |
| Gigabyte      | P55M-UD2                    | [4d2f49f47a](https://linux-hardware.org/?probe=4d2f49f47a) | Mar 25, 2022 |
| MSI           | B550M PRO-VDH               | [acd7be917a](https://linux-hardware.org/?probe=acd7be917a) | Mar 25, 2022 |
| Gigabyte      | H510M H                     | [d809ca0f7a](https://linux-hardware.org/?probe=d809ca0f7a) | Mar 25, 2022 |
| ASUSTek       | P8H61-M LE                  | [77f39ed5ef](https://linux-hardware.org/?probe=77f39ed5ef) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| ASUSTek       | P5G41-M LX2/GB/LPT          | [38f567bb43](https://linux-hardware.org/?probe=38f567bb43) | Mar 25, 2022 |
| HP            | 843E A01                    | [8b6e63fbd4](https://linux-hardware.org/?probe=8b6e63fbd4) | Mar 25, 2022 |
| Gigabyte      | G1.Sniper 5                 | [272dabac8d](https://linux-hardware.org/?probe=272dabac8d) | Mar 25, 2022 |
| Gigabyte      | 990XA-UD3                   | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| ASRock        | B550M-HDV                   | [00e8da8c29](https://linux-hardware.org/?probe=00e8da8c29) | Mar 25, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Gigabyte      | G1.Sniper 5                 | [701e91dcac](https://linux-hardware.org/?probe=701e91dcac) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [2a333a0767](https://linux-hardware.org/?probe=2a333a0767) | Mar 25, 2022 |
| Intel         | B75                         | [9f73efdcc8](https://linux-hardware.org/?probe=9f73efdcc8) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [40ec2200ee](https://linux-hardware.org/?probe=40ec2200ee) | Mar 25, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [fc2b611797](https://linux-hardware.org/?probe=fc2b611797) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [cb639d5f0a](https://linux-hardware.org/?probe=cb639d5f0a) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [1381f81018](https://linux-hardware.org/?probe=1381f81018) | Mar 25, 2022 |
| Gigabyte      | Z77-DS3H                    | [f758ccfcbe](https://linux-hardware.org/?probe=f758ccfcbe) | Mar 25, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [d5a1c13ab1](https://linux-hardware.org/?probe=d5a1c13ab1) | Mar 25, 2022 |
| Dell          | 00V62H A01                  | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| ASUSTek       | M2R-FVM                     | [eaaef17c19](https://linux-hardware.org/?probe=eaaef17c19) | Mar 25, 2022 |
| ASRock        | A75M-HVS                    | [5340d6cada](https://linux-hardware.org/?probe=5340d6cada) | Mar 25, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [381e2b1130](https://linux-hardware.org/?probe=381e2b1130) | Mar 25, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [0579061135](https://linux-hardware.org/?probe=0579061135) | Mar 25, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [c4c99ca0fa](https://linux-hardware.org/?probe=c4c99ca0fa) | Mar 25, 2022 |
| HP            | 3398                        | [b84864ecc4](https://linux-hardware.org/?probe=b84864ecc4) | Mar 25, 2022 |
| Unknown       | YL-J1900-V1                 | [835f68900c](https://linux-hardware.org/?probe=835f68900c) | Mar 25, 2022 |
| ASUSTek       | SABERTOOTH X58              | [bce45f36b9](https://linux-hardware.org/?probe=bce45f36b9) | Mar 25, 2022 |
| Gigabyte      | B450 AORUS M                | [81a6571a8b](https://linux-hardware.org/?probe=81a6571a8b) | Mar 25, 2022 |
| Gigabyte      | A520M H                     | [0eb6fdc31d](https://linux-hardware.org/?probe=0eb6fdc31d) | Mar 25, 2022 |
| ASUSTek       | PRIME H270-PRO              | [d60719a932](https://linux-hardware.org/?probe=d60719a932) | Mar 25, 2022 |
| ASUSTek       | PRIME H270-PRO              | [36f716cd9b](https://linux-hardware.org/?probe=36f716cd9b) | Mar 25, 2022 |
| ASRock        | X570 Taichi                 | [8163b935aa](https://linux-hardware.org/?probe=8163b935aa) | Mar 25, 2022 |
| Login Info... | LOG-H110M-G3                | [30a691b952](https://linux-hardware.org/?probe=30a691b952) | Mar 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [50335ac3a2](https://linux-hardware.org/?probe=50335ac3a2) | Mar 25, 2022 |
| ASUSTek       | Z170-AR                     | [f3edf6dd88](https://linux-hardware.org/?probe=f3edf6dd88) | Mar 25, 2022 |
| Dell          | 08WKV3 A00                  | [04bca4a56e](https://linux-hardware.org/?probe=04bca4a56e) | Mar 25, 2022 |
| Pegatron      | 2AC2                        | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [b2c47467cc](https://linux-hardware.org/?probe=b2c47467cc) | Mar 25, 2022 |
| HP            | 8643 SMVB                   | [170657280c](https://linux-hardware.org/?probe=170657280c) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [5a897fa995](https://linux-hardware.org/?probe=5a897fa995) | Mar 25, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [2a51a62d10](https://linux-hardware.org/?probe=2a51a62d10) | Mar 25, 2022 |
| ASRock        | H61M-HVS                    | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| ASRock        | G41M-VS3                    | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [1a9b30af2a](https://linux-hardware.org/?probe=1a9b30af2a) | Mar 25, 2022 |
| MSI           | B450 TOMAHAWK               | [cda786fd40](https://linux-hardware.org/?probe=cda786fd40) | Mar 25, 2022 |
| Dell          | 0JP3NX A01                  | [60eeaf871f](https://linux-hardware.org/?probe=60eeaf871f) | Mar 25, 2022 |
| Pegatron      | Benicia                     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| Dell          | 01KD4V A01                  | [9fae82a988](https://linux-hardware.org/?probe=9fae82a988) | Mar 24, 2022 |
| ASRock        | A300M-STX                   | [2a059657b4](https://linux-hardware.org/?probe=2a059657b4) | Mar 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [dfe9201f95](https://linux-hardware.org/?probe=dfe9201f95) | Mar 24, 2022 |
| Acer          | Veriton M6660G V:1.0        | [ee5d755daf](https://linux-hardware.org/?probe=ee5d755daf) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2424807acb](https://linux-hardware.org/?probe=2424807acb) | Mar 24, 2022 |
| ASUSTek       | P9X79 PRO                   | [4f717acbaa](https://linux-hardware.org/?probe=4f717acbaa) | Mar 24, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [994cca77b2](https://linux-hardware.org/?probe=994cca77b2) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [55171208ed](https://linux-hardware.org/?probe=55171208ed) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [fe7be471b2](https://linux-hardware.org/?probe=fe7be471b2) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d6d6620190](https://linux-hardware.org/?probe=d6d6620190) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7c46f54dc](https://linux-hardware.org/?probe=d7c46f54dc) | Mar 24, 2022 |
| ASRock        | B550 Taichi                 | [2c71d397fd](https://linux-hardware.org/?probe=2c71d397fd) | Mar 24, 2022 |
| HP            | 212B                        | [b7c0d8bedf](https://linux-hardware.org/?probe=b7c0d8bedf) | Mar 24, 2022 |
| MSI           | B550M PRO                   | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| Unknown       | Unknown                     | [e22336384e](https://linux-hardware.org/?probe=e22336384e) | Mar 24, 2022 |
| MSI           | Z97 GAMING 5                | [0bb5a2b0d1](https://linux-hardware.org/?probe=0bb5a2b0d1) | Mar 24, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [80fa34cf94](https://linux-hardware.org/?probe=80fa34cf94) | Mar 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| HP            | 82FF                        | [cb8d5d95bb](https://linux-hardware.org/?probe=cb8d5d95bb) | Mar 24, 2022 |
| Gigabyte      | H55-UD3H                    | [1cf4bf2cfd](https://linux-hardware.org/?probe=1cf4bf2cfd) | Mar 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| MSI           | Z390-A PRO                  | [337f4c12b3](https://linux-hardware.org/?probe=337f4c12b3) | Mar 24, 2022 |
| Dell          | 0P096C A01                  | [fff71ec7de](https://linux-hardware.org/?probe=fff71ec7de) | Mar 24, 2022 |
| ASRock        | 4X4-V1000                   | [f02931fb21](https://linux-hardware.org/?probe=f02931fb21) | Mar 24, 2022 |
| Intel         | B75                         | [e536726a62](https://linux-hardware.org/?probe=e536726a62) | Mar 24, 2022 |
| MSI           | Z390-A PRO                  | [a71c026397](https://linux-hardware.org/?probe=a71c026397) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| ASRock        | N68C-S UCC                  | [da1fd40737](https://linux-hardware.org/?probe=da1fd40737) | Mar 24, 2022 |
| BESSTAR Te... | UM700                       | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25d5cba9dc](https://linux-hardware.org/?probe=25d5cba9dc) | Mar 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [f1b11a1c3a](https://linux-hardware.org/?probe=f1b11a1c3a) | Mar 24, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | [090041bea7](https://linux-hardware.org/?probe=090041bea7) | Mar 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b4c23c72de](https://linux-hardware.org/?probe=b4c23c72de) | Mar 24, 2022 |
| Dell          | 0M863N A01                  | [c05eaeb499](https://linux-hardware.org/?probe=c05eaeb499) | Mar 24, 2022 |
| Biostar       | H81MHV3                     | [66b47eae5d](https://linux-hardware.org/?probe=66b47eae5d) | Mar 24, 2022 |
| Unknown       | Unknown                     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| Gigabyte      | B550M S2H                   | [29ede999bb](https://linux-hardware.org/?probe=29ede999bb) | Mar 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c10b664e4e](https://linux-hardware.org/?probe=c10b664e4e) | Mar 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [93014492bd](https://linux-hardware.org/?probe=93014492bd) | Mar 24, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [f1007aa153](https://linux-hardware.org/?probe=f1007aa153) | Mar 24, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Intel         | DH61BE AAG14062-206         | [08a352b1d2](https://linux-hardware.org/?probe=08a352b1d2) | Mar 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [9da89c589d](https://linux-hardware.org/?probe=9da89c589d) | Mar 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Gigabyte      | EX58-UD5                    | [beb844045e](https://linux-hardware.org/?probe=beb844045e) | Mar 24, 2022 |
| ASUSTek       | PRIME H510M-A               | [9590cc2288](https://linux-hardware.org/?probe=9590cc2288) | Mar 24, 2022 |
| ASUSTek       | P5Q SE                      | [926ae629bd](https://linux-hardware.org/?probe=926ae629bd) | Mar 24, 2022 |
| ASRock        | X300M-STX                   | [0d7d21ac36](https://linux-hardware.org/?probe=0d7d21ac36) | Mar 24, 2022 |
| Dell          | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| ASRock        | H110M-HDV R3.0              | [5409f0281e](https://linux-hardware.org/?probe=5409f0281e) | Mar 24, 2022 |
| Biostar       | A10N-9630E                  | [08e8cd5735](https://linux-hardware.org/?probe=08e8cd5735) | Mar 24, 2022 |
| Unknown       | Unknown                     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [75c60aeaeb](https://linux-hardware.org/?probe=75c60aeaeb) | Mar 24, 2022 |
| Unknown       | Unknown                     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [fa4526e9f3](https://linux-hardware.org/?probe=fa4526e9f3) | Mar 24, 2022 |
| Gigabyte      | H270-Gaming 3               | [90ce7b8310](https://linux-hardware.org/?probe=90ce7b8310) | Mar 24, 2022 |
| Pegatron      | 2ACE                        | [3f091e30fe](https://linux-hardware.org/?probe=3f091e30fe) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6136cfa920](https://linux-hardware.org/?probe=6136cfa920) | Mar 24, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cf9c727b0d](https://linux-hardware.org/?probe=cf9c727b0d) | Mar 24, 2022 |
| ECS           | H61H2-M13                   | [de7d87020c](https://linux-hardware.org/?probe=de7d87020c) | Mar 24, 2022 |
| ASUSTek       | PRIME B550M-A               | [3ff04aae1c](https://linux-hardware.org/?probe=3ff04aae1c) | Mar 24, 2022 |
| Biostar       | G31D-M7                     | [9882f292ea](https://linux-hardware.org/?probe=9882f292ea) | Mar 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d74979a970](https://linux-hardware.org/?probe=d74979a970) | Mar 24, 2022 |
| Gigabyte      | MZBAYAP-D9                  | [2c077e2993](https://linux-hardware.org/?probe=2c077e2993) | Mar 24, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4c70e2fa37](https://linux-hardware.org/?probe=4c70e2fa37) | Mar 24, 2022 |
| Gigabyte      | X570 GAMING X               | [5c424251c8](https://linux-hardware.org/?probe=5c424251c8) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| HP            | 1998                        | [ec47a4edb9](https://linux-hardware.org/?probe=ec47a4edb9) | Mar 24, 2022 |
| ASRock        | G31M-GS                     | [9304842ca4](https://linux-hardware.org/?probe=9304842ca4) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [f7248b112d](https://linux-hardware.org/?probe=f7248b112d) | Mar 24, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4bc13fce28](https://linux-hardware.org/?probe=4bc13fce28) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [0e85a5ee68](https://linux-hardware.org/?probe=0e85a5ee68) | Mar 24, 2022 |
| Alienware     | 0R3FWM A00                  | [fcbc77d9e4](https://linux-hardware.org/?probe=fcbc77d9e4) | Mar 24, 2022 |
| Biostar       | J3060NH                     | [6f46c10afd](https://linux-hardware.org/?probe=6f46c10afd) | Mar 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [bb1d6b4aae](https://linux-hardware.org/?probe=bb1d6b4aae) | Mar 24, 2022 |
| Gigabyte      | Z590 UD                     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [689868473e](https://linux-hardware.org/?probe=689868473e) | Mar 24, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [53c3899d7b](https://linux-hardware.org/?probe=53c3899d7b) | Mar 24, 2022 |
| HP            | 8643 SMVB                   | [3b5e516908](https://linux-hardware.org/?probe=3b5e516908) | Mar 24, 2022 |
| Dell          | 0KWVT8 A00                  | [5e2b36f808](https://linux-hardware.org/?probe=5e2b36f808) | Mar 24, 2022 |
| HP            | 0AA8h                       | [4d89df8b98](https://linux-hardware.org/?probe=4d89df8b98) | Mar 24, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [87989ace9b](https://linux-hardware.org/?probe=87989ace9b) | Mar 24, 2022 |
| MSI           | Z270-A PRO                  | [d9e98611b8](https://linux-hardware.org/?probe=d9e98611b8) | Mar 23, 2022 |
| Foxconn       | 2ADA                        | [b9aec6129a](https://linux-hardware.org/?probe=b9aec6129a) | Mar 23, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| ASRock        | H510M-HVS                   | [f47c9449b9](https://linux-hardware.org/?probe=f47c9449b9) | Mar 23, 2022 |
| ASUSTek       | X99-A                       | [b071309501](https://linux-hardware.org/?probe=b071309501) | Mar 23, 2022 |
| MSI           | Z270-A PRO                  | [e0fefdb7c8](https://linux-hardware.org/?probe=e0fefdb7c8) | Mar 23, 2022 |
| Dell          | 0HN7XN A01                  | [53f17c5666](https://linux-hardware.org/?probe=53f17c5666) | Mar 23, 2022 |
| Dell          | 0M858N A00                  | [b5b6beaa5d](https://linux-hardware.org/?probe=b5b6beaa5d) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [58cfc7fbae](https://linux-hardware.org/?probe=58cfc7fbae) | Mar 23, 2022 |
| Lenovo        | ThinkStation C20 426593U    | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| MSI           | B350 PC MATE                | [4bef3efcae](https://linux-hardware.org/?probe=4bef3efcae) | Mar 23, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [7c4be75815](https://linux-hardware.org/?probe=7c4be75815) | Mar 23, 2022 |
| Gigabyte      | B660 GAMING X DDR4          | [1b81b37d97](https://linux-hardware.org/?probe=1b81b37d97) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd0e0e448b](https://linux-hardware.org/?probe=bd0e0e448b) | Mar 23, 2022 |
| ASUSTek       | PRIME Z390-P                | [53a7830bc0](https://linux-hardware.org/?probe=53a7830bc0) | Mar 23, 2022 |
| Shuttle       | FH61V                       | [9b18d7b2ed](https://linux-hardware.org/?probe=9b18d7b2ed) | Mar 23, 2022 |
| Dell          | 08HPGT A01                  | [440e4d8b48](https://linux-hardware.org/?probe=440e4d8b48) | Mar 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [18d216846f](https://linux-hardware.org/?probe=18d216846f) | Mar 23, 2022 |
| Dell          | 0Y7WYT A00                  | [2376c46c04](https://linux-hardware.org/?probe=2376c46c04) | Mar 23, 2022 |
| Dell          | 0YXT71 A01                  | [447996a0c7](https://linux-hardware.org/?probe=447996a0c7) | Mar 23, 2022 |
| ASUSTek       | PRIME B360M-A               | [61a3132b66](https://linux-hardware.org/?probe=61a3132b66) | Mar 23, 2022 |
| Gigabyte      | X79-UD3                     | [6a88c14776](https://linux-hardware.org/?probe=6a88c14776) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| ASRock        | N68-VS3 FX                  | [c675421a82](https://linux-hardware.org/?probe=c675421a82) | Mar 23, 2022 |
| Gigabyte      | H97-HD3                     | [33fa2b3eff](https://linux-hardware.org/?probe=33fa2b3eff) | Mar 23, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [847b9e1fbb](https://linux-hardware.org/?probe=847b9e1fbb) | Mar 23, 2022 |
| Dell          | 0YXT71 A01                  | [c7bfffa6d4](https://linux-hardware.org/?probe=c7bfffa6d4) | Mar 23, 2022 |
| ASRock        | A320M-HDV R4.0              | [66d2a3d28a](https://linux-hardware.org/?probe=66d2a3d28a) | Mar 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [481f4ad619](https://linux-hardware.org/?probe=481f4ad619) | Mar 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [ccfdbc46a0](https://linux-hardware.org/?probe=ccfdbc46a0) | Mar 23, 2022 |
| HP            | 1589                        | [1758805274](https://linux-hardware.org/?probe=1758805274) | Mar 23, 2022 |
| Dell          | 0XHGV1 A01                  | [f9fb419fef](https://linux-hardware.org/?probe=f9fb419fef) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASUSTek       | M5A97                       | [ea157e214f](https://linux-hardware.org/?probe=ea157e214f) | Mar 23, 2022 |
| Gigabyte      | GA-73PVM-S2H                | [ac9f20a77c](https://linux-hardware.org/?probe=ac9f20a77c) | Mar 23, 2022 |
| HP            | 1589                        | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| Gigabyte      | B75M-HD3                    | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| ASUSTek       | M2R-FVM                     | [eb934cc46a](https://linux-hardware.org/?probe=eb934cc46a) | Mar 23, 2022 |
| ASRock        | B560M-HDV                   | [f54eafc909](https://linux-hardware.org/?probe=f54eafc909) | Mar 23, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [ae49c43f44](https://linux-hardware.org/?probe=ae49c43f44) | Mar 23, 2022 |
| HP            | 3048h                       | [fdbbb2adf6](https://linux-hardware.org/?probe=fdbbb2adf6) | Mar 23, 2022 |
| HP            | 18E4                        | [42cc8215b7](https://linux-hardware.org/?probe=42cc8215b7) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | [81ba20b0d1](https://linux-hardware.org/?probe=81ba20b0d1) | Mar 23, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a9df37f3f0](https://linux-hardware.org/?probe=a9df37f3f0) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [388e425010](https://linux-hardware.org/?probe=388e425010) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | [e7181d25ff](https://linux-hardware.org/?probe=e7181d25ff) | Mar 23, 2022 |
| ASUSTek       | PRIME B450M-K II            | [27b65f8212](https://linux-hardware.org/?probe=27b65f8212) | Mar 23, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASUSTek       | P8B75-M LE                  | [a2055267ff](https://linux-hardware.org/?probe=a2055267ff) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f4e6e46fc5](https://linux-hardware.org/?probe=f4e6e46fc5) | Mar 23, 2022 |
| Unknown       | YL-J1900-V1                 | [add4b942ef](https://linux-hardware.org/?probe=add4b942ef) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| Dell          | 0VNP2H A00                  | [7f8e588fd2](https://linux-hardware.org/?probe=7f8e588fd2) | Mar 23, 2022 |
| ASRock        | X570 Taichi                 | [a889471411](https://linux-hardware.org/?probe=a889471411) | Mar 23, 2022 |
| HP            | 18E9                        | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| MSI           | H61M-P21                    | [99db7fcf53](https://linux-hardware.org/?probe=99db7fcf53) | Mar 23, 2022 |
| Intel         | Unknown                     | [169b017d29](https://linux-hardware.org/?probe=169b017d29) | Mar 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e75d387eea](https://linux-hardware.org/?probe=e75d387eea) | Mar 23, 2022 |
| ASUSTek       | P8Z68-V LX                  | [cf169cd574](https://linux-hardware.org/?probe=cf169cd574) | Mar 23, 2022 |
| ASRock        | X570 Steel Legend           | [b8906f2c35](https://linux-hardware.org/?probe=b8906f2c35) | Mar 23, 2022 |
| Alienware     | 0FPV4P A00                  | [b1d20542b8](https://linux-hardware.org/?probe=b1d20542b8) | Mar 23, 2022 |
| HP            | 0B4Ch D                     | [5936c86b5d](https://linux-hardware.org/?probe=5936c86b5d) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [86c831ce79](https://linux-hardware.org/?probe=86c831ce79) | Mar 23, 2022 |
| Gigabyte      | X99-Designare EX-CF         | [868791f75e](https://linux-hardware.org/?probe=868791f75e) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| Dell          | 0D883F A06                  | [7966cb4145](https://linux-hardware.org/?probe=7966cb4145) | Mar 23, 2022 |
| MSI           | 2A9C                        | [5789a9614f](https://linux-hardware.org/?probe=5789a9614f) | Mar 23, 2022 |
| Foxconn       | G31MX Series                | [911987151a](https://linux-hardware.org/?probe=911987151a) | Mar 23, 2022 |
| Gigabyte      | G1.Sniper Z97               | [3024cce066](https://linux-hardware.org/?probe=3024cce066) | Mar 23, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [ce3756c3cb](https://linux-hardware.org/?probe=ce3756c3cb) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M LX3                | [305ac1dddd](https://linux-hardware.org/?probe=305ac1dddd) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c5a0300da9](https://linux-hardware.org/?probe=c5a0300da9) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| Dell          | 0NK70N A03                  | [e5fe628a7b](https://linux-hardware.org/?probe=e5fe628a7b) | Mar 23, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [d9a46720c0](https://linux-hardware.org/?probe=d9a46720c0) | Mar 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [44ff6c5827](https://linux-hardware.org/?probe=44ff6c5827) | Mar 22, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [39b19d4ecf](https://linux-hardware.org/?probe=39b19d4ecf) | Mar 22, 2022 |
| Dell          | 0YMVJ6 A00                  | [0db6363744](https://linux-hardware.org/?probe=0db6363744) | Mar 22, 2022 |
| HP            | 3397                        | [51dd330f09](https://linux-hardware.org/?probe=51dd330f09) | Mar 22, 2022 |
| HP            | ProLiant ML310e Gen8        | [db93476384](https://linux-hardware.org/?probe=db93476384) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| Biostar       | H61MLV2                     | [1bce4dc771](https://linux-hardware.org/?probe=1bce4dc771) | Mar 22, 2022 |
| Biostar       | H61MLV2                     | [4d97559516](https://linux-hardware.org/?probe=4d97559516) | Mar 22, 2022 |
| ASRock        | B75M-GL R2.0                | [b80c58b93c](https://linux-hardware.org/?probe=b80c58b93c) | Mar 22, 2022 |
| ASUSTek       | M2N-MX                      | [6d2cb7a6f5](https://linux-hardware.org/?probe=6d2cb7a6f5) | Mar 22, 2022 |
| ASUSTek       | A68HM-PLUS                  | [21e6b2c7c3](https://linux-hardware.org/?probe=21e6b2c7c3) | Mar 22, 2022 |
| ASUSTek       | Maximus IX HERO             | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| Intel         | DG45ID AAE46743-302         | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b2d23b47a5](https://linux-hardware.org/?probe=b2d23b47a5) | Mar 22, 2022 |
| ASUSTek       | PRIME B550M-A               | [aa6203abee](https://linux-hardware.org/?probe=aa6203abee) | Mar 22, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [5298f9dcc9](https://linux-hardware.org/?probe=5298f9dcc9) | Mar 22, 2022 |
| Foxconn       | G31MX Series                | [7d9cc6ac07](https://linux-hardware.org/?probe=7d9cc6ac07) | Mar 22, 2022 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [d1fd7ebdcc](https://linux-hardware.org/?probe=d1fd7ebdcc) | Mar 22, 2022 |
| Gigabyte      | B450M S2H V2                | [a8e8d6dd5e](https://linux-hardware.org/?probe=a8e8d6dd5e) | Mar 22, 2022 |
| Gigabyte      | AX370-Gaming K7             | [eddbf95bd8](https://linux-hardware.org/?probe=eddbf95bd8) | Mar 22, 2022 |
| Intel         | E5 M2L-8D                   | [12234d8f86](https://linux-hardware.org/?probe=12234d8f86) | Mar 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ddf8fb6916](https://linux-hardware.org/?probe=ddf8fb6916) | Mar 22, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | [7bbd4d76d8](https://linux-hardware.org/?probe=7bbd4d76d8) | Mar 22, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [6239582d24](https://linux-hardware.org/?probe=6239582d24) | Mar 22, 2022 |
| Gigabyte      | AX370-Gaming K7             | [1cef860a0a](https://linux-hardware.org/?probe=1cef860a0a) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [3429bc98ac](https://linux-hardware.org/?probe=3429bc98ac) | Mar 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d24fcefe24](https://linux-hardware.org/?probe=d24fcefe24) | Mar 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9183654349](https://linux-hardware.org/?probe=9183654349) | Mar 22, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [3625536523](https://linux-hardware.org/?probe=3625536523) | Mar 22, 2022 |
| Acer          | Veriton M6660G V:1.0        | [228974c486](https://linux-hardware.org/?probe=228974c486) | Mar 22, 2022 |
| ASUSTek       | X99-M WS                    | [5f29519a18](https://linux-hardware.org/?probe=5f29519a18) | Mar 22, 2022 |
| Biostar       | J3060NH                     | [cabe778eeb](https://linux-hardware.org/?probe=cabe778eeb) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Dell          | 0K3CM7 A00                  | [8f5ec6c004](https://linux-hardware.org/?probe=8f5ec6c004) | Mar 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7a02e1b55c](https://linux-hardware.org/?probe=7a02e1b55c) | Mar 22, 2022 |
| Gigabyte      | P55-UD3L                    | [ee3e9ec967](https://linux-hardware.org/?probe=ee3e9ec967) | Mar 22, 2022 |
| Gigabyte      | M61PME-S2P                  | [ccb3b312a1](https://linux-hardware.org/?probe=ccb3b312a1) | Mar 22, 2022 |
| HP            | 1589                        | [a97fa22164](https://linux-hardware.org/?probe=a97fa22164) | Mar 22, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [28ac28ad02](https://linux-hardware.org/?probe=28ac28ad02) | Mar 22, 2022 |
| NU591         | 1.0                         | [a2e3eb7d41](https://linux-hardware.org/?probe=a2e3eb7d41) | Mar 22, 2022 |
| MSI           | MS-7619                     | [65c73f26b0](https://linux-hardware.org/?probe=65c73f26b0) | Mar 22, 2022 |
| ASRock        | Z370 Extreme4               | [f39b16204a](https://linux-hardware.org/?probe=f39b16204a) | Mar 22, 2022 |
| ASUSTek       | PRIME X299-A II             | [631ae2fff8](https://linux-hardware.org/?probe=631ae2fff8) | Mar 22, 2022 |
| Apple         | Mac-27AD2F918AE68F61        | [03e06a3a70](https://linux-hardware.org/?probe=03e06a3a70) | Mar 22, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [0ae4b366a6](https://linux-hardware.org/?probe=0ae4b366a6) | Mar 22, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [1b06197c8b](https://linux-hardware.org/?probe=1b06197c8b) | Mar 22, 2022 |
| ASRock        | X370 Killer SLI             | [8f2239d221](https://linux-hardware.org/?probe=8f2239d221) | Mar 22, 2022 |
| ASUSTek       | P8B75-M                     | [6788522a8a](https://linux-hardware.org/?probe=6788522a8a) | Mar 22, 2022 |
| Dell          | 040DDP A01                  | [d034ba5d2b](https://linux-hardware.org/?probe=d034ba5d2b) | Mar 22, 2022 |
| HP            | 0AECh D                     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| Gigabyte      | G31M-ES2L                   | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [91d5c07184](https://linux-hardware.org/?probe=91d5c07184) | Mar 22, 2022 |
| ASRock        | B550M-HDV                   | [22983e54a4](https://linux-hardware.org/?probe=22983e54a4) | Mar 22, 2022 |
| ASUSTek       | P8Z68-V LX                  | [e7f8300ff6](https://linux-hardware.org/?probe=e7f8300ff6) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [d2e30b1d8b](https://linux-hardware.org/?probe=d2e30b1d8b) | Mar 22, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [ac271ec90a](https://linux-hardware.org/?probe=ac271ec90a) | Mar 22, 2022 |
| HP            | 859C                        | [4c598fdb6d](https://linux-hardware.org/?probe=4c598fdb6d) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [72e8662f26](https://linux-hardware.org/?probe=72e8662f26) | Mar 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [66f133fcf0](https://linux-hardware.org/?probe=66f133fcf0) | Mar 22, 2022 |
| Unknown       | YL-J1900-V1                 | [396ac36ac2](https://linux-hardware.org/?probe=396ac36ac2) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2c7a4a9552](https://linux-hardware.org/?probe=2c7a4a9552) | Mar 22, 2022 |
| Unknown       | T3 MRD                      | [1e89cedec2](https://linux-hardware.org/?probe=1e89cedec2) | Mar 22, 2022 |
| ASUSTek       | A88XM-A                     | [052225ab9a](https://linux-hardware.org/?probe=052225ab9a) | Mar 22, 2022 |
| Gigabyte      | A320M-H-CF                  | [1462cd20b7](https://linux-hardware.org/?probe=1462cd20b7) | Mar 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e3d131ff9a](https://linux-hardware.org/?probe=e3d131ff9a) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | P5K                         | [da0019c5d0](https://linux-hardware.org/?probe=da0019c5d0) | Mar 22, 2022 |
| ASRock        | N68C-S UCC                  | [4346995b24](https://linux-hardware.org/?probe=4346995b24) | Mar 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [dec65a823a](https://linux-hardware.org/?probe=dec65a823a) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [012e192ece](https://linux-hardware.org/?probe=012e192ece) | Mar 22, 2022 |
| MSI           | B450M PRO-VDH MAX           | [a6718f483b](https://linux-hardware.org/?probe=a6718f483b) | Mar 22, 2022 |
| ASRock        | AB350M-HDV                  | [069ce018ad](https://linux-hardware.org/?probe=069ce018ad) | Mar 22, 2022 |
| MSI           | MS-7250                     | [c115855cc4](https://linux-hardware.org/?probe=c115855cc4) | Mar 22, 2022 |
| ZOTAC         | Unknown                     | [395ccacda8](https://linux-hardware.org/?probe=395ccacda8) | Mar 22, 2022 |
| ASRock        | 970 Pro3 R2.0               | [7662478d56](https://linux-hardware.org/?probe=7662478d56) | Mar 22, 2022 |
| HP            | 18E4                        | [c4dec6c79b](https://linux-hardware.org/?probe=c4dec6c79b) | Mar 22, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | [35f8ba571f](https://linux-hardware.org/?probe=35f8ba571f) | Mar 22, 2022 |
| HP            | 18E4                        | [e06e0c412c](https://linux-hardware.org/?probe=e06e0c412c) | Mar 22, 2022 |
| Digiboard     | MPxx                        | [b3bb9ff288](https://linux-hardware.org/?probe=b3bb9ff288) | Mar 22, 2022 |
| Dell          | 04GJJT A00                  | [0b2a7b240f](https://linux-hardware.org/?probe=0b2a7b240f) | Mar 22, 2022 |
| Gigabyte      | X570S AERO G                | [97cfd592c5](https://linux-hardware.org/?probe=97cfd592c5) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d755a1a962](https://linux-hardware.org/?probe=d755a1a962) | Mar 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bea334f9c7](https://linux-hardware.org/?probe=bea334f9c7) | Mar 22, 2022 |
| ASUSTek       | P5KC                        | [b4511f91a2](https://linux-hardware.org/?probe=b4511f91a2) | Mar 22, 2022 |
| Colorful T... | A320M-K PRO YV14            | [94393a4d0a](https://linux-hardware.org/?probe=94393a4d0a) | Mar 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [4307f7f265](https://linux-hardware.org/?probe=4307f7f265) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2cfe733664](https://linux-hardware.org/?probe=2cfe733664) | Mar 22, 2022 |
| ASRock        | B450 Steel Legend           | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Pegatron      | 2AB6                        | [9e862658aa](https://linux-hardware.org/?probe=9e862658aa) | Mar 22, 2022 |
| Biostar       | J3060NH                     | [2b4227a591](https://linux-hardware.org/?probe=2b4227a591) | Mar 22, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| ASUSTek       | M3A78-CM                    | [ff9f133207](https://linux-hardware.org/?probe=ff9f133207) | Mar 22, 2022 |
| ASUSTek       | Q87M-E                      | [42e766a482](https://linux-hardware.org/?probe=42e766a482) | Mar 22, 2022 |
| HP            | ProLiant ML310e Gen8        | [c8afce0622](https://linux-hardware.org/?probe=c8afce0622) | Mar 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [5d6041ffc4](https://linux-hardware.org/?probe=5d6041ffc4) | Mar 21, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [7c5dff1166](https://linux-hardware.org/?probe=7c5dff1166) | Mar 21, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| ABIT          | IP35-E                      | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| MSI           | 760GM -E51                  | [fd746ce3ee](https://linux-hardware.org/?probe=fd746ce3ee) | Mar 21, 2022 |
| ASRock        | B75M-GL R2.0                | [8b7a65c8e3](https://linux-hardware.org/?probe=8b7a65c8e3) | Mar 21, 2022 |
| MiTAC         | UltraPoint                  | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| ASUSTek       | H81M-E                      | [069849c461](https://linux-hardware.org/?probe=069849c461) | Mar 21, 2022 |
| ABIT          | IP35-E                      | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| Foxconn       | 2ABF                        | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| MSI           | B560-A PRO                  | [70f24bb773](https://linux-hardware.org/?probe=70f24bb773) | Mar 21, 2022 |
| ASRock        | FM2A75 Pro4+                | [0d7edce12d](https://linux-hardware.org/?probe=0d7edce12d) | Mar 21, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [747e4d92cf](https://linux-hardware.org/?probe=747e4d92cf) | Mar 21, 2022 |
| HP            | 802E                        | [b15f756d65](https://linux-hardware.org/?probe=b15f756d65) | Mar 21, 2022 |
| MSI           | E350IA-E45                  | [84a19b6203](https://linux-hardware.org/?probe=84a19b6203) | Mar 21, 2022 |
| HP            | 0B54h D                     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| ASRock        | G41C-GS R2.0                | [6cd511ea30](https://linux-hardware.org/?probe=6cd511ea30) | Mar 21, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [4492e433cd](https://linux-hardware.org/?probe=4492e433cd) | Mar 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [366258c1f2](https://linux-hardware.org/?probe=366258c1f2) | Mar 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | [672496577e](https://linux-hardware.org/?probe=672496577e) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Gigabyte      | Z77MX-D3H                   | [142036cdc3](https://linux-hardware.org/?probe=142036cdc3) | Mar 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [9ca3ea91d3](https://linux-hardware.org/?probe=9ca3ea91d3) | Mar 21, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [bfe7047633](https://linux-hardware.org/?probe=bfe7047633) | Mar 21, 2022 |
| ASUSTek       | PRIME H510M-A               | [9c0d4c37d8](https://linux-hardware.org/?probe=9c0d4c37d8) | Mar 21, 2022 |
| HP            | 3032h                       | [e57d52908c](https://linux-hardware.org/?probe=e57d52908c) | Mar 21, 2022 |
| ASRock        | H61M-VS                     | [c795f0ba68](https://linux-hardware.org/?probe=c795f0ba68) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f4552c4008](https://linux-hardware.org/?probe=f4552c4008) | Mar 21, 2022 |
| Supermicro    | C2SBC-Q                     | [338275254e](https://linux-hardware.org/?probe=338275254e) | Mar 21, 2022 |
| Gigabyte      | H81M-S2V                    | [d8f482f916](https://linux-hardware.org/?probe=d8f482f916) | Mar 21, 2022 |
| Gigabyte      | Z97-HD3                     | [46c12ec623](https://linux-hardware.org/?probe=46c12ec623) | Mar 21, 2022 |
| ASRock        | B75M-GL R2.0                | [f4d30f6c20](https://linux-hardware.org/?probe=f4d30f6c20) | Mar 21, 2022 |
| MSI           | MS-7360                     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| Gigabyte      | P35-DS3P                    | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| MSI           | A320M-A PRO MAX             | [8ffacf54c4](https://linux-hardware.org/?probe=8ffacf54c4) | Mar 21, 2022 |
| ASUSTek       | M5A78L-M LX3                | [80ef8b623c](https://linux-hardware.org/?probe=80ef8b623c) | Mar 21, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | [b789768b64](https://linux-hardware.org/?probe=b789768b64) | Mar 21, 2022 |
| MACHINIST     | X99-G7 V1.0                 | [70a784f09c](https://linux-hardware.org/?probe=70a784f09c) | Mar 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | [b379b1157c](https://linux-hardware.org/?probe=b379b1157c) | Mar 21, 2022 |
| ASRock        | B550 Extreme4               | [9c194b83e5](https://linux-hardware.org/?probe=9c194b83e5) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B560M-A               | [0b69dcafad](https://linux-hardware.org/?probe=0b69dcafad) | Mar 21, 2022 |
| Gigabyte      | GA-970A-DS3                 | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | Z490 VISION D               | [da9773a25d](https://linux-hardware.org/?probe=da9773a25d) | Mar 21, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [f2fb8fc533](https://linux-hardware.org/?probe=f2fb8fc533) | Mar 21, 2022 |
| MSI           | MAG B550M MORTAR            | [78b6d2b02e](https://linux-hardware.org/?probe=78b6d2b02e) | Mar 21, 2022 |
| MSI           | Z87-G45 GAMING              | [a4d8d08ea6](https://linux-hardware.org/?probe=a4d8d08ea6) | Mar 21, 2022 |
| Dell          | 07T4MC A09                  | [ef5f0dcfe7](https://linux-hardware.org/?probe=ef5f0dcfe7) | Mar 21, 2022 |
| MSI           | MAG B550M MORTAR            | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [c294e20164](https://linux-hardware.org/?probe=c294e20164) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [5b9b7903ad](https://linux-hardware.org/?probe=5b9b7903ad) | Mar 21, 2022 |
| ASUSTek       | B150 PRO GAMING             | [fce8e3cc98](https://linux-hardware.org/?probe=fce8e3cc98) | Mar 21, 2022 |
| MSI           | H510M PRO-E                 | [111cf21b7f](https://linux-hardware.org/?probe=111cf21b7f) | Mar 21, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [0fab7594d6](https://linux-hardware.org/?probe=0fab7594d6) | Mar 21, 2022 |
| Dell          | 0VD92X A00                  | [1f00b8ed57](https://linux-hardware.org/?probe=1f00b8ed57) | Mar 21, 2022 |
| ASRock        | Z270 Extreme4               | [0f3a8eb166](https://linux-hardware.org/?probe=0f3a8eb166) | Mar 21, 2022 |
| HP            | 8054                        | [38288fadf8](https://linux-hardware.org/?probe=38288fadf8) | Mar 21, 2022 |
| ASUSTek       | P5KC                        | [b2fd45aebb](https://linux-hardware.org/?probe=b2fd45aebb) | Mar 21, 2022 |
| ASUSTek       | SABERTOOTH X79              | [9e6ccdc0e4](https://linux-hardware.org/?probe=9e6ccdc0e4) | Mar 21, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [3c97963539](https://linux-hardware.org/?probe=3c97963539) | Mar 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [621ad4beae](https://linux-hardware.org/?probe=621ad4beae) | Mar 21, 2022 |
| Intel         | DH55TC AAE70932-301         | [e0c4ac33b9](https://linux-hardware.org/?probe=e0c4ac33b9) | Mar 21, 2022 |
| Dell          | 04GJJT A00                  | [b94dc1035d](https://linux-hardware.org/?probe=b94dc1035d) | Mar 21, 2022 |
| ASRock        | B550 Steel Legend           | [5c1495ecf1](https://linux-hardware.org/?probe=5c1495ecf1) | Mar 21, 2022 |
| Intel         | H55                         | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| ASUSTek       | P5B                         | [0ec5966c98](https://linux-hardware.org/?probe=0ec5966c98) | Mar 21, 2022 |
| MSI           | MAG B550M BAZOOKA           | [fbbcb0de35](https://linux-hardware.org/?probe=fbbcb0de35) | Mar 21, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [279bb03666](https://linux-hardware.org/?probe=279bb03666) | Mar 21, 2022 |
| Gigabyte      | B560M H                     | [dad19ddec6](https://linux-hardware.org/?probe=dad19ddec6) | Mar 20, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| ASUSTek       | PRIME Z370-P                | [a5937e694a](https://linux-hardware.org/?probe=a5937e694a) | Mar 20, 2022 |
| ASRock        | B550 Steel Legend           | [00ea7017ff](https://linux-hardware.org/?probe=00ea7017ff) | Mar 20, 2022 |
| Dell          | 0XJ8C4 A00                  | [2b010e4e7c](https://linux-hardware.org/?probe=2b010e4e7c) | Mar 20, 2022 |
| ASUSTek       | M4A78-VM                    | [c48ac764a4](https://linux-hardware.org/?probe=c48ac764a4) | Mar 20, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [8ed2aea22d](https://linux-hardware.org/?probe=8ed2aea22d) | Mar 20, 2022 |
| ASRock        | G41C-GS                     | [baab4934ee](https://linux-hardware.org/?probe=baab4934ee) | Mar 20, 2022 |
| MSI           | Z390-A PRO                  | [bd978690a8](https://linux-hardware.org/?probe=bd978690a8) | Mar 20, 2022 |
| HP            | 18E7                        | [727446a2df](https://linux-hardware.org/?probe=727446a2df) | Mar 20, 2022 |
| ASUSTek       | A68HM-PLUS                  | [d4a63f4b81](https://linux-hardware.org/?probe=d4a63f4b81) | Mar 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f8f92ef73d](https://linux-hardware.org/?probe=f8f92ef73d) | Mar 20, 2022 |
| Gigabyte      | Z77-DS3H                    | [d9a23e9bfb](https://linux-hardware.org/?probe=d9a23e9bfb) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| MSI           | MS-7388                     | [d68b981042](https://linux-hardware.org/?probe=d68b981042) | Mar 20, 2022 |
| MSI           | X570-A PRO                  | [622384c18e](https://linux-hardware.org/?probe=622384c18e) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| MSI           | H81M-E34                    | [2278c36b03](https://linux-hardware.org/?probe=2278c36b03) | Mar 20, 2022 |
| Gigabyte      | AX370-Gaming K7             | [37599ed869](https://linux-hardware.org/?probe=37599ed869) | Mar 20, 2022 |
| MSI           | B250M PRO-VH                | [d3885311bc](https://linux-hardware.org/?probe=d3885311bc) | Mar 20, 2022 |
| MSI           | A320M-A PRO MAX             | [7504eeaaa1](https://linux-hardware.org/?probe=7504eeaaa1) | Mar 20, 2022 |
| Acer          | Aspire X1440                | [dba7164067](https://linux-hardware.org/?probe=dba7164067) | Mar 20, 2022 |
| Intel         | B75                         | [242c4cde30](https://linux-hardware.org/?probe=242c4cde30) | Mar 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d98f42c86b](https://linux-hardware.org/?probe=d98f42c86b) | Mar 20, 2022 |
| ECS           | H87H3-M                     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | [0008f2b843](https://linux-hardware.org/?probe=0008f2b843) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | [34d7600473](https://linux-hardware.org/?probe=34d7600473) | Mar 20, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [3bd6a87950](https://linux-hardware.org/?probe=3bd6a87950) | Mar 20, 2022 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [8ab51e0212](https://linux-hardware.org/?probe=8ab51e0212) | Mar 20, 2022 |
| HP            | 3397                        | [60dc930e32](https://linux-hardware.org/?probe=60dc930e32) | Mar 20, 2022 |
| VIA Techno... | KM266-8235                  | [ad3f9e9e12](https://linux-hardware.org/?probe=ad3f9e9e12) | Mar 20, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | [1bfef458ea](https://linux-hardware.org/?probe=1bfef458ea) | Mar 20, 2022 |
| MSI           | B560M PRO-VDH               | [b171a344f7](https://linux-hardware.org/?probe=b171a344f7) | Mar 20, 2022 |
| MSI           | B450M GAMING PLUS           | [9f0ed452aa](https://linux-hardware.org/?probe=9f0ed452aa) | Mar 20, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | [8d38254b48](https://linux-hardware.org/?probe=8d38254b48) | Mar 20, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | [db394898e7](https://linux-hardware.org/?probe=db394898e7) | Mar 20, 2022 |
| Unknown       | Unknown                     | [a9ac1b42ff](https://linux-hardware.org/?probe=a9ac1b42ff) | Mar 20, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [15e53dcce2](https://linux-hardware.org/?probe=15e53dcce2) | Mar 20, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [e2d7611daa](https://linux-hardware.org/?probe=e2d7611daa) | Mar 20, 2022 |
| Gigabyte      | B450 AORUS M                | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [daa5dd8024](https://linux-hardware.org/?probe=daa5dd8024) | Mar 20, 2022 |
| Dell          | 042P49 A02                  | [1a94f7526c](https://linux-hardware.org/?probe=1a94f7526c) | Mar 20, 2022 |
| Gigabyte      | H510M H                     | [4e555a8efa](https://linux-hardware.org/?probe=4e555a8efa) | Mar 20, 2022 |
| Gigabyte      | GA-MA69VM-S2                | [5b7201b789](https://linux-hardware.org/?probe=5b7201b789) | Mar 20, 2022 |
| ASRock        | B560 Steel Legend           | [29e1abc7b1](https://linux-hardware.org/?probe=29e1abc7b1) | Mar 20, 2022 |
| ASRock        | 890GX Extreme4              | [3c57e1ac31](https://linux-hardware.org/?probe=3c57e1ac31) | Mar 20, 2022 |
| Foxconn       | H67M-S/H67M-V/H67M          | [ced87dc2b5](https://linux-hardware.org/?probe=ced87dc2b5) | Mar 20, 2022 |
| MSI           | Z390-A PRO                  | [a6674cd472](https://linux-hardware.org/?probe=a6674cd472) | Mar 20, 2022 |
| ASUSTek       | PRIME Z590-A                | [bb400c5756](https://linux-hardware.org/?probe=bb400c5756) | Mar 20, 2022 |
| MSI           | A320M-A PRO MAX             | [f3ed30e261](https://linux-hardware.org/?probe=f3ed30e261) | Mar 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [536bac0d6a](https://linux-hardware.org/?probe=536bac0d6a) | Mar 20, 2022 |
| ASRock        | 890GX Extreme4              | [8c38c582bf](https://linux-hardware.org/?probe=8c38c582bf) | Mar 20, 2022 |
| HP            | 212B                        | [fd6a569226](https://linux-hardware.org/?probe=fd6a569226) | Mar 20, 2022 |
| ASUSTek       | NODUSM3                     | [14c35dc52c](https://linux-hardware.org/?probe=14c35dc52c) | Mar 20, 2022 |
| ECS           | Nettle2                     | [7de5975b89](https://linux-hardware.org/?probe=7de5975b89) | Mar 20, 2022 |
| Gigabyte      | G41MT-S2PT                  | [ddc4f4eb12](https://linux-hardware.org/?probe=ddc4f4eb12) | Mar 20, 2022 |
| Unknown       | Unknown                     | [4f882f4865](https://linux-hardware.org/?probe=4f882f4865) | Mar 20, 2022 |
| Dell          | 0GDG8Y A00                  | [1deed3b4bb](https://linux-hardware.org/?probe=1deed3b4bb) | Mar 20, 2022 |
| Unknown       | Unknown                     | [cb949f34eb](https://linux-hardware.org/?probe=cb949f34eb) | Mar 20, 2022 |
| Gigabyte      | Z590 VISION G               | [8740fa2680](https://linux-hardware.org/?probe=8740fa2680) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| ASUSTek       | H170 PRO GAMING             | [8ce1eed900](https://linux-hardware.org/?probe=8ce1eed900) | Mar 20, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [b4287e3cb1](https://linux-hardware.org/?probe=b4287e3cb1) | Mar 20, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| Lenovo        | ThinkStation S30 060618U    | [c448617378](https://linux-hardware.org/?probe=c448617378) | Mar 20, 2022 |
| Biostar       | G41D3+                      | [8d6a4e54b1](https://linux-hardware.org/?probe=8d6a4e54b1) | Mar 20, 2022 |
| Dell          | 0F3KHR A00                  | [b312650d8d](https://linux-hardware.org/?probe=b312650d8d) | Mar 20, 2022 |
| ASRock        | H370M-HDV                   | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [01ad19348a](https://linux-hardware.org/?probe=01ad19348a) | Mar 20, 2022 |
| AMI           | Cherry Trail Tablet         | [d0d93b8255](https://linux-hardware.org/?probe=d0d93b8255) | Mar 20, 2022 |
| MSI           | MEG Z390 ACE                | [688c3edc68](https://linux-hardware.org/?probe=688c3edc68) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| ASRock        | H61M-VG3                    | [6e1d3b66a7](https://linux-hardware.org/?probe=6e1d3b66a7) | Mar 20, 2022 |
| Gigabyte      | B450 GAMING X               | [2fd6e0b6e8](https://linux-hardware.org/?probe=2fd6e0b6e8) | Mar 20, 2022 |
| HP            | 2129                        | [9e7ce5ec4f](https://linux-hardware.org/?probe=9e7ce5ec4f) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | [f3e67de15e](https://linux-hardware.org/?probe=f3e67de15e) | Mar 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | [beda807e51](https://linux-hardware.org/?probe=beda807e51) | Mar 20, 2022 |
| Unknown       | Unknown                     | [ba50ffd3f8](https://linux-hardware.org/?probe=ba50ffd3f8) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | [78676e017b](https://linux-hardware.org/?probe=78676e017b) | Mar 19, 2022 |
| HP            | 1906                        | [5a67de9420](https://linux-hardware.org/?probe=5a67de9420) | Mar 19, 2022 |
| Dell          | 0NV0M7 A02                  | [978401b13f](https://linux-hardware.org/?probe=978401b13f) | Mar 19, 2022 |
| HP            | 2129                        | [0d503098ab](https://linux-hardware.org/?probe=0d503098ab) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| ASRock        | H55M-LE                     | [f789f4563a](https://linux-hardware.org/?probe=f789f4563a) | Mar 19, 2022 |
| Gigabyte      | X570 GAMING X               | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Dell          | 0P01GV A03                  | [54c52f2837](https://linux-hardware.org/?probe=54c52f2837) | Mar 19, 2022 |
| ASUSTek       | P8Z68-V LX                  | [2b99f73675](https://linux-hardware.org/?probe=2b99f73675) | Mar 19, 2022 |
| Gigabyte      | F2A78M-HD2                  | [ae9d2db004](https://linux-hardware.org/?probe=ae9d2db004) | Mar 19, 2022 |
| Gigabyte      | Z77X-UD3H                   | [9ad4cf0954](https://linux-hardware.org/?probe=9ad4cf0954) | Mar 19, 2022 |
| ASUSTek       | VC62B                       | [c7bb3b876e](https://linux-hardware.org/?probe=c7bb3b876e) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [8ba917619e](https://linux-hardware.org/?probe=8ba917619e) | Mar 19, 2022 |
| MSI           | B350 TOMAHAWK               | [174ce8eaee](https://linux-hardware.org/?probe=174ce8eaee) | Mar 19, 2022 |
| Gigabyte      | X570 AORUS PRO              | [861e43b0c6](https://linux-hardware.org/?probe=861e43b0c6) | Mar 19, 2022 |
| Gigabyte      | B450M GAMING                | [9cc0fc6cd0](https://linux-hardware.org/?probe=9cc0fc6cd0) | Mar 19, 2022 |
| ASRock        | A55M-HVS                    | [b10a9e37bb](https://linux-hardware.org/?probe=b10a9e37bb) | Mar 19, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8328ee30d7](https://linux-hardware.org/?probe=8328ee30d7) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [48c7f5e6ae](https://linux-hardware.org/?probe=48c7f5e6ae) | Mar 19, 2022 |
| Gigabyte      | Z170-Gaming K3-CF           | [fb3415d61d](https://linux-hardware.org/?probe=fb3415d61d) | Mar 19, 2022 |
| Acer          | Aspire XC600 v1.0           | [4191a185d4](https://linux-hardware.org/?probe=4191a185d4) | Mar 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [73bf7d8080](https://linux-hardware.org/?probe=73bf7d8080) | Mar 19, 2022 |
| ASUSTek       | P8B75-M                     | [b1a437de4c](https://linux-hardware.org/?probe=b1a437de4c) | Mar 19, 2022 |
| HP            | 1497                        | [2aac5eaf08](https://linux-hardware.org/?probe=2aac5eaf08) | Mar 19, 2022 |
| HP            | 1497                        | [ec392b9979](https://linux-hardware.org/?probe=ec392b9979) | Mar 19, 2022 |
| Dell          | 0R6PCT A01                  | [de08cb0741](https://linux-hardware.org/?probe=de08cb0741) | Mar 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | [90adc19337](https://linux-hardware.org/?probe=90adc19337) | Mar 19, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [9cdf9a4b0b](https://linux-hardware.org/?probe=9cdf9a4b0b) | Mar 19, 2022 |
| HP            | 8906 SMVB                   | [da9b5fc00d](https://linux-hardware.org/?probe=da9b5fc00d) | Mar 19, 2022 |
| Dell          | 0VRWRC A01                  | [48a73bd70f](https://linux-hardware.org/?probe=48a73bd70f) | Mar 19, 2022 |
| Dell          | 0VRWRC A01                  | [bcced0a8f2](https://linux-hardware.org/?probe=bcced0a8f2) | Mar 19, 2022 |
| ASRock        | Z270 Gaming K4              | [fd96a47e75](https://linux-hardware.org/?probe=fd96a47e75) | Mar 19, 2022 |
| HP            | 8906 SMVB                   | [b07f0b09c6](https://linux-hardware.org/?probe=b07f0b09c6) | Mar 19, 2022 |
| ASUSTek       | B150M-PLUS D3               | [3ab8a178e9](https://linux-hardware.org/?probe=3ab8a178e9) | Mar 19, 2022 |
| ASUSTek       | H110I-PLUS                  | [6a83a88b15](https://linux-hardware.org/?probe=6a83a88b15) | Mar 19, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [97e0d86243](https://linux-hardware.org/?probe=97e0d86243) | Mar 19, 2022 |
| MSI           | A320M-A PRO MAX             | [b77a3343c9](https://linux-hardware.org/?probe=b77a3343c9) | Mar 19, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [a763963402](https://linux-hardware.org/?probe=a763963402) | Mar 19, 2022 |
| ASUSTek       | P7P55D LE                   | [df99604e73](https://linux-hardware.org/?probe=df99604e73) | Mar 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [3c40d0446b](https://linux-hardware.org/?probe=3c40d0446b) | Mar 19, 2022 |
| MACHINIST     | X99-G7 V1.0                 | [ebc42c3206](https://linux-hardware.org/?probe=ebc42c3206) | Mar 19, 2022 |
| Gigabyte      | H97-HD3                     | [92215486d6](https://linux-hardware.org/?probe=92215486d6) | Mar 19, 2022 |
| ECS           | A990FXM-A                   | [32deb5b6a1](https://linux-hardware.org/?probe=32deb5b6a1) | Mar 19, 2022 |
| Online Lab... | SR 42                       | [2e13340a50](https://linux-hardware.org/?probe=2e13340a50) | Mar 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| Unknown       | X79-P3                      | [df0d4ee1a9](https://linux-hardware.org/?probe=df0d4ee1a9) | Mar 19, 2022 |
| Unknown       | X79-P3                      | [ab104fe8c0](https://linux-hardware.org/?probe=ab104fe8c0) | Mar 19, 2022 |
| ASRock        | B450M Pro4                  | [eca789aa9e](https://linux-hardware.org/?probe=eca789aa9e) | Mar 19, 2022 |
| Gigabyte      | GA-78LMT-S2 R2              | [550ded7f81](https://linux-hardware.org/?probe=550ded7f81) | Mar 19, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| ECS           | P4M900T-M2                  | [262211610d](https://linux-hardware.org/?probe=262211610d) | Mar 19, 2022 |
| ASUSTek       | B85M-E                      | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | J1800I-C/BR                 | [4d11bb964b](https://linux-hardware.org/?probe=4d11bb964b) | Mar 19, 2022 |
| Dell          | 08HPGT A01                  | [30ecdb0b0e](https://linux-hardware.org/?probe=30ecdb0b0e) | Mar 19, 2022 |
| ASUSTek       | PRIME B450M-A               | [893f0d0600](https://linux-hardware.org/?probe=893f0d0600) | Mar 19, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | [1897912bfc](https://linux-hardware.org/?probe=1897912bfc) | Mar 19, 2022 |
| HP            | 212B                        | [a85896bd48](https://linux-hardware.org/?probe=a85896bd48) | Mar 19, 2022 |
| HP            | 1589                        | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| HP            | 2B4B                        | [def1b2ee5b](https://linux-hardware.org/?probe=def1b2ee5b) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6c063a5e86](https://linux-hardware.org/?probe=6c063a5e86) | Mar 19, 2022 |
| MSI           | X370 GAMING M7 ACK          | [336e7a8d1d](https://linux-hardware.org/?probe=336e7a8d1d) | Mar 19, 2022 |
| MSI           | B350 TOMAHAWK               | [10ae2a1745](https://linux-hardware.org/?probe=10ae2a1745) | Mar 19, 2022 |
| Gigabyte      | B75M-D3V                    | [116074683a](https://linux-hardware.org/?probe=116074683a) | Mar 19, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [725c0249b8](https://linux-hardware.org/?probe=725c0249b8) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6dd4a41851](https://linux-hardware.org/?probe=6dd4a41851) | Mar 19, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [6c60e6d6af](https://linux-hardware.org/?probe=6c60e6d6af) | Mar 19, 2022 |
| HP            | 212A                        | [785ff8748d](https://linux-hardware.org/?probe=785ff8748d) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| ASUSTek       | P4P800                      | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [e7534ca823](https://linux-hardware.org/?probe=e7534ca823) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34fb0ae26f](https://linux-hardware.org/?probe=34fb0ae26f) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| HP            | 0AA8h                       | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| ASUSTek       | P7H55D-M EVO                | [2e70de8c8d](https://linux-hardware.org/?probe=2e70de8c8d) | Mar 19, 2022 |
| Gigabyte      | Z370P D3-CF                 | [7da4dbd801](https://linux-hardware.org/?probe=7da4dbd801) | Mar 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [399ab158b9](https://linux-hardware.org/?probe=399ab158b9) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d64fc66c4](https://linux-hardware.org/?probe=9d64fc66c4) | Mar 19, 2022 |
| Pegatron      | 2AC3                        | [d1f5b906e4](https://linux-hardware.org/?probe=d1f5b906e4) | Mar 19, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [5415b5f876](https://linux-hardware.org/?probe=5415b5f876) | Mar 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| MSI           | Z97 GUARD-PRO               | [a412a37e5f](https://linux-hardware.org/?probe=a412a37e5f) | Mar 18, 2022 |
| Dell          | 0P611C A00                  | [0c433bca90](https://linux-hardware.org/?probe=0c433bca90) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a5d1f1ec32](https://linux-hardware.org/?probe=a5d1f1ec32) | Mar 18, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | [e46a5c3db4](https://linux-hardware.org/?probe=e46a5c3db4) | Mar 18, 2022 |
| Gigabyte      | Z170-Gaming K3-CF           | [f7c5c30266](https://linux-hardware.org/?probe=f7c5c30266) | Mar 18, 2022 |
| TPV-INVENT... | 2AF2 A01                    | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Biostar       | H61MHV2                     | [7215b0c338](https://linux-hardware.org/?probe=7215b0c338) | Mar 18, 2022 |
| Gigabyte      | B560M GAMING HD             | [7fb3161cf4](https://linux-hardware.org/?probe=7fb3161cf4) | Mar 18, 2022 |
| MSI           | MS-7360                     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Dell          | 0M863N A01                  | [f23210fa33](https://linux-hardware.org/?probe=f23210fa33) | Mar 18, 2022 |
| Gigabyte      | H410M H V3                  | [4d4f3f2f75](https://linux-hardware.org/?probe=4d4f3f2f75) | Mar 18, 2022 |
| Gigabyte      | M68MT-S2P                   | [74bdda89c3](https://linux-hardware.org/?probe=74bdda89c3) | Mar 18, 2022 |
| ASUSTek       | H81M-K                      | [9055c398c9](https://linux-hardware.org/?probe=9055c398c9) | Mar 18, 2022 |
| Gigabyte      | B560M H                     | [e1abb8fa21](https://linux-hardware.org/?probe=e1abb8fa21) | Mar 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [661d9fcffa](https://linux-hardware.org/?probe=661d9fcffa) | Mar 18, 2022 |
| Gigabyte      | A520I AC                    | [5a27854c64](https://linux-hardware.org/?probe=5a27854c64) | Mar 18, 2022 |
| ASUSTek       | PRIME B250M-A               | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Dell          | 08WKV3 A00                  | [147bdbc26d](https://linux-hardware.org/?probe=147bdbc26d) | Mar 18, 2022 |
| Gigabyte      | X48T-DQ6                    | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [47ed3a5e98](https://linux-hardware.org/?probe=47ed3a5e98) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [a2b06f49d3](https://linux-hardware.org/?probe=a2b06f49d3) | Mar 18, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0c7c91a687](https://linux-hardware.org/?probe=0c7c91a687) | Mar 18, 2022 |
| Inspur        | Computer All in one PC V... | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| ASRock        | H370M-ITX/ac                | [e425e911e9](https://linux-hardware.org/?probe=e425e911e9) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [9e32abccd6](https://linux-hardware.org/?probe=9e32abccd6) | Mar 18, 2022 |
| Gigabyte      | H110M-H-CF                  | [a164112f8d](https://linux-hardware.org/?probe=a164112f8d) | Mar 18, 2022 |
| HP            | 3397                        | [fe1ae429b1](https://linux-hardware.org/?probe=fe1ae429b1) | Mar 18, 2022 |
| Gigabyte      | B450M S2H                   | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| Gigabyte      | H81M-S2PV                   | [5f407ad359](https://linux-hardware.org/?probe=5f407ad359) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [b8ad1b22aa](https://linux-hardware.org/?probe=b8ad1b22aa) | Mar 18, 2022 |
| Dell          | 0YNVJG A01                  | [7a52c137cf](https://linux-hardware.org/?probe=7a52c137cf) | Mar 18, 2022 |
| ASUSTek       | P8Z77-V LX                  | [4b2329edf6](https://linux-hardware.org/?probe=4b2329edf6) | Mar 18, 2022 |
| ASUSTek       | M5A78L LE                   | [d50c3e8e85](https://linux-hardware.org/?probe=d50c3e8e85) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| ASRock        | H570M Pro4                  | [b04e0c4c1c](https://linux-hardware.org/?probe=b04e0c4c1c) | Mar 18, 2022 |
| Gigabyte      | G31M-S2L                    | [b9822ea50b](https://linux-hardware.org/?probe=b9822ea50b) | Mar 18, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f3b0889850](https://linux-hardware.org/?probe=f3b0889850) | Mar 18, 2022 |
| ASUSTek       | PRIME B450M-K II            | [406c69d7cd](https://linux-hardware.org/?probe=406c69d7cd) | Mar 18, 2022 |
| ASUSTek       | PRIME Z490-A                | [2692e4dfd1](https://linux-hardware.org/?probe=2692e4dfd1) | Mar 18, 2022 |
| Gigabyte      | P31-ES3G                    | [e2219e60ea](https://linux-hardware.org/?probe=e2219e60ea) | Mar 18, 2022 |
| Gigabyte      | P31-ES3G                    | [f2011ec78e](https://linux-hardware.org/?probe=f2011ec78e) | Mar 18, 2022 |
| ASUSTek       | H81M-PLUS                   | [191c15c66b](https://linux-hardware.org/?probe=191c15c66b) | Mar 18, 2022 |
| ASUSTek       | H81M-PLUS                   | [3001c43eca](https://linux-hardware.org/?probe=3001c43eca) | Mar 18, 2022 |
| ASRock        | B560M-ITX/ac                | [58d3e7c461](https://linux-hardware.org/?probe=58d3e7c461) | Mar 18, 2022 |
| Dell          | 040DDP A01                  | [4cf633a014](https://linux-hardware.org/?probe=4cf633a014) | Mar 18, 2022 |
| Dell          | 0VD92X A00                  | [d52410b817](https://linux-hardware.org/?probe=d52410b817) | Mar 18, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [8b31578713](https://linux-hardware.org/?probe=8b31578713) | Mar 18, 2022 |
| ASUSTek       | P5E                         | [ec2b80980d](https://linux-hardware.org/?probe=ec2b80980d) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [dc3b3ab391](https://linux-hardware.org/?probe=dc3b3ab391) | Mar 18, 2022 |
| Dell          | 0RY206                      | [df958219ab](https://linux-hardware.org/?probe=df958219ab) | Mar 18, 2022 |
| ASUSTek       | P7H55-M LE                  | [a3c7a555df](https://linux-hardware.org/?probe=a3c7a555df) | Mar 18, 2022 |
| Dell          | 0RY206                      | [d46b854bd5](https://linux-hardware.org/?probe=d46b854bd5) | Mar 18, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [d2378fc2ac](https://linux-hardware.org/?probe=d2378fc2ac) | Mar 18, 2022 |
| MSI           | MS-7309                     | [60978399dd](https://linux-hardware.org/?probe=60978399dd) | Mar 18, 2022 |
| Biostar       | N68S3B                      | [736799fe08](https://linux-hardware.org/?probe=736799fe08) | Mar 18, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | [a3b5b7c37e](https://linux-hardware.org/?probe=a3b5b7c37e) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5d2c6c0279](https://linux-hardware.org/?probe=5d2c6c0279) | Mar 18, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [6f4835e78d](https://linux-hardware.org/?probe=6f4835e78d) | Mar 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [66f505c139](https://linux-hardware.org/?probe=66f505c139) | Mar 18, 2022 |
| ASRock        | Z97 Extreme6                | [bf2f07e405](https://linux-hardware.org/?probe=bf2f07e405) | Mar 18, 2022 |
| Lenovo        | H420                        | [b6aa4d1454](https://linux-hardware.org/?probe=b6aa4d1454) | Mar 18, 2022 |
| Biostar       | J3060NH                     | [90d9af88d8](https://linux-hardware.org/?probe=90d9af88d8) | Mar 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f43e92acdd](https://linux-hardware.org/?probe=f43e92acdd) | Mar 18, 2022 |
| ASRock        | Z87 Pro4                    | [7c46cc65dc](https://linux-hardware.org/?probe=7c46cc65dc) | Mar 18, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [af8d9c8c06](https://linux-hardware.org/?probe=af8d9c8c06) | Mar 18, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| ASUSTek       | Hematite                    | [e4258e3376](https://linux-hardware.org/?probe=e4258e3376) | Mar 17, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [337a1bad36](https://linux-hardware.org/?probe=337a1bad36) | Mar 17, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [554e077e77](https://linux-hardware.org/?probe=554e077e77) | Mar 17, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| HP            | 3398                        | [5f018df1dd](https://linux-hardware.org/?probe=5f018df1dd) | Mar 17, 2022 |
| HP            | 81B3                        | [1924290221](https://linux-hardware.org/?probe=1924290221) | Mar 17, 2022 |
| MSI           | H81M-P33                    | [3cfbfd5eae](https://linux-hardware.org/?probe=3cfbfd5eae) | Mar 17, 2022 |
| MSI           | H61M-E22                    | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| Unknown       | Intel X79                   | [1b92468c15](https://linux-hardware.org/?probe=1b92468c15) | Mar 17, 2022 |
| Dell          | 0Y5DDC A00                  | [ddca79ef25](https://linux-hardware.org/?probe=ddca79ef25) | Mar 17, 2022 |
| Medion        | TJ4125                      | [d8535f37cc](https://linux-hardware.org/?probe=d8535f37cc) | Mar 17, 2022 |
| MSI           | J1900I                      | [991f20b3b8](https://linux-hardware.org/?probe=991f20b3b8) | Mar 17, 2022 |
| ASRock        | G31M-VS2                    | [129721c7ce](https://linux-hardware.org/?probe=129721c7ce) | Mar 17, 2022 |
| Dell          | 0HD5W2 A00                  | [14d41935a3](https://linux-hardware.org/?probe=14d41935a3) | Mar 17, 2022 |
| ASUSTek       | Z87-K                       | [984debdd3a](https://linux-hardware.org/?probe=984debdd3a) | Mar 17, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b68926de8f](https://linux-hardware.org/?probe=b68926de8f) | Mar 17, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [d75cb4d8c6](https://linux-hardware.org/?probe=d75cb4d8c6) | Mar 17, 2022 |
| ASUSTek       | M2A-VM HDMI                 | [ea35877485](https://linux-hardware.org/?probe=ea35877485) | Mar 17, 2022 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | [0a880e2e5c](https://linux-hardware.org/?probe=0a880e2e5c) | Mar 17, 2022 |
| Acer          | Veriton S2610G              | [f386a19d48](https://linux-hardware.org/?probe=f386a19d48) | Mar 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b2ec039a2e](https://linux-hardware.org/?probe=b2ec039a2e) | Mar 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [b928348a02](https://linux-hardware.org/?probe=b928348a02) | Mar 17, 2022 |
| Dell          | 06JWJY A01                  | [55cad08f99](https://linux-hardware.org/?probe=55cad08f99) | Mar 17, 2022 |
| Biostar       | H61MHV2                     | [e35ee37a65](https://linux-hardware.org/?probe=e35ee37a65) | Mar 17, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4fa05350b7](https://linux-hardware.org/?probe=4fa05350b7) | Mar 17, 2022 |
| Lenovo        | 1046 NO DPK                 | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | G31M-S2C                    | [a56fb721dd](https://linux-hardware.org/?probe=a56fb721dd) | Mar 17, 2022 |
| ASRock        | B550 Steel Legend           | [c6b6cc1f1d](https://linux-hardware.org/?probe=c6b6cc1f1d) | Mar 17, 2022 |
| Packard Be... | IMEDIA S2885                | [1cf614db1e](https://linux-hardware.org/?probe=1cf614db1e) | Mar 17, 2022 |
| Acer          | Veriton X2640G V:1.0        | [30bcf38da7](https://linux-hardware.org/?probe=30bcf38da7) | Mar 17, 2022 |
| ASUSTek       | Rampage IV FORMULA          | [433ed3c3d7](https://linux-hardware.org/?probe=433ed3c3d7) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M LX3                | [24b9866304](https://linux-hardware.org/?probe=24b9866304) | Mar 17, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [a40f7ff51b](https://linux-hardware.org/?probe=a40f7ff51b) | Mar 17, 2022 |
| Gigabyte      | GA-78LMT-S2 R2              | [715a4f0c38](https://linux-hardware.org/?probe=715a4f0c38) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [0af153934b](https://linux-hardware.org/?probe=0af153934b) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [2071129adb](https://linux-hardware.org/?probe=2071129adb) | Mar 17, 2022 |
| ASRock        | A300M-STX                   | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| MSI           | H61I-E35 V2/W8              | [172c4ac7f6](https://linux-hardware.org/?probe=172c4ac7f6) | Mar 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [9d6f42b14f](https://linux-hardware.org/?probe=9d6f42b14f) | Mar 17, 2022 |
| ASUSTek       | PRIME B460-PLUS             | [c0db7c9966](https://linux-hardware.org/?probe=c0db7c9966) | Mar 17, 2022 |
| Acer          | Veriton N4660G              | [d388b291e1](https://linux-hardware.org/?probe=d388b291e1) | Mar 17, 2022 |
| HP            | 1408h                       | [d80307d774](https://linux-hardware.org/?probe=d80307d774) | Mar 17, 2022 |
| Acer          | EM61SM/EM61PM               | [a33e5dfb8e](https://linux-hardware.org/?probe=a33e5dfb8e) | Mar 17, 2022 |
| ASUSTek       | P5K/EPU                     | [38de085421](https://linux-hardware.org/?probe=38de085421) | Mar 17, 2022 |
| Intel         | DH67BL AAG10189-211         | [90b9116ab3](https://linux-hardware.org/?probe=90b9116ab3) | Mar 17, 2022 |
| Acer          | EM61SM/EM61PM               | [6f3290f91a](https://linux-hardware.org/?probe=6f3290f91a) | Mar 17, 2022 |
| Gigabyte      | A520M H                     | [46b8c80485](https://linux-hardware.org/?probe=46b8c80485) | Mar 17, 2022 |
| HP            | 18E4                        | [d7f09dbc7f](https://linux-hardware.org/?probe=d7f09dbc7f) | Mar 17, 2022 |
| Gigabyte      | MZBSWMP-00                  | [7067f88bee](https://linux-hardware.org/?probe=7067f88bee) | Mar 17, 2022 |
| ASRock        | J3455-ITX                   | [9b36863bd5](https://linux-hardware.org/?probe=9b36863bd5) | Mar 17, 2022 |
| ASUSTek       | PRIME H510M-A               | [d71d1c794b](https://linux-hardware.org/?probe=d71d1c794b) | Mar 17, 2022 |
| Gigabyte      | B360M H                     | [3190c29544](https://linux-hardware.org/?probe=3190c29544) | Mar 17, 2022 |
| ASUSTek       | H170M-E D3                  | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Dell          | 0V8F20 A01                  | [4ebf0529e9](https://linux-hardware.org/?probe=4ebf0529e9) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP            | 876C SMVB                   | [70e0a9f8cd](https://linux-hardware.org/?probe=70e0a9f8cd) | Mar 17, 2022 |
| ASUSTek       | PRIME B460M-A               | [bb8e459621](https://linux-hardware.org/?probe=bb8e459621) | Mar 17, 2022 |
| Unknown       | Unknown                     | [fd9e66788c](https://linux-hardware.org/?probe=fd9e66788c) | Mar 17, 2022 |
| Alienware     | 0PGRP5 A02                  | [8a28919b48](https://linux-hardware.org/?probe=8a28919b48) | Mar 17, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 8796     | 13.72%  |
| Ubuntu 18.04      | 5290     | 8.25%   |
| OpenMandriva 4.2  | 2157     | 3.37%   |
| ROSA R10          | 2143     | 3.34%   |
| ROSA R11          | 2075     | 3.24%   |
| ROSA R8           | 1904     | 2.97%   |
| ROSA R6           | 1785     | 2.78%   |
| ROSA R7           | 1702     | 2.66%   |
| ROSA R8.1         | 1461     | 2.28%   |
| ROSA R9           | 1276     | 1.99%   |
| BlackPanther 18.1 | 1154     | 1.8%    |
| ROSA R11.1        | 1077     | 1.68%   |
| Debian 11         | 1022     | 1.59%   |
| KDE neon 20.04    | 914      | 1.43%   |
| OpenMandriva 4.3  | 898      | 1.4%    |
| Arch              | 880      | 1.37%   |
| Linux Mint 20.1   | 874      | 1.36%   |
| Pop!_OS 20.04     | 847      | 1.32%   |
| Linux Mint 20.2   | 837      | 1.31%   |
| Linux Mint 19.3   | 823      | 1.28%   |
| Manjaro           | 780      | 1.22%   |
| Arch Rolling      | 779      | 1.22%   |
| Linux Mint 20     | 758      | 1.18%   |
| Ubuntu 19.10      | 751      | 1.17%   |
| Ubuntu 19.04      | 746      | 1.16%   |
| Ubuntu 20.10      | 738      | 1.15%   |
| Xubuntu 20.04     | 725      | 1.13%   |
| Pop!_OS 21.04     | 715      | 1.12%   |
| Debian 10         | 693      | 1.08%   |
| Pop!_OS 20.10     | 669      | 1.04%   |
| Ubuntu 21.10      | 639      | 1%      |
| Ubuntu 21.04      | 605      | 0.94%   |
| Fedora 33         | 560      | 0.87%   |
| Kubuntu 20.04     | 532      | 0.83%   |
| Zorin 15          | 520      | 0.81%   |
| Fedora 32         | 517      | 0.81%   |
| Fedora 34         | 509      | 0.79%   |
| Zorin 16          | 499      | 0.78%   |
| Ubuntu 16.04      | 493      | 0.77%   |
| Linux Mint 20.3   | 446      | 0.7%    |
| Fedora 35         | 438      | 0.68%   |
| ArcoLinux Rolling | 432      | 0.67%   |
| Linux Mint 19.1   | 394      | 0.61%   |
| Xubuntu 18.04     | 378      | 0.59%   |
| Pop!_OS 21.10     | 370      | 0.58%   |
| Ubuntu 18.10      | 352      | 0.55%   |
| Fedora 31         | 345      | 0.54%   |
| ROSA 12.2         | 338      | 0.53%   |
| Linux Mint 19.2   | 317      | 0.49%   |
| Gentoo 2.7        | 263      | 0.41%   |
| OpenMandriva 4.50 | 253      | 0.39%   |
| ROSA R5           | 246      | 0.38%   |
| Ubuntu MATE 20.04 | 228      | 0.36%   |
| Debian Testing    | 189      | 0.29%   |
| Gentoo 2.6        | 170      | 0.27%   |
| KDE neon 18.04    | 150      | 0.23%   |
| Linux Mint 19     | 149      | 0.23%   |
| ROSA 12.1         | 148      | 0.23%   |
| LMDE 4            | 146      | 0.23%   |
| CentOS 8          | 146      | 0.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 17820    | 30.06%  |
| ROSA          | 11952    | 20.16%  |
| Linux Mint    | 4445     | 7.5%    |
| OpenMandriva  | 3308     | 5.58%   |
| Pop!_OS       | 2483     | 4.19%   |
| Fedora        | 2299     | 3.88%   |
| Debian        | 2110     | 3.56%   |
| Manjaro       | 1885     | 3.18%   |
| Arch          | 1641     | 2.77%   |
| Xubuntu       | 1304     | 2.2%    |
| BlackPanther  | 1211     | 2.04%   |
| Zorin         | 1091     | 1.84%   |
| KDE neon      | 1054     | 1.78%   |
| Kubuntu       | 916      | 1.55%   |
| Endless       | 605      | 1.02%   |
| openSUSE      | 510      | 0.86%   |
| ArcoLinux     | 479      | 0.81%   |
| Gentoo        | 460      | 0.78%   |
| Ubuntu MATE   | 405      | 0.68%   |
| CentOS        | 283      | 0.48%   |
| Lubuntu       | 276      | 0.47%   |
| Elementary    | 274      | 0.46%   |
| Clear Linux   | 241      | 0.41%   |
| LMDE          | 165      | 0.28%   |
| EndeavourOS   | 157      | 0.26%   |
| Kali          | 147      | 0.25%   |
| ALT Linux     | 137      | 0.23%   |
| Ubuntu Budgie | 133      | 0.22%   |
| RED           | 121      | 0.2%    |
| Garuda Linux  | 93       | 0.16%   |
| MX            | 92       | 0.16%   |
| Peppermint    | 90       | 0.15%   |
| LinuxFX       | 66       | 0.11%   |
| Parrot        | 62       | 0.1%    |
| RHEL          | 61       | 0.1%    |
| Reborn OS     | 58       | 0.1%    |
| Mageia        | 54       | 0.09%   |
| Solus         | 53       | 0.09%   |
| Slackware     | 50       | 0.08%   |
| Deepin        | 50       | 0.08%   |
| Artix         | 43       | 0.07%   |
| Devuan        | 38       | 0.06%   |
| RELS          | 35       | 0.06%   |
| Void Linux    | 33       | 0.06%   |
| NixOS         | 28       | 0.05%   |
| ClearOS       | 24       | 0.04%   |
| Xero          | 21       | 0.04%   |
| Red OS        | 21       | 0.04%   |
| antergos      | 20       | 0.03%   |
| Makulu        | 19       | 0.03%   |
| Rocky Linux   | 18       | 0.03%   |
| Alpine        | 18       | 0.03%   |
| Sparky        | 16       | 0.03%   |
| QTS           | 15       | 0.03%   |
| Chrome OS     | 14       | 0.02%   |
| GNOME OS      | 11       | 0.02%   |
| Linux Lite    | 10       | 0.02%   |
| BunsenLabs    | 10       | 0.02%   |
| Siduction     | 9        | 0.02%   |
| Oracle Linux  | 9        | 0.02%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002           | 2093     | 2.9%    |
| 5.4.0-42-generic                   | 1396     | 1.94%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 1052     | 1.46%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 956      | 1.33%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 948      | 1.32%   |
| 4.18.16-desktop-1bP                | 916      | 1.27%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 909      | 1.26%   |
| 5.16.7-desktop-1omv4003            | 888      | 1.23%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 882      | 1.22%   |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 754      | 1.05%   |
| 5.4.0-58-generic                   | 698      | 0.97%   |
| 5.4.0-52-generic                   | 646      | 0.9%    |
| 5.4.0-48-generic                   | 633      | 0.88%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 512      | 0.71%   |
| 5.4.0-26-generic                   | 501      | 0.69%   |
| 5.4.0-40-generic                   | 460      | 0.64%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 456      | 0.63%   |
| 3.14.44-nrj-desktop-2rosa-i586     | 436      | 0.6%    |
| 5.3.0-40-generic                   | 435      | 0.6%    |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 424      | 0.59%   |
| 5.4.0-29-generic                   | 413      | 0.57%   |
| 5.4.0-54-generic                   | 412      | 0.57%   |
| 5.4.0-37-generic                   | 407      | 0.56%   |
| 5.4.0-65-generic                   | 385      | 0.53%   |
| 5.3.0-28-generic                   | 373      | 0.52%   |
| 5.3.0-46-generic                   | 360      | 0.5%    |
| 5.11.0-27-generic                  | 353      | 0.49%   |
| 4.1.38-nrj-desktop-2rosa-x86_64    | 352      | 0.49%   |
| 5.4.0-47-generic                   | 350      | 0.49%   |
| 5.11.0-37-generic                  | 344      | 0.48%   |
| 5.8.0-43-generic                   | 343      | 0.48%   |
| 5.11.0-7620-generic                | 339      | 0.47%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 333      | 0.46%   |
| 5.11.0-38-generic                  | 326      | 0.45%   |
| 5.8.0-7630-generic                 | 318      | 0.44%   |
| 5.0.0-37-generic                   | 315      | 0.44%   |
| 5.11.0-40-generic                  | 313      | 0.43%   |
| 5.4.0-66-generic                   | 309      | 0.43%   |
| 4.1.25-nrj-desktop-1rosa-i586      | 307      | 0.43%   |
| 5.8.0-50-generic                   | 304      | 0.42%   |
| 5.8.0-44-generic                   | 304      | 0.42%   |
| 5.10.0-7-amd64                     | 296      | 0.41%   |
| 5.6.14-desktop-2bP                 | 295      | 0.41%   |
| 5.4.0-33-generic                   | 295      | 0.41%   |
| 5.4.0-91-generic                   | 294      | 0.41%   |
| 5.4.0-72-generic                   | 293      | 0.41%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 292      | 0.41%   |
| 5.4.0-7634-generic                 | 285      | 0.4%    |
| 4.9.76-nrj-desktop-1rosa-x86_64    | 278      | 0.39%   |
| 5.13.0-39-generic                  | 276      | 0.38%   |
| 5.4.0-74-generic                   | 271      | 0.38%   |
| 5.11.0-41-generic                  | 269      | 0.37%   |
| 5.4.0-56-generic                   | 266      | 0.37%   |
| 5.13.0-30-generic                  | 266      | 0.37%   |
| 5.4.0-31-generic                   | 261      | 0.36%   |
| 5.8.0-59-generic                   | 260      | 0.36%   |
| 5.13.0-28-generic                  | 259      | 0.36%   |
| 4.1.16-nrj-desktop-1rosa-x86_64    | 259      | 0.36%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 258      | 0.36%   |
| 5.4.0-70-generic                   | 257      | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 11799    | 17.57%  |
| 4.15.0  | 6401     | 9.53%   |
| 5.8.0   | 3849     | 5.73%   |
| 5.11.0  | 3522     | 5.24%   |
| 5.3.0   | 2768     | 4.12%   |
| 5.13.0  | 2213     | 3.3%    |
| 5.10.14 | 2113     | 3.15%   |
| 5.0.0   | 1971     | 2.94%   |
| 4.18.0  | 1496     | 2.23%   |
| 3.14.44 | 1386     | 2.06%   |
| 4.9.60  | 1304     | 1.94%   |
| 4.9.20  | 1251     | 1.86%   |
| 4.1.25  | 1182     | 1.76%   |
| 5.10.0  | 1173     | 1.75%   |
| 4.1.15  | 973      | 1.45%   |
| 4.18.16 | 939      | 1.4%    |
| 5.16.7  | 907      | 1.35%   |
| 4.19.0  | 739      | 1.1%    |
| 4.1.34  | 704      | 1.05%   |
| 4.1.38  | 587      | 0.87%   |
| 4.9.9   | 507      | 0.76%   |
| 4.9.124 | 503      | 0.75%   |
| 5.10.74 | 463      | 0.69%   |
| 4.9.155 | 363      | 0.54%   |
| 4.9.76  | 340      | 0.51%   |
| 5.6.14  | 335      | 0.5%    |
| 4.1.16  | 335      | 0.5%    |
| 4.9.41  | 320      | 0.48%   |
| 5.4.32  | 268      | 0.4%    |
| 4.4.0   | 245      | 0.36%   |
| 5.12.4  | 233      | 0.35%   |
| 5.4.83  | 213      | 0.32%   |
| 4.1.19  | 204      | 0.3%    |
| 4.1.22  | 203      | 0.3%    |
| 3.14.53 | 203      | 0.3%    |
| 5.9.16  | 198      | 0.29%   |
| 4.1.33  | 190      | 0.28%   |
| 3.10.0  | 182      | 0.27%   |
| 4.9.95  | 176      | 0.26%   |
| 5.16.11 | 172      | 0.26%   |
| 5.15.0  | 158      | 0.24%   |
| 4.1.13  | 158      | 0.24%   |
| 5.3.18  | 146      | 0.22%   |
| 4.9.111 | 143      | 0.21%   |
| 5.6.0   | 136      | 0.2%    |
| 5.7.0   | 135      | 0.2%    |
| 5.15.15 | 126      | 0.19%   |
| 4.9.0   | 126      | 0.19%   |
| 5.9.0   | 123      | 0.18%   |
| 5.15.5  | 123      | 0.18%   |
| 5.11.12 | 122      | 0.18%   |
| 5.14.0  | 121      | 0.18%   |
| 5.13.19 | 117      | 0.17%   |
| 5.9.11  | 112      | 0.17%   |
| 5.10.71 | 106      | 0.16%   |
| 4.9.87  | 103      | 0.15%   |
| 5.15.12 | 102      | 0.15%   |
| 4.13.0  | 101      | 0.15%   |
| 5.9.1   | 98       | 0.15%   |
| 5.8.18  | 98       | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 13203    | 20.43%  |
| 4.15    | 6435     | 9.96%   |
| 5.10    | 5022     | 7.77%   |
| 5.8     | 4832     | 7.48%   |
| 4.9     | 4492     | 6.95%   |
| 5.11    | 4273     | 6.61%   |
| 4.1     | 3923     | 6.07%   |
| 5.3     | 3149     | 4.87%   |
| 5.13    | 2799     | 4.33%   |
| 4.18    | 2481     | 3.84%   |
| 5.0     | 2103     | 3.25%   |
| 3.14    | 1775     | 2.75%   |
| 5.16    | 1646     | 2.55%   |
| 5.15    | 1322     | 2.05%   |
| 5.6     | 1031     | 1.6%    |
| 4.19    | 929      | 1.44%   |
| 5.9     | 901      | 1.39%   |
| 5.12    | 786      | 1.22%   |
| 5.7     | 671      | 1.04%   |
| 5.14    | 664      | 1.03%   |
| 5.5     | 364      | 0.56%   |
| 4.4     | 330      | 0.51%   |
| 3.10    | 216      | 0.33%   |
| 5.2     | 162      | 0.25%   |
| 5.17    | 141      | 0.22%   |
| 5.1     | 133      | 0.21%   |
| 4.13    | 125      | 0.19%   |
| 4.14    | 94       | 0.15%   |
| 4.12    | 89       | 0.14%   |
| 4.8     | 66       | 0.1%    |
| 4.10    | 63       | 0.1%    |
| 4.20    | 61       | 0.09%   |
| 4.16    | 49       | 0.08%   |
| 4.7     | 42       | 0.07%   |
| 4.17    | 42       | 0.07%   |
| 4.6     | 22       | 0.03%   |
| 2.6     | 22       | 0.03%   |
| 3.18    | 21       | 0.03%   |
| 4.3     | 18       | 0.03%   |
| 4.2     | 16       | 0.02%   |
| 4.11    | 16       | 0.02%   |
| 4.5     | 15       | 0.02%   |
| 3.16    | 13       | 0.02%   |
| 3.13    | 13       | 0.02%   |
| 4.0     | 11       | 0.02%   |
| 3.19    | 8        | 0.01%   |
| 3.0     | 6        | 0.01%   |
| Unknown | 5        | 0.01%   |
| 3.2     | 3        | 0.005%  |
| 3.17    | 3        | 0.005%  |
| 6.0     | 1        | 0.002%  |
| 5       | 1        | 0.002%  |
| 3.9     | 1        | 0.002%  |
| 3.8     | 1        | 0.002%  |
| 3.15    | 1        | 0.002%  |
| 2.6.35  | 1        | 0.002%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 53682    | 92.84%  |
| i686     | 4110     | 7.11%   |
| armv7l   | 9        | 0.02%   |
| ppc64    | 3        | 0.01%   |
| ppc      | 3        | 0.01%   |
| e2k      | 3        | 0.01%   |
| ppc64le  | 2        | 0.003%  |
| mips64   | 2        | 0.003%  |
| unknow   | 1        | 0.002%  |
| i586     | 1        | 0.002%  |
| armv6l   | 1        | 0.002%  |
| armv5tel | 1        | 0.002%  |
| aarch64  | 1        | 0.002%  |
| Unknown  | 1        | 0.002%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 19619    | 32.35%  |
| KDE5                     | 10199    | 16.82%  |
| KDE4                     | 9242     | 15.24%  |
| Unknown                  | 8182     | 13.49%  |
| XFCE                     | 3421     | 5.64%   |
| X-Cinnamon               | 3088     | 5.09%   |
| KDE                      | 1882     | 3.1%    |
| MATE                     | 1498     | 2.47%   |
| Cinnamon                 | 746      | 1.23%   |
| LXQt                     | 570      | 0.94%   |
| Unity                    | 398      | 0.66%   |
| LXDE                     | 308      | 0.51%   |
| Pantheon                 | 256      | 0.42%   |
| Budgie                   | 239      | 0.39%   |
| i3                       | 202      | 0.33%   |
| Deepin                   | 158      | 0.26%   |
| GNOME Flashback          | 138      | 0.23%   |
| GNUstep                  | 95       | 0.16%   |
| GNOME Classic            | 73       | 0.12%   |
| awesome                  | 58       | 0.1%    |
| openbox                  | 44       | 0.07%   |
| sway                     | 25       | 0.04%   |
| bspwm                    | 25       | 0.04%   |
| xmonad                   | 22       | 0.04%   |
| qtile                    | 21       | 0.03%   |
| trinity                  | 18       | 0.03%   |
| lightdm-xsession         | 18       | 0.03%   |
| dwm                      | 17       | 0.03%   |
| Enlightenment            | 12       | 0.02%   |
| LeftWM                   | 10       | 0.02%   |
| ICEWM                    | 9        | 0.01%   |
| fluxbox                  | 5        | 0.01%   |
| herbstluftwm             | 4        | 0.01%   |
| FVWM                     | 4        | 0.01%   |
| Yaru:ubuntu:GNOME        | 3        | 0.005%  |
| i3-with-shmlog           | 3        | 0.005%  |
| Cutefish                 | 3        | 0.005%  |
| UKUI                     | 2        | 0.003%  |
| ubuntustudio             | 2        | 0.003%  |
| pearl:GNOME              | 2        | 0.003%  |
| Lubuntu                  | 2        | 0.003%  |
| jwm                      | 2        | 0.003%  |
| dusk                     | 2        | 0.003%  |
| default                  | 2        | 0.003%  |
| Core                     | 2        | 0.003%  |
| /usr/bin/openbox-session | 2        | 0.003%  |
| xubuntu                  | 1        | 0.002%  |
| XSession                 | 1        | 0.002%  |
| Xpra                     | 1        | 0.002%  |
| xinitrc                  | 1        | 0.002%  |
| sway:Unity               | 1        | 0.002%  |
| Peux Gnome               | 1        | 0.002%  |
| Peppermint               | 1        | 0.002%  |
| NsCDE                    | 1        | 0.002%  |
| Lumina                   | 1        | 0.002%  |
| GNOME-Flashback          | 1        | 0.002%  |
| fly                      | 1        | 0.002%  |
| 03WindowMaker            | 1        | 0.002%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 49985    | 85.19%  |
| Unknown     | 4106     | 7%      |
| Wayland     | 3536     | 6.03%   |
| Tty         | 1032     | 1.76%   |
| Web         | 11       | 0.02%   |
| Unspecified | 4        | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28517    | 47.59%  |
| SDDM    | 10049    | 16.77%  |
| KDM     | 9329     | 15.57%  |
| GDM     | 4748     | 7.92%   |
| LightDM | 2716     | 4.53%   |
| TDM     | 2280     | 3.81%   |
| GDM3    | 2004     | 3.34%   |
| XDM     | 99       | 0.17%   |
| SLiM    | 65       | 0.11%   |
| MDM     | 44       | 0.07%   |
| LXDM    | 34       | 0.06%   |
| Ly      | 20       | 0.03%   |
| NODM    | 8        | 0.01%   |
| GREETD  | 2        | 0.003%  |
| LDM     | 1        | 0.002%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18532    | 31.31%  |
| en_US   | 15774    | 26.65%  |
| de_DE   | 3723     | 6.29%   |
| ru_RU   | 3543     | 5.99%   |
| pt_BR   | 2294     | 3.88%   |
| en_GB   | 2151     | 3.63%   |
| fr_FR   | 1818     | 3.07%   |
| it_IT   | 1116     | 1.89%   |
| es_ES   | 974      | 1.65%   |
| en_CA   | 964      | 1.63%   |
| pl_PL   | 776      | 1.31%   |
| en_AU   | 736      | 1.24%   |
| C       | 714      | 1.21%   |
| en_IN   | 444      | 0.75%   |
| nl_NL   | 382      | 0.65%   |
| es_AR   | 345      | 0.58%   |
| hu_HU   | 279      | 0.47%   |
| es_MX   | 251      | 0.42%   |
| cs_CZ   | 242      | 0.41%   |
| de_AT   | 205      | 0.35%   |
| ja_JP   | 193      | 0.33%   |
| ru_UA   | 190      | 0.32%   |
| en_ZA   | 183      | 0.31%   |
| sv_SE   | 181      | 0.31%   |
| pt_PT   | 174      | 0.29%   |
| fi_FI   | 134      | 0.23%   |
| de_CH   | 132      | 0.22%   |
| fr_CA   | 129      | 0.22%   |
| el_GR   | 126      | 0.21%   |
| zh_CN   | 120      | 0.2%    |
| en_NZ   | 119      | 0.2%    |
| tr_TR   | 115      | 0.19%   |
| uk_UA   | 100      | 0.17%   |
| en_IE   | 97       | 0.16%   |
| nl_BE   | 95       | 0.16%   |
| es_CO   | 93       | 0.16%   |
| ro_RO   | 86       | 0.15%   |
| fr_BE   | 86       | 0.15%   |
| es_CL   | 80       | 0.14%   |
| sk_SK   | 79       | 0.13%   |
| zh_TW   | 74       | 0.13%   |
| en_IL   | 73       | 0.12%   |
| da_DK   | 66       | 0.11%   |
| bg_BG   | 57       | 0.1%    |
| nb_NO   | 55       | 0.09%   |
| es_VE   | 53       | 0.09%   |
| en_PH   | 53       | 0.09%   |
| es_PE   | 52       | 0.09%   |
| ko_KR   | 51       | 0.09%   |
| POSIX   | 47       | 0.08%   |
| fr_CH   | 47       | 0.08%   |
| ca_ES   | 42       | 0.07%   |
| en_HK   | 40       | 0.07%   |
| en_DK   | 37       | 0.06%   |
| en_SG   | 36       | 0.06%   |
| sl_SI   | 35       | 0.06%   |
| hr_HR   | 34       | 0.06%   |
| C.UTF8  | 30       | 0.05%   |
| es_UY   | 28       | 0.05%   |
| es_EC   | 28       | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39732    | 67.65%  |
| EFI  | 19001    | 32.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Ext4                | 39868    | 67.11%  |
| Unknown             | 10083    | 16.97%  |
| Overlay             | 4939     | 8.31%   |
| Btrfs               | 2723     | 4.58%   |
| Xfs                 | 850      | 1.43%   |
| Zfs                 | 363      | 0.61%   |
| Ext2                | 190      | 0.32%   |
| Ext3                | 183      | 0.31%   |
| F2fs                | 70       | 0.12%   |
| Tmpfs               | 54       | 0.09%   |
| Reiserfs            | 19       | 0.03%   |
| Aufs                | 18       | 0.03%   |
| Jfs                 | 14       | 0.02%   |
| Rootfs              | 7        | 0.01%   |
| SAMSUNG             | 6        | 0.01%   |
| XXXXXXX             | 3        | 0.01%   |
| XXXXX               | 2        | 0.003%  |
| XXXX                | 2        | 0.003%  |
| XXX                 | 2        | 0.003%  |
| ExX4                | 2        | 0.003%  |
| XXXfs               | 1        | 0.002%  |
| XXX4                | 1        | 0.002%  |
| SquXshfs            | 1        | 0.002%  |
| Fuse.sshfs          | 1        | 0.002%  |
| Fuse.fuse-overlayfs | 1        | 0.002%  |
| Exfat               | 1        | 0.002%  |
| 2G                  | 1        | 0.002%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31523    | 53.12%  |
| MBR     | 14327    | 24.14%  |
| GPT     | 13491    | 22.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48897    | 82.86%  |
| Yes       | 10118    | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39924    | 67.47%  |
| Yes       | 19248    | 32.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16169    | 28.15%  |
| Gigabyte Technology | 10738    | 18.69%  |
| MSI                 | 6378     | 11.1%   |
| ASRock              | 5765     | 10.04%  |
| Dell                | 4000     | 6.96%   |
| Hewlett-Packard     | 3339     | 5.81%   |
| Intel               | 1627     | 2.83%   |
| Lenovo              | 1540     | 2.68%   |
| Acer                | 954      | 1.66%   |
| Unknown             | 711      | 1.24%   |
| ECS                 | 646      | 1.12%   |
| Foxconn             | 633      | 1.1%    |
| Pegatron            | 604      | 1.05%   |
| Biostar             | 602      | 1.05%   |
| Fujitsu             | 470      | 0.82%   |
| Medion              | 279      | 0.49%   |
| Fujitsu Siemens     | 181      | 0.32%   |
| Supermicro          | 172      | 0.3%    |
| Positivo            | 147      | 0.26%   |
| Apple               | 137      | 0.24%   |
| Packard Bell        | 128      | 0.22%   |
| Huanan              | 118      | 0.21%   |
| Shuttle             | 111      | 0.19%   |
| Alienware           | 101      | 0.18%   |
| Gateway             | 91       | 0.16%   |
| PCWare              | 88       | 0.15%   |
| eMachines           | 87       | 0.15%   |
| ABIT                | 60       | 0.1%    |
| EVGA                | 54       | 0.09%   |
| AMI                 | 50       | 0.09%   |
| OEM                 | 47       | 0.08%   |
| IBM                 | 44       | 0.08%   |
| Semp Toshiba        | 40       | 0.07%   |
| ASRockRack          | 40       | 0.07%   |
| WinFast             | 39       | 0.07%   |
| AMD                 | 37       | 0.06%   |
| EPoX Computer       | 34       | 0.06%   |
| ZOTAC               | 33       | 0.06%   |
| Itautec             | 33       | 0.06%   |
| System76            | 32       | 0.06%   |
| Nvidia              | 30       | 0.05%   |
| BESSTAR Tech        | 30       | 0.05%   |
| NEC Computers       | 27       | 0.05%   |
| Google              | 27       | 0.05%   |
| AZW                 | 26       | 0.05%   |
| AAEON               | 26       | 0.05%   |
| TYAN Computer       | 24       | 0.04%   |
| PCChips             | 24       | 0.04%   |
| Megaware            | 24       | 0.04%   |
| AOpen               | 24       | 0.04%   |
| Wistron             | 22       | 0.04%   |
| Inventec            | 20       | 0.03%   |
| HARDKERNEL          | 19       | 0.03%   |
| DEPO Computers      | 16       | 0.03%   |
| Colorful Technology | 16       | 0.03%   |
| SiS Technology      | 14       | 0.02%   |
| Sapphire            | 14       | 0.02%   |
| Minix               | 14       | 0.02%   |
| VIA Technologies    | 13       | 0.02%   |
| Quanta              | 13       | 0.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 1550     | 2.7%    |
| Unknown                      | 764      | 1.33%   |
| Dell OptiPlex 7010           | 263      | 0.46%   |
| Gigabyte B450M DS3H          | 239      | 0.42%   |
| MSI MS-7C37                  | 223      | 0.39%   |
| ASUS TUF GAMING X570-PLUS    | 217      | 0.38%   |
| MSI MS-7C02                  | 214      | 0.37%   |
| Gigabyte 970A-DS3P           | 214      | 0.37%   |
| MSI MS-7817                  | 211      | 0.37%   |
| ASUS PRIME A320M-K           | 202      | 0.35%   |
| ASUS M5A78L-M/USB3           | 188      | 0.33%   |
| Dell OptiPlex 9020           | 184      | 0.32%   |
| MSI MS-7693                  | 172      | 0.3%    |
| Dell OptiPlex 780            | 172      | 0.3%    |
| ASUS M5A97 R2.0              | 170      | 0.3%    |
| MSI MS-7721                  | 163      | 0.28%   |
| Dell OptiPlex 790            | 163      | 0.28%   |
| MSI MS-7B86                  | 158      | 0.28%   |
| ASUS PRIME B450M-A           | 144      | 0.25%   |
| ASRock B450M Pro4            | 143      | 0.25%   |
| Gigabyte G31M-ES2L           | 139      | 0.24%   |
| MSI MS-7A38                  | 136      | 0.24%   |
| ASUS ROG STRIX B450-F GAMING | 134      | 0.23%   |
| Dell OptiPlex 755            | 133      | 0.23%   |
| MSI MS-7B79                  | 130      | 0.23%   |
| ASRock N68C-S UCC            | 128      | 0.22%   |
| Dell OptiPlex 3020           | 125      | 0.22%   |
| Gigabyte A320M-S2H           | 124      | 0.22%   |
| HP Compaq Elite 8300 SFF     | 119      | 0.21%   |
| ASUS M5A78L-M LX3            | 119      | 0.21%   |
| Gigabyte H61M-S1             | 118      | 0.21%   |
| ASUS M5A97 LE R2.0           | 118      | 0.21%   |
| ASUS PRIME B350-PLUS         | 113      | 0.2%    |
| MSI MS-7A34                  | 110      | 0.19%   |
| MSI MS-7592                  | 110      | 0.19%   |
| ASUS SABERTOOTH 990FX R2.0   | 110      | 0.19%   |
| ASUS P8Z77-V LX              | 108      | 0.19%   |
| Dell OptiPlex 3010           | 107      | 0.19%   |
| ASRock G31M-S                | 107      | 0.19%   |
| Dell OptiPlex 390            | 105      | 0.18%   |
| HP EliteDesk 800 G1 SFF      | 103      | 0.18%   |
| MSI MS-7B89                  | 102      | 0.18%   |
| Dell OptiPlex 990            | 102      | 0.18%   |
| ASUS PRIME X370-PRO          | 102      | 0.18%   |
| Dell OptiPlex 760            | 101      | 0.18%   |
| ASUS PRIME X470-PRO          | 101      | 0.18%   |
| ASUS M5A78L-M PLUS/USB3      | 101      | 0.18%   |
| Gigabyte GA-78LMT-USB3 6.0   | 100      | 0.17%   |
| ASUS P8H61-M LX3 R2.0        | 98       | 0.17%   |
| Gigabyte X570 AORUS ELITE    | 97       | 0.17%   |
| Gigabyte B450 AORUS M        | 95       | 0.17%   |
| Gigabyte B75M-D3H            | 94       | 0.16%   |
| ASUS P5K                     | 90       | 0.16%   |
| Dell OptiPlex 745            | 88       | 0.15%   |
| ASUS ROG STRIX B550-F GAMING | 88       | 0.15%   |
| MSI MS-7788                  | 87       | 0.15%   |
| HP Compaq 8200 Elite SFF PC  | 86       | 0.15%   |
| Gigabyte H61M-S2PV           | 85       | 0.15%   |
| ASUS P5G41T-M LX             | 85       | 0.15%   |
| Gigabyte GA-78LMT-USB3       | 84       | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 2333     | 4.06%   |
| ASUS PRIME             | 2105     | 3.66%   |
| ASUS All               | 1550     | 2.7%    |
| HP Compaq              | 1374     | 2.39%   |
| ASUS ROG               | 1199     | 2.09%   |
| Lenovo ThinkCentre     | 948      | 1.65%   |
| Unknown                | 764      | 1.33%   |
| ASUS TUF               | 746      | 1.3%    |
| Acer Aspire            | 620      | 1.08%   |
| ASUS M5A78L-M          | 591      | 1.03%   |
| Dell Precision         | 553      | 0.96%   |
| Dell Inspiron          | 436      | 0.76%   |
| Gigabyte X570          | 422      | 0.73%   |
| ASUS P8H61-M           | 422      | 0.73%   |
| ASUS M5A97             | 401      | 0.7%    |
| Gigabyte B450M         | 382      | 0.66%   |
| Gigabyte B450          | 336      | 0.58%   |
| ASUS P8Z77-V           | 336      | 0.58%   |
| HP EliteDesk           | 335      | 0.58%   |
| Fujitsu ESPRIMO        | 313      | 0.54%   |
| ASUS P5KPL-AM          | 270      | 0.47%   |
| HP ProDesk             | 264      | 0.46%   |
| ASUS SABERTOOTH        | 255      | 0.44%   |
| ASRock B450M           | 251      | 0.44%   |
| ASUS P5G41T-M          | 243      | 0.42%   |
| Gigabyte GA-78LMT-USB3 | 232      | 0.4%    |
| ASUS P5K               | 227      | 0.4%    |
| Gigabyte 970A-DS3P     | 225      | 0.39%   |
| MSI MS-7C37            | 223      | 0.39%   |
| MSI MS-7C02            | 214      | 0.37%   |
| MSI MS-7817            | 211      | 0.37%   |
| Dell Vostro            | 211      | 0.37%   |
| Acer Veriton           | 205      | 0.36%   |
| Dell XPS               | 198      | 0.34%   |
| Gigabyte Z390          | 192      | 0.33%   |
| ASUS P5Q               | 186      | 0.32%   |
| ASRock X570            | 178      | 0.31%   |
| ASRock B450            | 174      | 0.3%    |
| MSI MS-7693            | 172      | 0.3%    |
| Lenovo IdeaCentre      | 172      | 0.3%    |
| Gigabyte A320M-S2H     | 169      | 0.29%   |
| MSI MS-7721            | 163      | 0.28%   |
| ASRock 970             | 163      | 0.28%   |
| MSI MS-7B86            | 158      | 0.28%   |
| ASUS Maximus           | 157      | 0.27%   |
| HP Pavilion            | 152      | 0.26%   |
| Gigabyte G31M-ES2L     | 139      | 0.24%   |
| MSI MS-7A38            | 136      | 0.24%   |
| ASUS P8Z68-V           | 135      | 0.23%   |
| ASRock N68C-S          | 134      | 0.23%   |
| Lenovo ThinkStation    | 132      | 0.23%   |
| MSI MS-7B79            | 130      | 0.23%   |
| ASUS P8P67             | 126      | 0.22%   |
| ASUS P8B75-M           | 124      | 0.22%   |
| Gigabyte B550          | 122      | 0.21%   |
| HP ProLiant            | 118      | 0.21%   |
| Gigabyte H61M-S1       | 118      | 0.21%   |
| ASRock Z77             | 116      | 0.2%    |
| Gigabyte X470          | 111      | 0.19%   |
| ASUS P6T               | 111      | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 6458     | 11.24%  |
| 2018    | 5404     | 9.41%   |
| 2011    | 4867     | 8.47%   |
| 2013    | 4836     | 8.42%   |
| 2009    | 4165     | 7.25%   |
| 2010    | 4115     | 7.16%   |
| 2019    | 3633     | 6.32%   |
| 2014    | 3580     | 6.23%   |
| 2017    | 3326     | 5.79%   |
| 2008    | 3167     | 5.51%   |
| 2007    | 2917     | 5.08%   |
| 2020    | 2698     | 4.7%    |
| 2015    | 2386     | 4.15%   |
| 2016    | 2210     | 3.85%   |
| 2006    | 1474     | 2.57%   |
| 2021    | 1036     | 1.8%    |
| 2005    | 665      | 1.16%   |
| 2004    | 226      | 0.39%   |
| 2003    | 117      | 0.2%    |
| Unknown | 87       | 0.15%   |
| 2022    | 32       | 0.06%   |
| 2002    | 27       | 0.05%   |
| 2001    | 13       | 0.02%   |
| 2000    | 8        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 57447    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 56483    | 98.1%   |
| Enabled  | 1094     | 1.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 57398    | 99.91%  |
| Yes  | 49       | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 12209    | 20.62%  |
| 3.01-4.0        | 12036    | 20.33%  |
| 16.01-24.0      | 11960    | 20.2%   |
| 4.01-8.0        | 8355     | 14.11%  |
| 32.01-64.0      | 5881     | 9.93%   |
| 1.01-2.0        | 3283     | 5.55%   |
| 64.01-256.0     | 1837     | 3.1%    |
| 2.01-3.0        | 1800     | 3.04%   |
| 24.01-32.0      | 1041     | 1.76%   |
| 0.51-1.0        | 524      | 0.89%   |
| Unknown         | 179      | 0.3%    |
| More than 256.0 | 56       | 0.09%   |
| 0.01-0.5        | 44       | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 24587    | 37.76%  |
| 2.01-3.0    | 12414    | 19.07%  |
| 0.51-1.0    | 10776    | 16.55%  |
| 4.01-8.0    | 6760     | 10.38%  |
| 3.01-4.0    | 5798     | 8.9%    |
| 8.01-16.0   | 2105     | 3.23%   |
| 0.01-0.5    | 1688     | 2.59%   |
| 16.01-24.0  | 435      | 0.67%   |
| Unknown     | 246      | 0.38%   |
| 24.01-32.0  | 161      | 0.25%   |
| 32.01-64.0  | 115      | 0.18%   |
| 64.01-256.0 | 26       | 0.04%   |
| 0           | 1        | 0.002%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 25723    | 42.49%  |
| 2       | 17153    | 28.34%  |
| 3       | 8757     | 14.47%  |
| 4       | 4405     | 7.28%   |
| 5       | 2057     | 3.4%    |
| 6       | 912      | 1.51%   |
| 0       | 559      | 0.92%   |
| 7       | 431      | 0.71%   |
| 8       | 209      | 0.35%   |
| 9       | 118      | 0.19%   |
| 10      | 54       | 0.09%   |
| 11      | 44       | 0.07%   |
| Unknown | 26       | 0.04%   |
| 12      | 21       | 0.03%   |
| 13      | 20       | 0.03%   |
| 14      | 8        | 0.01%   |
| 20      | 5        | 0.01%   |
| 16      | 5        | 0.01%   |
| 15      | 5        | 0.01%   |
| 17      | 4        | 0.01%   |
| 24      | 3        | 0.005%  |
| 25      | 2        | 0.003%  |
| 23      | 2        | 0.003%  |
| 22      | 2        | 0.003%  |
| 21      | 2        | 0.003%  |
| 19      | 2        | 0.003%  |
| 18      | 2        | 0.003%  |
| 71      | 1        | 0.002%  |
| 68      | 1        | 0.002%  |
| 32      | 1        | 0.002%  |
| 28      | 1        | 0.002%  |
| 27      | 1        | 0.002%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31578    | 53.93%  |
| No        | 26976    | 46.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 56835    | 98.92%  |
| No        | 619      | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37184    | 63.66%  |
| Yes       | 21224    | 36.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45398    | 77.92%  |
| Yes       | 12863    | 22.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 9450     | 16.19%  |
| USA          | 8669     | 14.85%  |
| Germany      | 5371     | 9.2%    |
| Unknown      | 4066     | 6.97%   |
| Brazil       | 3522     | 6.03%   |
| France       | 2284     | 3.91%   |
| UK           | 2074     | 3.55%   |
| Italy        | 1722     | 2.95%   |
| Canada       | 1675     | 2.87%   |
| Spain        | 1400     | 2.4%    |
| Hungary      | 1281     | 2.19%   |
| Poland       | 1224     | 2.1%    |
| Ukraine      | 1197     | 2.05%   |
| Netherlands  | 980      | 1.68%   |
| Australia    | 969      | 1.66%   |
| India        | 697      | 1.19%   |
| Sweden       | 574      | 0.98%   |
| Switzerland  | 568      | 0.97%   |
| Argentina    | 542      | 0.93%   |
| Austria      | 485      | 0.83%   |
| Mexico       | 473      | 0.81%   |
| Belgium      | 450      | 0.77%   |
| Czechia      | 441      | 0.76%   |
| Finland      | 399      | 0.68%   |
| Romania      | 395      | 0.68%   |
| Greece       | 383      | 0.66%   |
| Japan        | 340      | 0.58%   |
| Portugal     | 301      | 0.52%   |
| South Africa | 285      | 0.49%   |
| Belarus      | 274      | 0.47%   |
| Turkey       | 263      | 0.45%   |
| Norway       | 244      | 0.42%   |
| Bulgaria     | 244      | 0.42%   |
| China        | 236      | 0.4%    |
| Serbia       | 228      | 0.39%   |
| Denmark      | 208      | 0.36%   |
| New Zealand  | 205      | 0.35%   |
| Indonesia    | 204      | 0.35%   |
| Israel       | 200      | 0.34%   |
| Slovakia     | 187      | 0.32%   |
| Colombia     | 169      | 0.29%   |
| Taiwan       | 159      | 0.27%   |
| Chile        | 158      | 0.27%   |
| Kazakhstan   | 157      | 0.27%   |
| Ireland      | 133      | 0.23%   |
| South Korea  | 120      | 0.21%   |
| Philippines  | 115      | 0.2%    |
| Iran         | 115      | 0.2%    |
| Croatia      | 113      | 0.19%   |
| Thailand     | 112      | 0.19%   |
| Malaysia     | 102      | 0.17%   |
| Hong Kong    | 98       | 0.17%   |
| Egypt        | 94       | 0.16%   |
| Venezuela    | 91       | 0.16%   |
| Peru         | 90       | 0.15%   |
| Slovenia     | 89       | 0.15%   |
| Lithuania    | 89       | 0.15%   |
| Estonia      | 78       | 0.13%   |
| Vietnam      | 74       | 0.13%   |
| Singapore    | 70       | 0.12%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 4077     | 6.54%   |
| Moscow            | 1573     | 2.52%   |
| St Petersburg     | 645      | 1.03%   |
| Voronezh          | 465      | 0.75%   |
| Berlin            | 450      | 0.72%   |
| Sao Paulo         | 434      | 0.7%    |
| Pecherskoye       | 422      | 0.68%   |
| Budapest          | 389      | 0.62%   |
| Paris             | 306      | 0.49%   |
| Novosibirsk       | 301      | 0.48%   |
| Vienna            | 278      | 0.45%   |
| Yekaterinburg     | 277      | 0.44%   |
| Sydney            | 264      | 0.42%   |
| Kyiv              | 250      | 0.4%    |
| Warsaw            | 245      | 0.39%   |
| Rome              | 236      | 0.38%   |
| Hamburg           | 233      | 0.37%   |
| Madrid            | 229      | 0.37%   |
| Rio de Janeiro    | 226      | 0.36%   |
| Munich            | 213      | 0.34%   |
| Milan             | 209      | 0.34%   |
| Nizhniy Novgorod  | 201      | 0.32%   |
| Athens            | 201      | 0.32%   |
| Krasnodar         | 198      | 0.32%   |
| Rostov-on-Don     | 194      | 0.31%   |
| London            | 193      | 0.31%   |
| Frankfurt am Main | 193      | 0.31%   |
| Toronto           | 168      | 0.27%   |
| Montreal          | 166      | 0.27%   |
| Barcelona         | 156      | 0.25%   |
| Zurich            | 153      | 0.25%   |
| Amsterdam         | 152      | 0.24%   |
| Helsinki          | 150      | 0.24%   |
| Melbourne         | 147      | 0.24%   |
| Chelyabinsk       | 145      | 0.23%   |
| Srednyaya Akhtuba | 144      | 0.23%   |
| Brisbane          | 133      | 0.21%   |
| Perm              | 129      | 0.21%   |
| Buenos Aires      | 129      | 0.21%   |
| Prague            | 126      | 0.2%    |
| Stuttgart         | 123      | 0.2%    |
| Omsk              | 123      | 0.2%    |
| Chicago           | 123      | 0.2%    |
| Krasnoyarsk       | 122      | 0.2%    |
| Minsk             | 119      | 0.19%   |
| Saratov           | 116      | 0.19%   |
| Belgrade          | 115      | 0.18%   |
| Sofia             | 113      | 0.18%   |
| New York          | 113      | 0.18%   |
| Cologne           | 112      | 0.18%   |
| Bucharest         | 109      | 0.17%   |
| Belo Horizonte    | 107      | 0.17%   |
| Istanbul          | 106      | 0.17%   |
| Vancouver         | 101      | 0.16%   |
| Tel Aviv          | 101      | 0.16%   |
| Auckland          | 100      | 0.16%   |
| Portland          | 98       | 0.16%   |
| Kharkiv           | 95       | 0.15%   |
| Dallas            | 95       | 0.15%   |
| Curitiba          | 95       | 0.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 21843    | 37176  | 21.95%  |
| WDC                       | 21684    | 38150  | 21.79%  |
| Samsung Electronics       | 13957    | 24061  | 14.03%  |
| Kingston                  | 5639     | 8078   | 5.67%   |
| Toshiba                   | 5389     | 8095   | 5.42%   |
| Hitachi                   | 4496     | 6492   | 4.52%   |
| SanDisk                   | 3396     | 4729   | 3.41%   |
| Crucial                   | 3294     | 4864   | 3.31%   |
| Intel                     | 1568     | 2324   | 1.58%   |
| A-DATA Technology         | 1491     | 2077   | 1.5%    |
| MAXTOR                    | 1291     | 1762   | 1.3%    |
| Phison                    | 974      | 1435   | 0.98%   |
| Unknown                   | 932      | 1446   | 0.94%   |
| HGST                      | 915      | 1532   | 0.92%   |
| OCZ                       | 829      | 1101   | 0.83%   |
| China                     | 773      | 1032   | 0.78%   |
| SPCC                      | 695      | 934    | 0.7%    |
| Corsair                   | 551      | 750    | 0.55%   |
| PNY                       | 548      | 748    | 0.55%   |
| Patriot                   | 449      | 618    | 0.45%   |
| Silicon Motion            | 420      | 585    | 0.42%   |
| Intenso                   | 404      | 591    | 0.41%   |
| Transcend                 | 396      | 540    | 0.4%    |
| PLEXTOR                   | 343      | 588    | 0.34%   |
| SK Hynix                  | 332      | 451    | 0.33%   |
| Micron Technology         | 322      | 434    | 0.32%   |
| GOODRAM                   | 310      | 476    | 0.31%   |
| Hewlett-Packard           | 261      | 387    | 0.26%   |
| XPG                       | 247      | 336    | 0.25%   |
| Micron/Crucial Technology | 245      | 335    | 0.25%   |
| Apacer                    | 233      | 335    | 0.23%   |
| Fujitsu                   | 211      | 262    | 0.21%   |
| JMicron                   | 206      | 266    | 0.21%   |
| Team                      | 203      | 264    | 0.2%    |
| Gigabyte Technology       | 199      | 297    | 0.2%    |
| HUAWEI                    | 164      | 201    | 0.16%   |
| KingSpec                  | 160      | 235    | 0.16%   |
| ASMT                      | 150      | 212    | 0.15%   |
| Realtek Semiconductor     | 144      | 183    | 0.14%   |
| KingDian                  | 138      | 185    | 0.14%   |
| LITEON                    | 122      | 149    | 0.12%   |
| Lexar                     | 119      | 129    | 0.12%   |
| Smartbuy                  | 112      | 146    | 0.11%   |
| Mushkin                   | 112      | 161    | 0.11%   |
| SABRENT                   | 104      | 124    | 0.1%    |
| LITEONIT                  | 99       | 124    | 0.1%    |
| Apple                     | 95       | 113    | 0.1%    |
| AMD                       | 93       | 139    | 0.09%   |
| Netac                     | 85       | 140    | 0.09%   |
| KingFast                  | 66       | 90     | 0.07%   |
| Kingmax                   | 64       | 115    | 0.06%   |
| Unknown                   | 61       | 73     | 0.06%   |
| WD MediaMax               | 59       | 84     | 0.06%   |
| TO Exter                  | 59       | 72     | 0.06%   |
| Verbatim                  | 53       | 64     | 0.05%   |
| ExcelStor                 | 53       | 66     | 0.05%   |
| Lite-On                   | 47       | 64     | 0.05%   |
| LaCie                     | 47       | 76     | 0.05%   |
| Drevo                     | 44       | 62     | 0.04%   |
| Phison Electronics        | 41       | 50     | 0.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 1793     | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB   | 1178     | 1.01%   |
| Kingston SA400S37240G 240GB SSD  | 1145     | 0.99%   |
| Toshiba DT01ACA100 1TB           | 1074     | 0.92%   |
| Samsung SSD 850 EVO 250GB        | 976      | 0.84%   |
| Samsung SSD 860 EVO 500GB        | 923      | 0.79%   |
| Seagate ST3500418AS 500GB        | 915      | 0.79%   |
| Kingston SA400S37120G 120GB SSD  | 880      | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB         | 876      | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB   | 835      | 0.72%   |
| Kingston SV300S37A120G 120GB SSD | 783      | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB   | 778      | 0.67%   |
| Toshiba DT01ACA050 500GB         | 715      | 0.62%   |
| Samsung SSD 850 EVO 500GB        | 713      | 0.61%   |
| Samsung NVMe SSD Drive 500GB     | 706      | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB   | 683      | 0.59%   |
| Samsung SSD 860 EVO 1TB          | 602      | 0.52%   |
| Toshiba HDWD110 1TB              | 584      | 0.5%    |
| Samsung SSD 860 EVO 250GB        | 575      | 0.5%    |
| Seagate ST31000528AS 1TB         | 549      | 0.47%   |
| Kingston SA400S37480G 480GB SSD  | 508      | 0.44%   |
| Seagate ST31000524AS 1TB         | 501      | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB         | 496      | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB   | 491      | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB   | 487      | 0.42%   |
| Samsung NVMe SSD Drive 1TB       | 472      | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB   | 466      | 0.4%    |
| Crucial CT500MX500SSD1 500GB     | 456      | 0.39%   |
| Toshiba DT01ACA200 2TB           | 454      | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB   | 410      | 0.35%   |
| WDC WD5000AAKX-001CA0 500GB      | 401      | 0.35%   |
| Seagate ST3500413AS 500GB        | 395      | 0.34%   |
| Crucial CT240BX500SSD1 240GB     | 394      | 0.34%   |
| Seagate ST3160815AS 160GB        | 393      | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 373      | 0.32%   |
| Samsung HD103SJ 1TB              | 373      | 0.32%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 370      | 0.32%   |
| Samsung SSD 840 EVO 250GB        | 368      | 0.32%   |
| Crucial CT1000MX500SSD1 1TB      | 355      | 0.31%   |
| Seagate Expansion 1TB            | 351      | 0.3%    |
| Seagate ST1000DM003-9YN162 1TB   | 339      | 0.29%   |
| Seagate ST3250310AS 250GB        | 325      | 0.28%   |
| WDC WD10EARS-00Y5B1 1TB          | 315      | 0.27%   |
| Seagate ST1000DM003-1SB102 1TB   | 314      | 0.27%   |
| Samsung HD502HJ 500GB            | 313      | 0.27%   |
| Hitachi HDS721010CLA332 1TB      | 312      | 0.27%   |
| WDC WD20EARX-00PASB0 2TB         | 308      | 0.27%   |
| Seagate ST380815AS 80GB          | 305      | 0.26%   |
| Unknown SD/MMC/MS PRO 394GB      | 303      | 0.26%   |
| Seagate ST3250318AS 250GB        | 303      | 0.26%   |
| Samsung SSD 970 EVO Plus 500GB   | 299      | 0.26%   |
| Hitachi HDS721050CLA362 500GB    | 292      | 0.25%   |
| Samsung SSD 970 EVO Plus 1TB     | 281      | 0.24%   |
| Seagate ST3500312CS 500GB        | 274      | 0.24%   |
| Samsung SSD 840 EVO 120GB        | 273      | 0.24%   |
| SanDisk SDSSDA240G 240GB         | 270      | 0.23%   |
| Sandisk NVMe SSD Drive 500GB     | 270      | 0.23%   |
| Seagate ST3250410AS 250GB        | 269      | 0.23%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 266      | 0.23%   |
| WDC WD20EZRX-00D8PB0 2TB         | 265      | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21583    | 36581  | 36.58%  |
| WDC                 | 19906    | 34660  | 33.73%  |
| Toshiba             | 4949     | 7362   | 8.39%   |
| Hitachi             | 4496     | 6492   | 7.62%   |
| Samsung Electronics | 4461     | 6744   | 7.56%   |
| MAXTOR              | 1266     | 1718   | 2.15%   |
| HGST                | 912      | 1482   | 1.55%   |
| Unknown             | 348      | 492    | 0.59%   |
| Fujitsu             | 205      | 250    | 0.35%   |
| ASMT                | 114      | 155    | 0.19%   |
| Hewlett-Packard     | 106      | 165    | 0.18%   |
| SABRENT             | 94       | 112    | 0.16%   |
| Apple               | 62       | 73     | 0.11%   |
| Intenso             | 50       | 82     | 0.08%   |
| ExcelStor           | 49       | 62     | 0.08%   |
| WD MediaMax         | 35       | 51     | 0.06%   |
| asmedia             | 35       | 52     | 0.06%   |
| JMicron             | 31       | 48     | 0.05%   |
| IBM/Hitachi         | 31       | 36     | 0.05%   |
| QUANTUM             | 19       | 20     | 0.03%   |
| ASMT109x            | 19       | 36     | 0.03%   |
| LaCie               | 16       | 30     | 0.03%   |
| MARVELL             | 15       | 22     | 0.03%   |
| USB3.0              | 14       | 17     | 0.02%   |
| USB                 | 14       | 18     | 0.02%   |
| HPE                 | 13       | 22     | 0.02%   |
| KESU                | 12       | 19     | 0.02%   |
| IBM                 | 11       | 16     | 0.02%   |
| Magnetic Data       | 9        | 9      | 0.02%   |
| Inateck             | 9        | 14     | 0.02%   |
| USB 3.0             | 7        | 13     | 0.01%   |
| PHD 3.0             | 6        | 7      | 0.01%   |
| MaxDigital          | 6        | 8      | 0.01%   |
| Dell                | 6        | 10     | 0.01%   |
| Synology            | 5        | 13     | 0.01%   |
| Maxone              | 5        | 6      | 0.01%   |
| HGST HTS            | 5        | 5      | 0.01%   |
| China               | 5        | 5      | 0.01%   |
| Unknown             | 5        | 7      | 0.01%   |
| MDT                 | 4        | 4      | 0.01%   |
| Lenovo              | 4        | 6      | 0.01%   |
| RSH-319             | 3        | 3      | 0.01%   |
| Maxtor 6            | 3        | 3      | 0.01%   |
| LIO-ORG             | 3        | 10     | 0.01%   |
| ICY BOX             | 3        | 4      | 0.01%   |
| H/W                 | 3        | 3      | 0.01%   |
| Fantom              | 3        | 3      | 0.01%   |
| Config              | 3        | 3      | 0.01%   |
| ASMT106x            | 3        | 3      | 0.01%   |
| SINTECHI            | 2        | 2      | 0.003%  |
| RSH-339             | 2        | 2      | 0.003%  |
| IET                 | 2        | 4      | 0.003%  |
| IB                  | 2        | 4      | 0.003%  |
| CLOVER              | 2        | 2      | 0.003%  |
| Unknown (583)       | 1        | 1      | 0.002%  |
| TPH01204000GB       | 1        | 1      | 0.002%  |
| TPH00800640GB       | 1        | 1      | 0.002%  |
| TPH00100500GB       | 1        | 1      | 0.002%  |
| SUN                 | 1        | 3      | 0.002%  |
| Speeding            | 1        | 1      | 0.002%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7246     | 11600  | 22.96%  |
| Kingston            | 5149     | 7286   | 16.31%  |
| Crucial             | 3046     | 4503   | 9.65%   |
| SanDisk             | 2735     | 3783   | 8.66%   |
| WDC                 | 2056     | 2790   | 6.51%   |
| A-DATA Technology   | 1263     | 1758   | 4%      |
| Intel               | 958      | 1411   | 3.04%   |
| OCZ                 | 816      | 1069   | 2.59%   |
| China               | 761      | 1019   | 2.41%   |
| SPCC                | 640      | 857    | 2.03%   |
| PNY                 | 513      | 701    | 1.63%   |
| Patriot             | 422      | 589    | 1.34%   |
| Corsair             | 399      | 533    | 1.26%   |
| Transcend           | 366      | 498    | 1.16%   |
| Toshiba             | 353      | 524    | 1.12%   |
| PLEXTOR             | 312      | 520    | 0.99%   |
| Intenso             | 302      | 417    | 0.96%   |
| GOODRAM             | 300      | 459    | 0.95%   |
| Micron Technology   | 264      | 352    | 0.84%   |
| Apacer              | 222      | 323    | 0.7%    |
| Team                | 190      | 236    | 0.6%    |
| SK Hynix            | 164      | 220    | 0.52%   |
| KingSpec            | 156      | 231    | 0.49%   |
| KingDian            | 135      | 182    | 0.43%   |
| Gigabyte Technology | 133      | 201    | 0.42%   |
| Seagate             | 121      | 163    | 0.38%   |
| JMicron             | 112      | 132    | 0.35%   |
| Hewlett-Packard     | 111      | 151    | 0.35%   |
| Lexar               | 110      | 119    | 0.35%   |
| LITEON              | 109      | 136    | 0.35%   |
| Smartbuy            | 106      | 138    | 0.34%   |
| LITEONIT            | 99       | 124    | 0.31%   |
| Mushkin             | 98       | 146    | 0.31%   |
| AMD                 | 82       | 115    | 0.26%   |
| Unknown             | 76       | 96     | 0.24%   |
| Netac               | 75       | 128    | 0.24%   |
| Kingmax             | 64       | 115    | 0.2%    |
| TO Exter            | 59       | 72     | 0.19%   |
| Verbatim            | 53       | 64     | 0.17%   |
| Leven               | 38       | 44     | 0.12%   |
| DREVO               | 36       | 49     | 0.11%   |
| Unknown             | 35       | 40     | 0.11%   |
| External            | 33       | 38     | 0.1%    |
| Apple               | 32       | 39     | 0.1%    |
| TCSUNBOW            | 31       | 43     | 0.1%    |
| KingFast            | 31       | 38     | 0.1%    |
| DOGFISH             | 31       | 45     | 0.1%    |
| ASMT                | 30       | 47     | 0.1%    |
| OCZ-VERTEX3         | 26       | 35     | 0.08%   |
| EMTEC               | 26       | 31     | 0.08%   |
| Vaseky              | 25       | 30     | 0.08%   |
| MAXTOR              | 25       | 44     | 0.08%   |
| KIOXIA-EXCERIA      | 25       | 35     | 0.08%   |
| FOXLINE             | 25       | 29     | 0.08%   |
| AXIOMTEK            | 24       | 24     | 0.08%   |
| LDLC                | 22       | 29     | 0.07%   |
| OWC                 | 21       | 37     | 0.07%   |
| OCZ-VERTEX          | 19       | 23     | 0.06%   |
| Hoodisk             | 19       | 26     | 0.06%   |
| Pioneer             | 18       | 22     | 0.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 45085    | 97029  | 55.07%  |
| SSD     | 26261    | 45568  | 32.07%  |
| NVMe    | 8889     | 14418  | 10.86%  |
| Unknown | 1405     | 2083   | 1.72%   |
| MMC     | 234      | 301    | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 54355    | 138966 | 81.23%  |
| NVMe | 8888     | 14402  | 13.28%  |
| SAS  | 3437     | 5730   | 5.14%   |
| MMC  | 234      | 301    | 0.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 43164    | 82312  | 55.63%  |
| 0.51-1.0   | 20824    | 35594  | 26.84%  |
| 1.01-2.0   | 7475     | 12616  | 9.63%   |
| 3.01-4.0   | 2320     | 4378   | 2.99%   |
| 2.01-3.0   | 2045     | 3725   | 2.64%   |
| 4.01-10.0  | 1559     | 3387   | 2.01%   |
| 10.01-20.0 | 196      | 573    | 0.25%   |
| 20.01-50.0 | 5        | 9      | 0.01%   |
| 0          | 4        | 3      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14237    | 22.63%  |
| 251-500        | 11137    | 17.7%   |
| 501-1000       | 8958     | 14.24%  |
| 1001-2000      | 6159     | 9.79%   |
| 1-20           | 4946     | 7.86%   |
| 51-100         | 4588     | 7.29%   |
| More than 3000 | 4417     | 7.02%   |
| Unknown        | 2965     | 4.71%   |
| 2001-3000      | 2757     | 4.38%   |
| 21-50          | 2751     | 4.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 26141    | 40.59%  |
| 21-50          | 8322     | 12.92%  |
| 101-250        | 6570     | 10.2%   |
| 51-100         | 5513     | 8.56%   |
| 251-500        | 4724     | 7.34%   |
| 501-1000       | 4335     | 6.73%   |
| 1001-2000      | 2993     | 4.65%   |
| Unknown        | 2965     | 4.6%    |
| More than 3000 | 1703     | 2.64%   |
| 2001-3000      | 1121     | 1.74%   |
| 0              | 10       | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 360      | 485    | 2.72%   |
| Seagate ST3500418AS 500GB         | 249      | 353    | 1.88%   |
| WDC WD5000AAKX-001CA0 500GB       | 137      | 179    | 1.03%   |
| Seagate ST3250410AS 250GB         | 135      | 177    | 1.02%   |
| Seagate ST31000528AS 1TB          | 130      | 164    | 0.98%   |
| Seagate ST3250310AS 250GB         | 119      | 175    | 0.9%    |
| Seagate ST31000524AS 1TB          | 103      | 134    | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB    | 97       | 132    | 0.73%   |
| Seagate ST1000DM003-9YN162 1TB    | 95       | 107    | 0.72%   |
| Seagate ST3320613AS 320GB         | 94       | 127    | 0.71%   |
| Kingston SV300S37A120G 120GB SSD  | 91       | 105    | 0.69%   |
| WDC WD10EARS-00Y5B1 1TB           | 89       | 160    | 0.67%   |
| Seagate ST3160815AS 160GB         | 86       | 101    | 0.65%   |
| WDC WD5000AADS-00S9B0 500GB       | 85       | 103    | 0.64%   |
| Seagate ST31500341AS 1TB          | 81       | 114    | 0.61%   |
| Seagate ST3250318AS 250GB         | 80       | 106    | 0.6%    |
| Hitachi HDS721050CLA362 500GB     | 80       | 104    | 0.6%    |
| Hitachi HDS721010CLA332 1TB       | 77       | 102    | 0.58%   |
| Samsung Electronics HD080HJ 80GB  | 75       | 93     | 0.57%   |
| Seagate ST380011A 80GB            | 72       | 82     | 0.54%   |
| Hitachi HDP725050GLA360 500GB     | 72       | 96     | 0.54%   |
| Seagate ST3160811AS 160GB         | 69       | 98     | 0.52%   |
| Toshiba DT01ACA050 500GB          | 67       | 87     | 0.51%   |
| Samsung Electronics HD160JJ 160GB | 67       | 108    | 0.51%   |
| Seagate ST3320620AS 320GB         | 66       | 90     | 0.5%    |
| Seagate ST3500320AS 500GB         | 65       | 87     | 0.49%   |
| Samsung Electronics HD161HJ 160GB | 65       | 82     | 0.49%   |
| WDC WD3200AAJS-00L7A0 320GB       | 64       | 76     | 0.48%   |
| Seagate ST3500413AS 500GB         | 63       | 69     | 0.48%   |
| Toshiba DT01ACA100 1TB            | 61       | 86     | 0.46%   |
| Seagate ST380815AS 80GB           | 61       | 80     | 0.46%   |
| Hitachi HDS721616PLA380 160GB     | 61       | 81     | 0.46%   |
| Seagate ST250DM000-1BD141 250GB   | 60       | 79     | 0.45%   |
| Samsung Electronics HD321KJ 320GB | 58       | 68     | 0.44%   |
| MAXTOR STM3250310AS 250GB         | 58       | 80     | 0.44%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 56       | 76     | 0.42%   |
| Samsung Electronics HD103UJ 1TB   | 55       | 105    | 0.41%   |
| Seagate ST3320418AS 320GB         | 54       | 69     | 0.41%   |
| Seagate ST9500325AS 500GB         | 53       | 64     | 0.4%    |
| Samsung Electronics HD103SJ 1TB   | 50       | 82     | 0.38%   |
| Samsung Electronics SP2504C 250GB | 49       | 72     | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB    | 48       | 60     | 0.36%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 46       | 59     | 0.35%   |
| Samsung Electronics HD501LJ 500GB | 46       | 74     | 0.35%   |
| WDC WD20EARX-00PASB0 2TB          | 45       | 53     | 0.34%   |
| WDC WD5000AAKS-00V1A0 500GB       | 44       | 54     | 0.33%   |
| WDC WD20EARS-00MVWB0 2TB          | 43       | 52     | 0.32%   |
| Samsung Electronics HD502HJ 500GB | 43       | 54     | 0.32%   |
| MAXTOR 6Y080L0 82GB               | 40       | 48     | 0.3%    |
| Kingston SHFS37A120G 120GB SSD    | 39       | 48     | 0.29%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 38       | 45     | 0.29%   |
| Seagate ST1000DM010-2EP102 1TB    | 38       | 46     | 0.29%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 37       | 50     | 0.28%   |
| WDC WD10EZEX-00BN5A0 1TB          | 37       | 47     | 0.28%   |
| Seagate ST2000DM001-9YN164 2TB    | 37       | 46     | 0.28%   |
| Samsung Electronics HD103SI 1TB   | 37       | 43     | 0.28%   |
| WDC WD5000AAKX-003CA0 500GB       | 36       | 38     | 0.27%   |
| Samsung Electronics SP2004C 200GB | 36       | 45     | 0.27%   |
| Samsung Electronics HD322HJ 320GB | 36       | 36     | 0.27%   |
| Hitachi HDS721680PLA380 80GB      | 36       | 41     | 0.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4164     | 5922   | 33.44%  |
| WDC                 | 3560     | 5141   | 28.59%  |
| Samsung Electronics | 1312     | 1840   | 10.54%  |
| Hitachi             | 1067     | 1465   | 8.57%   |
| MAXTOR              | 417      | 540    | 3.35%   |
| Toshiba             | 407      | 533    | 3.27%   |
| Kingston            | 293      | 351    | 2.35%   |
| Intel               | 138      | 195    | 1.11%   |
| Crucial             | 125      | 159    | 1%      |
| SanDisk             | 118      | 141    | 0.95%   |
| A-DATA Technology   | 112      | 145    | 0.9%    |
| HGST                | 96       | 114    | 0.77%   |
| OCZ                 | 93       | 133    | 0.75%   |
| SPCC                | 62       | 81     | 0.5%    |
| Corsair             | 60       | 91     | 0.48%   |
| Fujitsu             | 42       | 50     | 0.34%   |
| Kingmax             | 29       | 55     | 0.23%   |
| Hewlett-Packard     | 22       | 26     | 0.18%   |
| SK Hynix            | 21       | 36     | 0.17%   |
| IBM/Hitachi         | 20       | 25     | 0.16%   |
| PLEXTOR             | 19       | 33     | 0.15%   |
| Micron Technology   | 19       | 25     | 0.15%   |
| China               | 18       | 25     | 0.14%   |
| ASMT                | 15       | 23     | 0.12%   |
| Intenso             | 11       | 16     | 0.09%   |
| ExcelStor           | 11       | 13     | 0.09%   |
| KingSpec            | 10       | 10     | 0.08%   |
| WD MediaMax         | 9        | 14     | 0.07%   |
| Unknown             | 9        | 14     | 0.07%   |
| Transcend           | 9        | 12     | 0.07%   |
| Patriot             | 9        | 11     | 0.07%   |
| LITEONIT            | 9        | 9      | 0.07%   |
| IBM                 | 9        | 11     | 0.07%   |
| Mushkin             | 7        | 7      | 0.06%   |
| LITEON              | 7        | 7      | 0.06%   |
| KingDian            | 6        | 8      | 0.05%   |
| Drevo               | 6        | 9      | 0.05%   |
| AMD                 | 6        | 8      | 0.05%   |
| Unknown             | 6        | 7      | 0.05%   |
| OCZ-VERTEX3         | 5        | 9      | 0.04%   |
| PNY                 | 4        | 5      | 0.03%   |
| Apacer              | 4        | 8      | 0.03%   |
| XPG                 | 3        | 3      | 0.02%   |
| Team                | 3        | 4      | 0.02%   |
| QUANTUM             | 3        | 3      | 0.02%   |
| Netac               | 3        | 3      | 0.02%   |
| LDLC                | 3        | 3      | 0.02%   |
| GOODRAM             | 3        | 3      | 0.02%   |
| asmedia             | 3        | 4      | 0.02%   |
| Apple               | 3        | 3      | 0.02%   |
| Verbatim            | 2        | 2      | 0.02%   |
| Smartbuy            | 2        | 2      | 0.02%   |
| Silicon Motion      | 2        | 6      | 0.02%   |
| QUMO                | 2        | 3      | 0.02%   |
| MDT                 | 2        | 2      | 0.02%   |
| Leven               | 2        | 2      | 0.02%   |
| INNOVATION IT       | 2        | 2      | 0.02%   |
| HPE                 | 2        | 2      | 0.02%   |
| Colorful            | 2        | 2      | 0.02%   |
| XrayDisk            | 1        | 1      | 0.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4163     | 5919   | 37.91%  |
| WDC                 | 3518     | 5080   | 32.04%  |
| Samsung Electronics | 1175     | 1668   | 10.7%   |
| Hitachi             | 1067     | 1465   | 9.72%   |
| MAXTOR              | 417      | 540    | 3.8%    |
| Toshiba             | 402      | 528    | 3.66%   |
| HGST                | 96       | 114    | 0.87%   |
| Fujitsu             | 42       | 50     | 0.38%   |
| IBM/Hitachi         | 20       | 25     | 0.18%   |
| Hewlett-Packard     | 14       | 18     | 0.13%   |
| ExcelStor           | 11       | 13     | 0.1%    |
| WD MediaMax         | 9        | 14     | 0.08%   |
| IBM                 | 9        | 11     | 0.08%   |
| ASMT                | 8        | 10     | 0.07%   |
| Unknown             | 7        | 12     | 0.06%   |
| QUANTUM             | 3        | 3      | 0.03%   |
| ASMedia             | 3        | 4      | 0.03%   |
| Apple               | 3        | 3      | 0.03%   |
| Unknown             | 3        | 4      | 0.03%   |
| MDT                 | 2        | 2      | 0.02%   |
| HPE                 | 2        | 2      | 0.02%   |
| TPH00100500GB       | 1        | 1      | 0.01%   |
| RSH-339             | 1        | 1      | 0.01%   |
| MaxDigital          | 1        | 1      | 0.01%   |
| ICY BOX             | 1        | 1      | 0.01%   |
| IB                  | 1        | 1      | 0.01%   |
| FEASSO              | 1        | 2      | 0.01%   |
| China               | 1        | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9656     | 15493  | 86.92%  |
| SSD  | 1336     | 1772   | 12.03%  |
| NVMe | 117      | 162    | 1.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 18       | 21     | 4.92%   |
| Seagate ST31000528AS 1TB          | 13       | 15     | 3.55%   |
| Samsung Electronics HD502HJ 500GB | 9        | 11     | 2.46%   |
| Hitachi HDS721010DLE630 1TB       | 9        | 18     | 2.46%   |
| Seagate ST31000524AS 1TB          | 8        | 10     | 2.19%   |
| Seagate ST3500412AS 500GB         | 6        | 8      | 1.64%   |
| Seagate ST3250318AS 250GB         | 5        | 10     | 1.37%   |
| Samsung Electronics HD322GJ 320GB | 5        | 6      | 1.37%   |
| Samsung Electronics HD103SJ 1TB   | 5        | 5      | 1.37%   |
| Seagate ST3500410AS 500GB         | 4        | 5      | 1.09%   |
| Seagate ST31000333AS 1TB          | 4        | 4      | 1.09%   |
| Samsung Electronics SP0411N 34GB  | 4        | 6      | 1.09%   |
| Samsung Electronics HD502IJ 500GB | 4        | 4      | 1.09%   |
| Apple HDD HTS541010A9E662 1TB     | 4        | 4      | 1.09%   |
| WDC WD5000AAKS-00V1A0 500GB       | 3        | 4      | 0.82%   |
| WDC WD3200AAJS-00L7A0 320GB       | 3        | 4      | 0.82%   |
| WDC WD15EARS-00MVWB0 1TB          | 3        | 7      | 0.82%   |
| Toshiba MK5065GSX 500GB           | 3        | 3      | 0.82%   |
| Toshiba DT01ACA200 2TB            | 3        | 3      | 0.82%   |
| Seagate ST500DM002-1BD142 500GB   | 3        | 3      | 0.82%   |
| Seagate ST500DM002-1BC142 500GB   | 3        | 3      | 0.82%   |
| Seagate ST3750528AS 752GB         | 3        | 3      | 0.82%   |
| Seagate ST3320613AS 320GB         | 3        | 4      | 0.82%   |
| Seagate ST32000542AS 2TB          | 3        | 5      | 0.82%   |
| Seagate ST31500341AS 1TB          | 3        | 4      | 0.82%   |
| Samsung Electronics HD252HJ 250GB | 3        | 12     | 0.82%   |
| Samsung Electronics HD204UI 2TB   | 3        | 3      | 0.82%   |
| MAXTOR 6Y080L0 82GB               | 3        | 3      | 0.82%   |
| Hitachi HDS721050DLE630 500GB     | 3        | 3      | 0.82%   |
| Hitachi HDS721025CLA382 250GB     | 3        | 3      | 0.82%   |
| Hitachi HDS721010CLA332 1TB       | 3        | 3      | 0.82%   |
| WDC WD800JD-00LSA0 80GB           | 2        | 2      | 0.55%   |
| WDC WD30EZRS-00J99B0 3TB          | 2        | 3      | 0.55%   |
| WDC WD2500JS-22NCB1 250GB         | 2        | 3      | 0.55%   |
| WDC WD20EZRX-00D8PB0 2TB          | 2        | 2      | 0.55%   |
| Toshiba MK1059GSM 1TB             | 2        | 2      | 0.55%   |
| Toshiba DT01ACA100 1TB            | 2        | 3      | 0.55%   |
| Toshiba DT01ACA050 500GB          | 2        | 2      | 0.55%   |
| Seagate STM3500418AS 500GB        | 2        | 2      | 0.55%   |
| Seagate ST9320325AS 320GB         | 2        | 3      | 0.55%   |
| Seagate ST9250315AS 250GB         | 2        | 2      | 0.55%   |
| Seagate ST500DM005 HD502HJ 500GB  | 2        | 3      | 0.55%   |
| Seagate ST380815AS 80GB           | 2        | 4      | 0.55%   |
| Seagate ST3640323AS 640GB         | 2        | 2      | 0.55%   |
| Seagate ST3500630AS 500GB         | 2        | 3      | 0.55%   |
| Seagate ST3320418AS 320GB         | 2        | 2      | 0.55%   |
| Seagate ST3160815AS 160GB         | 2        | 2      | 0.55%   |
| Seagate ST3160318AS 160GB         | 2        | 2      | 0.55%   |
| Seagate ST31000340NS 1TB          | 2        | 2      | 0.55%   |
| Samsung Electronics HM321HI 320GB | 2        | 3      | 0.55%   |
| Samsung Electronics HM250HI 250GB | 2        | 2      | 0.55%   |
| Samsung Electronics HD321HJ 320GB | 2        | 3      | 0.55%   |
| Samsung Electronics HD251HJ 250GB | 2        | 2      | 0.55%   |
| Samsung Electronics HD160JJ 160GB | 2        | 2      | 0.55%   |
| Samsung Electronics HD105SI 1TB   | 2        | 2      | 0.55%   |
| Samsung Electronics HD103UJ 1TB   | 2        | 2      | 0.55%   |
| MAXTOR STM380211AS 80GB           | 2        | 2      | 0.55%   |
| Kingston SV300S37A120G 120GB SSD  | 2        | 2      | 0.55%   |
| Hitachi HDT721032SLA380 320GB     | 2        | 2      | 0.55%   |
| HGST HTS545050A7E680 500GB        | 2        | 2      | 0.55%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 120      | 147    | 32.88%  |
| WDC                 | 84       | 101    | 23.01%  |
| Samsung Electronics | 69       | 89     | 18.9%   |
| Hitachi             | 32       | 42     | 8.77%   |
| Toshiba             | 20       | 21     | 5.48%   |
| MAXTOR              | 11       | 11     | 3.01%   |
| HGST                | 7        | 7      | 1.92%   |
| Apple               | 4        | 4      | 1.1%    |
| Kingston            | 3        | 3      | 0.82%   |
| Hewlett-Packard     | 2        | 2      | 0.55%   |
| Crucial             | 2        | 2      | 0.55%   |
| Transcend           | 1        | 1      | 0.27%   |
| TPH00800640GB       | 1        | 1      | 0.27%   |
| Patriot             | 1        | 2      | 0.27%   |
| OCZ-AGIL            | 1        | 1      | 0.27%   |
| OCZ                 | 1        | 1      | 0.27%   |
| Mushkin             | 1        | 1      | 0.27%   |
| Intenso             | 1        | 1      | 0.27%   |
| Intel               | 1        | 1      | 0.27%   |
| GOODRAM             | 1        | 1      | 0.27%   |
| Corsair             | 1        | 1      | 0.27%   |
| A-DATA Technology   | 1        | 1      | 0.27%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 30721    | 82541  | 46.57%  |
| Works    | 24141    | 58988  | 36.59%  |
| Malfunc  | 10746    | 17427  | 16.29%  |
| Failed   | 361      | 441    | 0.55%   |
| Limited  | 2        | 2      | 0.003%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 36498    | 48.05%  |
| AMD                              | 17466    | 22.99%  |
| Samsung Electronics              | 3938     | 5.18%   |
| Nvidia                           | 2973     | 3.91%   |
| JMicron Technology               | 2707     | 3.56%   |
| ASMedia Technology               | 2525     | 3.32%   |
| Marvell Technology Group         | 2281     | 3%      |
| Phison Electronics               | 1319     | 1.74%   |
| Sandisk                          | 1163     | 1.53%   |
| VIA Technologies                 | 746      | 0.98%   |
| Silicon Motion                   | 587      | 0.77%   |
| Kingston Technology Company      | 582      | 0.77%   |
| Micron/Crucial Technology        | 500      | 0.66%   |
| ADATA Technology                 | 418      | 0.55%   |
| LSI Logic / Symbios Logic        | 251      | 0.33%   |
| Silicon Image                    | 250      | 0.33%   |
| Realtek Semiconductor            | 247      | 0.33%   |
| Broadcom / LSI                   | 203      | 0.27%   |
| SK Hynix                         | 169      | 0.22%   |
| Toshiba America Info Systems     | 146      | 0.19%   |
| Silicon Integrated Systems [SiS] | 139      | 0.18%   |
| Adaptec                          | 136      | 0.18%   |
| Integrated Technology Express    | 103      | 0.14%   |
| Seagate Technology               | 92       | 0.12%   |
| Lite-On Technology               | 84       | 0.11%   |
| Micron Technology                | 75       | 0.1%    |
| KIOXIA                           | 51       | 0.07%   |
| Hewlett-Packard                  | 38       | 0.05%   |
| ULi Electronics                  | 31       | 0.04%   |
| OCZ Technology Group             | 30       | 0.04%   |
| Promise Technology               | 29       | 0.04%   |
| Shenzhen Longsys Electronics     | 26       | 0.03%   |
| HighPoint Technologies           | 23       | 0.03%   |
| 3ware                            | 17       | 0.02%   |
| Lite-On IT Corp. / Plextor       | 16       | 0.02%   |
| Unknown                          | 13       | 0.02%   |
| Solid State Storage Technology   | 11       | 0.01%   |
| Union Memory (Shenzhen)          | 8        | 0.01%   |
| Broadcom                         | 8        | 0.01%   |
| Yangtze Memory Technologies      | 6        | 0.01%   |
| MAXIO Technology (Hangzhou)      | 5        | 0.01%   |
| Tekram Technology                | 4        | 0.01%   |
| Biwin Storage Technology         | 4        | 0.01%   |
| Advanced System Products         | 4        | 0.01%   |
| MCST                             | 3        | 0.004%  |
| Lenovo                           | 3        | 0.004%  |
| Initio                           | 3        | 0.004%  |
| Beijing Starblaze Technology     | 3        | 0.004%  |
| ATTO Technology                  | 3        | 0.004%  |
| ATI Technologies                 | 3        | 0.004%  |
| Artop Electronic                 | 3        | 0.004%  |
| Areca Technology                 | 3        | 0.004%  |
| Toshiba                          | 2        | 0.003%  |
| Loongson Technology              | 2        | 0.003%  |
| Apple                            | 2        | 0.003%  |
| Zhaoxin                          | 1        | 0.001%  |
| Western Digital                  | 1        | 0.001%  |
| Synopsys                         | 1        | 0.001%  |
| Mylex                            | 1        | 0.001%  |
| Hefei DATANG Storage Technology  | 1        | 0.001%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9356     | 9.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4494     | 4.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4031     | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3987     | 3.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3462     | 3.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3343     | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3150     | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2876     | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2846     | 2.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2624     | 2.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2570     | 2.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2513     | 2.44%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2381     | 2.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2038     | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1910     | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1904     | 1.85%   |
| Intel SATA Controller [RAID mode]                                                       | 1870     | 1.81%   |
| Nvidia MCP61 SATA Controller                                                            | 1576     | 1.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1456     | 1.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1437     | 1.39%   |
| Nvidia MCP61 IDE                                                                        | 1357     | 1.32%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1077     | 1.05%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1061     | 1.03%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1001     | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 998      | 0.97%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 979      | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 910      | 0.88%   |
| AMD FCH SATA Controller D                                                               | 889      | 0.86%   |
| JMicron JMB368 IDE controller                                                           | 817      | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 790      | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 755      | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 740      | 0.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 722      | 0.7%    |
| Phison E12 NVMe Controller                                                              | 698      | 0.68%   |
| AMD FCH IDE Controller                                                                  | 680      | 0.66%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 654      | 0.63%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 646      | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 634      | 0.62%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 584      | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 584      | 0.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 508      | 0.49%   |
| AMD X370 Series Chipset SATA Controller                                                 | 489      | 0.47%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 482      | 0.47%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 474      | 0.46%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 471      | 0.46%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 462      | 0.45%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 423      | 0.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 422      | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 419      | 0.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 408      | 0.4%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 404      | 0.39%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 402      | 0.39%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 395      | 0.38%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 390      | 0.38%   |
| Kingston Company A2000 NVMe SSD                                                         | 361      | 0.35%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 361      | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 360      | 0.35%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 350      | 0.34%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 342      | 0.33%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 339      | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40714    | 53.57%  |
| IDE  | 22209    | 29.22%  |
| NVMe | 9083     | 11.95%  |
| RAID | 3349     | 4.41%   |
| SAS  | 376      | 0.49%   |
| SCSI | 273      | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 37195    | 64.74%  |
| AMD                      | 20213    | 35.18%  |
| CentaurHauls             | 14       | 0.02%   |
| ARM                      | 9        | 0.02%   |
| Unknown                  | 6        | 0.01%   |
| PowerNV C1P9S01 REV 1.01 | 2        | 0.003%  |
| Marvell Semiconductor    | 2        | 0.003%  |
| PowerMac8,1              | 1        | 0.002%  |
| PowerMac7,2              | 1        | 0.002%  |
| PowerMac3,6              | 1        | 0.002%  |
| PowerMac10,2             | 1        | 0.002%  |
| PowerBook5,5             | 1        | 0.002%  |
| MBE8C-PC                 | 1        | 0.002%  |
| E8C/EATX                 | 1        | 0.002%  |
| E8C-SWTX                 | 1        | 0.002%  |
| CHRP IBM,9131-52A        | 1        | 0.002%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 936      | 1.62%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 801      | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 735      | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 699      | 1.21%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 645      | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 596      | 1.03%   |
| AMD FX-8350 Eight-Core Processor            | 578      | 1%      |
| AMD FX-6300 Six-Core Processor              | 574      | 0.99%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 550      | 0.95%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 531      | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 492      | 0.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 488      | 0.84%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 488      | 0.84%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 472      | 0.82%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 467      | 0.81%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 457      | 0.79%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 450      | 0.78%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 421      | 0.73%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 414      | 0.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 394      | 0.68%   |
| Intel Pentium 4 CPU 3.00GHz                 | 378      | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 360      | 0.62%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 354      | 0.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 343      | 0.59%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 338      | 0.58%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 333      | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 328      | 0.57%   |
| AMD Athlon II X2 250 Processor              | 326      | 0.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 325      | 0.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 323      | 0.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 310      | 0.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 297      | 0.51%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 286      | 0.49%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 283      | 0.49%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 282      | 0.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 278      | 0.48%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 275      | 0.48%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 272      | 0.47%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 271      | 0.47%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 267      | 0.46%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 266      | 0.46%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 266      | 0.46%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 264      | 0.46%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 264      | 0.46%   |
| AMD Phenom II X4 955 Processor              | 258      | 0.45%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 257      | 0.44%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 256      | 0.44%   |
| AMD FX-8320 Eight-Core Processor            | 253      | 0.44%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 252      | 0.44%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 250      | 0.43%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 250      | 0.43%   |
| AMD FX-4300 Quad-Core Processor             | 248      | 0.43%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 247      | 0.43%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 244      | 0.42%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 240      | 0.42%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 239      | 0.41%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 237      | 0.41%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 229      | 0.4%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 226      | 0.39%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 224      | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 9328     | 16.16%  |
| Intel Core i7           | 6706     | 11.62%  |
| Intel Core i3           | 4350     | 7.54%   |
| AMD Ryzen 5             | 3722     | 6.45%   |
| Intel Core 2 Duo        | 3028     | 5.25%   |
| AMD FX                  | 2748     | 4.76%   |
| Intel Xeon              | 2484     | 4.3%    |
| AMD Ryzen 7             | 2478     | 4.29%   |
| Intel Celeron           | 2110     | 3.66%   |
| Intel Pentium           | 1910     | 3.31%   |
| Intel Core 2 Quad       | 1673     | 2.9%    |
| Intel Pentium Dual-Core | 1508     | 2.61%   |
| AMD Athlon 64 X2        | 1247     | 2.16%   |
| AMD Athlon II X2        | 1117     | 1.94%   |
| AMD Phenom II X4        | 1012     | 1.75%   |
| AMD Ryzen 9             | 992      | 1.72%   |
| Intel Pentium 4         | 894      | 1.55%   |
| AMD Ryzen 3             | 878      | 1.52%   |
| Intel Core 2            | 673      | 1.17%   |
| AMD A8                  | 660      | 1.14%   |
| Intel Pentium Dual      | 598      | 1.04%   |
| AMD A10                 | 587      | 1.02%   |
| AMD Athlon II X4        | 515      | 0.89%   |
| Intel Atom              | 487      | 0.84%   |
| Other                   | 470      | 0.81%   |
| AMD A4                  | 447      | 0.77%   |
| Intel Core i9           | 443      | 0.77%   |
| Intel Pentium D         | 411      | 0.71%   |
| AMD Phenom II X6        | 356      | 0.62%   |
| AMD Athlon              | 353      | 0.61%   |
| AMD A6                  | 353      | 0.61%   |
| AMD Ryzen Threadripper  | 312      | 0.54%   |
| AMD Phenom              | 311      | 0.54%   |
| AMD Athlon 64           | 284      | 0.49%   |
| AMD Sempron             | 280      | 0.49%   |
| AMD Athlon II X3        | 270      | 0.47%   |
| AMD Athlon X4           | 205      | 0.36%   |
| AMD Phenom II X2        | 168      | 0.29%   |
| Intel Pentium Gold      | 149      | 0.26%   |
| AMD E                   | 110      | 0.19%   |
| Intel Genuine           | 102      | 0.18%   |
| AMD Ryzen 5 PRO         | 90       | 0.16%   |
| AMD Athlon Dual Core    | 89       | 0.15%   |
| AMD E1                  | 62       | 0.11%   |
| AMD Phenom II X3        | 61       | 0.11%   |
| AMD Ryzen 7 PRO         | 55       | 0.1%    |
| AMD GX                  | 55       | 0.1%    |
| Intel Pentium Silver    | 48       | 0.08%   |
| AMD Ryzen 3 PRO         | 43       | 0.07%   |
| AMD E2                  | 43       | 0.07%   |
| AMD Athlon X2           | 40       | 0.07%   |
| AMD Athlon XP           | 38       | 0.07%   |
| Intel Celeron D         | 36       | 0.06%   |
| AMD Turion II Neo       | 34       | 0.06%   |
| Intel Core 2 Extreme    | 26       | 0.05%   |
| AMD G                   | 26       | 0.05%   |
| AMD A12                 | 24       | 0.04%   |
| AMD Ryzen Embedded      | 20       | 0.03%   |
| AMD Quad-Core Opteron   | 18       | 0.03%   |
| AMD PRO A10             | 17       | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 21637    | 37.22%  |
| 2       | 18984    | 32.66%  |
| 6       | 6312     | 10.86%  |
| 8       | 3982     | 6.85%   |
| 1       | 2594     | 4.46%   |
| Unknown | 1294     | 2.23%   |
| 3       | 1234     | 2.12%   |
| 12      | 1034     | 1.78%   |
| 16      | 536      | 0.92%   |
| 10      | 234      | 0.4%    |
| 24      | 97       | 0.17%   |
| 32      | 68       | 0.12%   |
| 14      | 29       | 0.05%   |
| 20      | 18       | 0.03%   |
| 18      | 17       | 0.03%   |
| 64      | 16       | 0.03%   |
| 28      | 14       | 0.02%   |
| 5       | 9        | 0.02%   |
| 44      | 4        | 0.01%   |
| 22      | 4        | 0.01%   |
| 40      | 3        | 0.01%   |
| 48      | 2        | 0.003%  |
| 36      | 2        | 0.003%  |
| 15      | 1        | 0.002%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 56737    | 98.67%  |
| 2       | 684      | 1.19%   |
| Unknown | 76       | 0.13%   |
| 4       | 3        | 0.01%   |
| 0       | 1        | 0.002%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 29692    | 51.15%  |
| 2       | 27055    | 46.61%  |
| Unknown | 1294     | 2.23%   |
| 4       | 3        | 0.01%   |
| 8       | 2        | 0.003%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 55716    | 96.49%  |
| Unknown        | 1368     | 2.37%   |
| 32-bit         | 567      | 0.98%   |
| 64-bit         | 94       | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10132    | 17.03%  |
| 0x306c3    | 4692     | 7.88%   |
| 0x206a7    | 3911     | 6.57%   |
| 0x1067a    | 3906     | 6.56%   |
| 0x306a9    | 3682     | 6.19%   |
| 0x506e3    | 1892     | 3.18%   |
| 0x010000c8 | 1735     | 2.92%   |
| 0x08701021 | 1509     | 2.54%   |
| 0x906e9    | 1350     | 2.27%   |
| 0x06000852 | 1345     | 2.26%   |
| 0x906ea    | 1308     | 2.2%    |
| 0x0800820d | 1180     | 1.98%   |
| 0x6fd      | 995      | 1.67%   |
| 0x06001119 | 994      | 1.67%   |
| 0x6fb      | 985      | 1.66%   |
| 0x08701013 | 898      | 1.51%   |
| 0x10676    | 839      | 1.41%   |
| 0x106e5    | 597      | 1%      |
| 0x08108109 | 542      | 0.91%   |
| 0x08001138 | 493      | 0.83%   |
| 0x010000db | 478      | 0.8%    |
| 0x20655    | 472      | 0.79%   |
| 0x906ed    | 446      | 0.75%   |
| 0x06003106 | 425      | 0.71%   |
| 0x106a5    | 417      | 0.7%    |
| 0x6f6      | 396      | 0.67%   |
| 0xa0655    | 388      | 0.65%   |
| 0x08001137 | 387      | 0.65%   |
| 0x306f2    | 373      | 0.63%   |
| 0xa0653    | 367      | 0.62%   |
| 0x206d7    | 365      | 0.61%   |
| 0x0600063e | 357      | 0.6%    |
| 0x20652    | 343      | 0.58%   |
| 0x0a201009 | 334      | 0.56%   |
| 0x906eb    | 331      | 0.56%   |
| 0x6f2      | 306      | 0.51%   |
| 0x08101016 | 306      | 0.51%   |
| 0x206c2    | 301      | 0.51%   |
| 0x010000dc | 291      | 0.49%   |
| 0x10677    | 290      | 0.49%   |
| 0x0810100b | 283      | 0.48%   |
| 0x03000027 | 267      | 0.45%   |
| 0xf41      | 253      | 0.43%   |
| 0x010000c7 | 249      | 0.42%   |
| 0x0600084f | 245      | 0.41%   |
| 0x306e4    | 230      | 0.39%   |
| 0x0a201016 | 229      | 0.38%   |
| 0xf49      | 223      | 0.37%   |
| 0xf65      | 220      | 0.37%   |
| 0x906ec    | 211      | 0.35%   |
| 0x30678    | 203      | 0.34%   |
| 0xa0671    | 201      | 0.34%   |
| 0x0800820b | 195      | 0.33%   |
| 0x06000822 | 187      | 0.31%   |
| 0x010000b6 | 181      | 0.3%    |
| 0xf43      | 179      | 0.3%    |
| 0x0600611a | 174      | 0.29%   |
| 0x106ca    | 162      | 0.27%   |
| 0x01000083 | 161      | 0.27%   |
| 0x01000095 | 155      | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 5937     | 10.29%  |
| Penryn           | 5317     | 9.22%   |
| SandyBridge      | 4791     | 8.3%    |
| IvyBridge        | 4436     | 7.69%   |
| KabyLake         | 4393     | 7.61%   |
| K10              | 4039     | 7%      |
| Piledriver       | 3273     | 5.67%   |
| Zen 2            | 3228     | 5.59%   |
| Core             | 3165     | 5.49%   |
| Zen+             | 2465     | 4.27%   |
| Skylake          | 2409     | 4.18%   |
| Zen              | 2138     | 3.71%   |
| K8 Hammer        | 1814     | 3.14%   |
| NetBurst         | 1586     | 2.75%   |
| Westmere         | 1231     | 2.13%   |
| Nehalem          | 1208     | 2.09%   |
| Zen 3            | 947      | 1.64%   |
| CometLake        | 936      | 1.62%   |
| Silvermont       | 598      | 1.04%   |
| Bulldozer        | 594      | 1.03%   |
| Steamroller      | 550      | 0.95%   |
| Unknown          | 416      | 0.72%   |
| Bonnell          | 340      | 0.59%   |
| K10 Llano        | 314      | 0.54%   |
| Excavator        | 310      | 0.54%   |
| Goldmont plus    | 215      | 0.37%   |
| Jaguar           | 198      | 0.34%   |
| Broadwell        | 188      | 0.33%   |
| Bobcat           | 185      | 0.32%   |
| Goldmont         | 130      | 0.23%   |
| Icelake          | 119      | 0.21%   |
| Puma             | 78       | 0.14%   |
| K6               | 57       | 0.1%    |
| Alderlake Hybrid | 57       | 0.1%    |
| P6               | 17       | 0.03%   |
| Tremont          | 8        | 0.01%   |
| TigerLake        | 6        | 0.01%   |
| K8 & K10 hybrid  | 3        | 0.01%   |
| Geode            | 1        | 0.002%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 25754    | 42.14%  |
| AMD                                          | 18071    | 29.57%  |
| Intel                                        | 16737    | 27.38%  |
| Matrox Electronics Systems                   | 164      | 0.27%   |
| ASPEED Technology                            | 130      | 0.21%   |
| VIA Technologies                             | 119      | 0.19%   |
| Silicon Integrated Systems [SiS]             | 51       | 0.08%   |
| ATI Technologies                             | 34       | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 26       | 0.04%   |
| S3 Graphics                                  | 16       | 0.03%   |
| Silicon Motion                               | 11       | 0.02%   |
| Loongson Technology                          | 2        | 0.003%  |
| Zhaoxin                                      | 1        | 0.002%  |
| Trident Microsystems                         | 1        | 0.002%  |
| NVidia / SGS Thomson (Joint Venture)         | 1        | 0.002%  |
| Dome Imaging Systems                         | 1        | 0.002%  |
| Conexant Systems                             | 1        | 0.002%  |
| Alliance Semiconductor                       | 1        | 0.002%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2556     | 4.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2405     | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2143     | 3.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1521     | 2.4%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1467     | 2.32%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1345     | 2.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1226     | 1.94%   |
| Nvidia GT218 [GeForce 210]                                                               | 1171     | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1079     | 1.7%    |
| Intel HD Graphics 530                                                                    | 914      | 1.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 825      | 1.3%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 822      | 1.3%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 773      | 1.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 720      | 1.14%   |
| Intel HD Graphics 630                                                                    | 674      | 1.06%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 632      | 1%      |
| Nvidia GP108 [GeForce GT 1030]                                                           | 629      | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 606      | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 602      | 0.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 595      | 0.94%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 579      | 0.91%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 565      | 0.89%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 544      | 0.86%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 544      | 0.86%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 544      | 0.86%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 529      | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 526      | 0.83%   |
| AMD RS780L [Radeon 3000]                                                                 | 517      | 0.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 488      | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 485      | 0.77%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 454      | 0.72%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 439      | 0.69%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 430      | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 407      | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 404      | 0.64%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 401      | 0.63%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 392      | 0.62%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 391      | 0.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 387      | 0.61%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 366      | 0.58%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 341      | 0.54%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 332      | 0.52%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 330      | 0.52%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 321      | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 307      | 0.48%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 305      | 0.48%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 300      | 0.47%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 298      | 0.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 296      | 0.47%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 290      | 0.46%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 286      | 0.45%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 276      | 0.44%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 273      | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 272      | 0.43%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 270      | 0.43%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 269      | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 265      | 0.42%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 262      | 0.41%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 256      | 0.4%    |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 252      | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Nvidia                               | 24238    | 41.48%  |
| 1 x AMD                                  | 16325    | 27.94%  |
| 1 x Intel                                | 14392    | 24.63%  |
| 2 x AMD                                  | 1053     | 1.8%    |
| Intel + Nvidia                           | 755      | 1.29%   |
| AMD + Nvidia                             | 356      | 0.61%   |
| Intel + AMD                              | 317      | 0.54%   |
| 2 x Nvidia                               | 305      | 0.52%   |
| 1 x Matrox                               | 142      | 0.24%   |
| 1 x VIA                                  | 117      | 0.2%    |
| 1 x ASPEED                               | 95       | 0.16%   |
| Other                                    | 64       | 0.11%   |
| 1 x SiS                                  | 50       | 0.09%   |
| 1 x XGI                                  | 22       | 0.04%   |
| Nvidia + ASPEED                          | 20       | 0.03%   |
| Intel + 2 x Nvidia                       | 19       | 0.03%   |
| Nvidia + Matrox                          | 16       | 0.03%   |
| 1 x S3 Graphics                          | 13       | 0.02%   |
| 3 x AMD                                  | 12       | 0.02%   |
| Intel + AMD + 1 x Nvidia                 | 12       | 0.02%   |
| 3 x Nvidia                               | 11       | 0.02%   |
| Intel + 2 x AMD                          | 11       | 0.02%   |
| AMD + ASPEED                             | 11       | 0.02%   |
| 2 x AMD + 1 x Nvidia                     | 9        | 0.02%   |
| 1 x Silicon Motion                       | 8        | 0.01%   |
| AMD + 2 x Nvidia                         | 6        | 0.01%   |
| AMD + Matrox                             | 5        | 0.01%   |
| Nvidia + XGI                             | 3        | 0.01%   |
| 1 x Intel + 3 x Nvidia                   | 3        | 0.01%   |
| 4 x Nvidia                               | 2        | 0.003%  |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED        | 2        | 0.003%  |
| 1 x Intel + 4 x Nvidia                   | 2        | 0.003%  |
| 1 x Intel + 3 x AMD                      | 2        | 0.003%  |
| Intel + Silicon Motion                   | 2        | 0.003%  |
| 6 x Nvidia                               | 1        | 0.002%  |
| 5 x Nvidia                               | 1        | 0.002%  |
| 5 x AMD                                  | 1        | 0.002%  |
| 3 x AMD + 1 x Nvidia                     | 1        | 0.002%  |
| 2 x Loongson Technology                  | 1        | 0.002%  |
| 2 x Intel                                | 1        | 0.002%  |
| 2 x AMD + 1 x Conexant Systems           | 1        | 0.002%  |
| 2 x AMD + 1 x ASPEED                     | 1        | 0.002%  |
| 2 x AMD + 1 x Alliance Semiconductor     | 1        | 0.002%  |
| 1 x Zhaoxin                              | 1        | 0.002%  |
| 1 x Trident Microsystems                 | 1        | 0.002%  |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.002%  |
| Nvidia + VIA                             | 1        | 0.002%  |
| Nvidia + Silicon Motion                  | 1        | 0.002%  |
| Nvidia + Dome Imaging Systems            | 1        | 0.002%  |
| 1 x Loongson Technology                  | 1        | 0.002%  |
| 1 x Intel + 7 x Nvidia                   | 1        | 0.002%  |
| Intel + 5 x AMD + Nvidia                 | 1        | 0.002%  |
| 1 x Intel + 4 x AMD                      | 1        | 0.002%  |
| Intel + SiS + 1 x S3 Graphics            | 1        | 0.002%  |
| Intel + S3 Graphics                      | 1        | 0.002%  |
| Intel + AMD + 4 x Nvidia                 | 1        | 0.002%  |
| Intel + AMD + 2 x Nvidia                 | 1        | 0.002%  |
| AMD + XGI                                | 1        | 0.002%  |
| AMD + SiS                                | 1        | 0.002%  |
| AMD + S3 Graphics                        | 1        | 0.002%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 42228    | 71.23%  |
| Proprietary | 13790    | 23.26%  |
| Unknown     | 3265     | 5.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20660    | 34.27%  |
| 1.01-2.0   | 10156    | 16.84%  |
| 0.51-1.0   | 8898     | 14.76%  |
| 0.01-0.5   | 8582     | 14.23%  |
| 3.01-4.0   | 4593     | 7.62%   |
| 7.01-8.0   | 3996     | 6.63%   |
| 5.01-6.0   | 1700     | 2.82%   |
| 8.01-16.0  | 852      | 1.41%   |
| 2.01-3.0   | 736      | 1.22%   |
| 16.01-24.0 | 80       | 0.13%   |
| 4.01-5.0   | 34       | 0.06%   |
| 24.01-32.0 | 4        | 0.01%   |
| 32.01-64.0 | 3        | 0.005%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 11221    | 18.78%  |
| Goldstar                | 7071     | 11.84%  |
| Dell                    | 5707     | 9.55%   |
| Acer                    | 4883     | 8.17%   |
| Hewlett-Packard         | 3573     | 5.98%   |
| BenQ                    | 3223     | 5.4%    |
| Ancor Communications    | 2862     | 4.79%   |
| AOC                     | 2849     | 4.77%   |
| Philips                 | 2846     | 4.76%   |
| ViewSonic               | 1601     | 2.68%   |
| Iiyama                  | 958      | 1.6%    |
| LG Electronics          | 920      | 1.54%   |
| Unknown                 | 893      | 1.49%   |
| Sony                    | 714      | 1.2%    |
| NEC Computers           | 662      | 1.11%   |
| Lenovo                  | 649      | 1.09%   |
| ASUSTek Computer        | 568      | 0.95%   |
| Fujitsu Siemens         | 424      | 0.71%   |
| Eizo                    | 394      | 0.66%   |
| HannStar                | 317      | 0.53%   |
| Vizio                   | 304      | 0.51%   |
| Medion                  | 265      | 0.44%   |
| Toshiba                 | 236      | 0.4%    |
| Sceptre Tech            | 229      | 0.38%   |
| Panasonic               | 222      | 0.37%   |
| MSI                     | 175      | 0.29%   |
| Vestel Elektronik       | 143      | 0.24%   |
| Plain Tree Systems      | 143      | 0.24%   |
| Belinea                 | 143      | 0.24%   |
| Hitachi                 | 139      | 0.23%   |
| Packard Bell            | 137      | 0.23%   |
| ___                     | 130      | 0.22%   |
| Idek Iiyama             | 128      | 0.21%   |
| Sharp                   | 119      | 0.2%    |
| MStar                   | 103      | 0.17%   |
| Insignia                | 103      | 0.17%   |
| AUS                     | 97       | 0.16%   |
| Gateway                 | 95       | 0.16%   |
| Apple                   | 93       | 0.16%   |
| HKC                     | 83       | 0.14%   |
| HPN                     | 82       | 0.14%   |
| Gigabyte Technology     | 81       | 0.14%   |
| MiTAC                   | 79       | 0.13%   |
| Envision Peripherals    | 78       | 0.13%   |
| KTC                     | 72       | 0.12%   |
| RTK                     | 69       | 0.12%   |
| Lenovo Group Limited    | 69       | 0.12%   |
| CVT                     | 69       | 0.12%   |
| Unknown                 | 64       | 0.11%   |
| Chi Mei Optoelectronics | 63       | 0.11%   |
| OEM                     | 58       | 0.1%    |
| eMachines               | 56       | 0.09%   |
| IBM                     | 54       | 0.09%   |
| DENON                   | 52       | 0.09%   |
| Westinghouse            | 51       | 0.09%   |
| ONN                     | 51       | 0.09%   |
| Microstep               | 51       | 0.09%   |
| FUS                     | 51       | 0.09%   |
| Sanyo                   | 50       | 0.08%   |
| AGO                     | 50       | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 288      | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 240      | 0.38%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 189      | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 176      | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 172      | 0.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 164      | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 145      | 0.23%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 143      | 0.22%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 140      | 0.22%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 138      | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 137      | 0.22%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 132      | 0.21%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch   | 128      | 0.2%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 124      | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 121      | 0.19%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 116      | 0.18%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 110      | 0.17%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                     | 101      | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 99       | 0.16%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 98       | 0.15%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 97       | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 95       | 0.15%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 93       | 0.15%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 90       | 0.14%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 90       | 0.14%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch   | 89       | 0.14%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 89       | 0.14%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 89       | 0.14%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 89       | 0.14%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 89       | 0.14%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 87       | 0.14%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 83       | 0.13%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 79       | 0.12%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 78       | 0.12%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 77       | 0.12%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 76       | 0.12%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                       | 76       | 0.12%   |
| ___ LCDTV16 ___0101 1360x768                                           | 75       | 0.12%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 75       | 0.12%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                       | 75       | 0.12%   |
| AOC 1970W-1 AOC1970 1366x768 410x230mm 18.5-inch                       | 74       | 0.12%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 74       | 0.12%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 74       | 0.12%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 72       | 0.11%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                     | 72       | 0.11%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch               | 71       | 0.11%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                     | 70       | 0.11%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 69       | 0.11%   |
| Goldstar LG FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch              | 68       | 0.11%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                    | 67       | 0.11%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 66       | 0.1%    |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                     | 66       | 0.1%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 65       | 0.1%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 65       | 0.1%    |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 64       | 0.1%    |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch             | 64       | 0.1%    |
| Unknown                                                                | 64       | 0.1%    |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch      | 63       | 0.1%    |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 63       | 0.1%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 62       | 0.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24899    | 42.34%  |
| 1280x1024 (SXGA)   | 7004     | 11.91%  |
| 1680x1050 (WSXGA+) | 3764     | 6.4%    |
| 3840x2160 (4K)     | 3524     | 5.99%   |
| 2560x1440 (QHD)    | 2890     | 4.91%   |
| 1440x900 (WXGA+)   | 2619     | 4.45%   |
| 1366x768 (WXGA)    | 2582     | 4.39%   |
| 1600x900 (HD+)     | 1923     | 3.27%   |
| 1920x1200 (WUXGA)  | 1667     | 2.83%   |
| Unknown            | 1534     | 2.61%   |
| 1360x768           | 1136     | 1.93%   |
| 2560x1080          | 762      | 1.3%    |
| 1024x768 (XGA)     | 649      | 1.1%    |
| 3440x1440          | 611      | 1.04%   |
| 3840x1080          | 610      | 1.04%   |
| 1600x1200          | 393      | 0.67%   |
| 1920x540           | 333      | 0.57%   |
| 1280x720 (HD)      | 205      | 0.35%   |
| 2560x1600          | 96       | 0.16%   |
| 4480x1440          | 80       | 0.14%   |
| 2048x1152          | 72       | 0.12%   |
| 3840x1200          | 71       | 0.12%   |
| 1400x1050          | 67       | 0.11%   |
| 1280x960           | 65       | 0.11%   |
| 5760x1080          | 63       | 0.11%   |
| 3200x1080          | 63       | 0.11%   |
| 2288x1287          | 63       | 0.11%   |
| 1152x864           | 60       | 0.1%    |
| 3600x1080          | 55       | 0.09%   |
| 3840x1600          | 53       | 0.09%   |
| 5760x2160          | 52       | 0.09%   |
| 5120x1440          | 48       | 0.08%   |
| 7680x2160          | 41       | 0.07%   |
| 1280x768           | 37       | 0.06%   |
| 3360x1080          | 28       | 0.05%   |
| 2048x1536          | 27       | 0.05%   |
| 4480x1080          | 23       | 0.04%   |
| 3520x1080          | 23       | 0.04%   |
| 3286x1080          | 23       | 0.04%   |
| 2960x1050          | 19       | 0.03%   |
| 3360x1050          | 18       | 0.03%   |
| 1920x1440          | 18       | 0.03%   |
| 6400x2160          | 17       | 0.03%   |
| 2560x1024          | 17       | 0.03%   |
| 1280x800 (WXGA)    | 17       | 0.03%   |
| 2160x1200          | 16       | 0.03%   |
| 6400x1440          | 12       | 0.02%   |
| 5120x1080          | 12       | 0.02%   |
| 3280x1080          | 12       | 0.02%   |
| 5360x1440          | 11       | 0.02%   |
| 3200x900           | 11       | 0.02%   |
| 3200x1200          | 10       | 0.02%   |
| 5760x1200          | 9        | 0.02%   |
| 4240x1440          | 9        | 0.02%   |
| 2944x1080          | 9        | 0.02%   |
| 2880x1800          | 9        | 0.02%   |
| 6400x1080          | 8        | 0.01%   |
| 2720x1024          | 8        | 0.01%   |
| 7680x1440          | 7        | 0.01%   |
| 5520x2160          | 7        | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 6976     | 11.73%  |
| 21      | 6975     | 11.73%  |
| 24      | 6588     | 11.08%  |
| Unknown | 6318     | 10.63%  |
| 27      | 6135     | 10.32%  |
| 19      | 5569     | 9.37%   |
| 17      | 3491     | 5.87%   |
| 18      | 2935     | 4.94%   |
| 22      | 2511     | 4.22%   |
| 20      | 2425     | 4.08%   |
| 31      | 1577     | 2.65%   |
| 15      | 1270     | 2.14%   |
| 34      | 1109     | 1.87%   |
| 84      | 613      | 1.03%   |
| 72      | 587      | 0.99%   |
| 32      | 514      | 0.86%   |
| 40      | 453      | 0.76%   |
| 54      | 419      | 0.7%    |
| 25      | 389      | 0.65%   |
| 26      | 220      | 0.37%   |
| 16      | 163      | 0.27%   |
| 52      | 158      | 0.27%   |
| 48      | 158      | 0.27%   |
| 28      | 150      | 0.25%   |
| 49      | 133      | 0.22%   |
| 42      | 116      | 0.2%    |
| 65      | 114      | 0.19%   |
| 46      | 110      | 0.19%   |
| 37      | 108      | 0.18%   |
| 29      | 94       | 0.16%   |
| 39      | 92       | 0.15%   |
| 33      | 91       | 0.15%   |
| 14      | 82       | 0.14%   |
| 12      | 78       | 0.13%   |
| 43      | 77       | 0.13%   |
| 13      | 71       | 0.12%   |
| 47      | 68       | 0.11%   |
| 55      | 59       | 0.1%    |
| 35      | 53       | 0.09%   |
| 74      | 42       | 0.07%   |
| 142     | 39       | 0.07%   |
| 41      | 36       | 0.06%   |
| 60      | 33       | 0.06%   |
| 36      | 32       | 0.05%   |
| 30      | 31       | 0.05%   |
| 50      | 30       | 0.05%   |
| 38      | 30       | 0.05%   |
| 57      | 18       | 0.03%   |
| 44      | 18       | 0.03%   |
| 64      | 17       | 0.03%   |
| 69      | 13       | 0.02%   |
| 11      | 12       | 0.02%   |
| 59      | 9        | 0.02%   |
| 10      | 8        | 0.01%   |
| 75      | 7        | 0.01%   |
| 99      | 4        | 0.01%   |
| 63      | 4        | 0.01%   |
| 61      | 4        | 0.01%   |
| 8       | 4        | 0.01%   |
| 7       | 3        | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 18294    | 31.61%  |
| 401-500        | 16751    | 28.95%  |
| Unknown        | 6318     | 10.92%  |
| 301-350        | 4632     | 8%      |
| 351-400        | 3763     | 6.5%    |
| 601-700        | 2515     | 4.35%   |
| 701-800        | 1729     | 2.99%   |
| 1001-1500      | 1336     | 2.31%   |
| 1501-2000      | 1262     | 2.18%   |
| 801-900        | 703      | 1.21%   |
| 901-1000       | 276      | 0.48%   |
| 201-300        | 231      | 0.4%    |
| More than 2000 | 46       | 0.08%   |
| 101-200        | 7        | 0.01%   |
| 1-100          | 3        | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 32302    | 57.7%   |
| 16/10   | 7744     | 13.83%  |
| 5/4     | 6485     | 11.58%  |
| Unknown | 5560     | 9.93%   |
| 4/3     | 1666     | 2.98%   |
| 21/9    | 1303     | 2.33%   |
| 3/2     | 399      | 0.71%   |
| 6/5     | 214      | 0.38%   |
| 32/9    | 207      | 0.37%   |
| 1.00    | 46       | 0.08%   |
| 1.96    | 34       | 0.06%   |
| 3.20    | 7        | 0.01%   |
| 11/10   | 4        | 0.01%   |
| 2.00    | 3        | 0.01%   |
| 0.80    | 2        | 0.004%  |
| 3.76    | 1        | 0.002%  |
| 2.01    | 1        | 0.002%  |
| 1.98    | 1        | 0.002%  |
| 0.75    | 1        | 0.002%  |
| 0.57    | 1        | 0.002%  |
| 0.56    | 1        | 0.002%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18608    | 31.83%  |
| 151-200        | 10267    | 17.56%  |
| Unknown        | 6318     | 10.81%  |
| 301-350        | 6257     | 10.7%   |
| 141-150        | 5507     | 9.42%   |
| 351-500        | 3428     | 5.86%   |
| 251-300        | 2607     | 4.46%   |
| More than 1000 | 2297     | 3.93%   |
| 501-1000       | 1310     | 2.24%   |
| 101-110        | 944      | 1.61%   |
| 111-120        | 360      | 0.62%   |
| 131-140        | 215      | 0.37%   |
| 121-130        | 97       | 0.17%   |
| 71-80          | 83       | 0.14%   |
| 91-100         | 69       | 0.12%   |
| 81-90          | 61       | 0.1%    |
| 51-60          | 13       | 0.02%   |
| 1-40           | 10       | 0.02%   |
| 41-50          | 7        | 0.01%   |
| 61-70          | 5        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 35468    | 63.24%  |
| 101-120       | 9821     | 17.51%  |
| Unknown       | 6319     | 11.27%  |
| 1-50          | 2285     | 4.07%   |
| 121-160       | 1458     | 2.6%    |
| 161-240       | 721      | 1.29%   |
| More than 240 | 9        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47084    | 80.19%  |
| 2     | 7515     | 12.8%   |
| 0     | 3210     | 5.47%   |
| 3     | 811      | 1.38%   |
| 4     | 87       | 0.15%   |
| 5     | 8        | 0.01%   |
| 6     | 1        | 0.002%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 35259    | 44.41%  |
| Intel                                  | 18446    | 23.23%  |
| Qualcomm Atheros                       | 6295     | 7.93%   |
| Nvidia                                 | 2496     | 3.14%   |
| Broadcom                               | 2418     | 3.05%   |
| Ralink Technology                      | 2304     | 2.9%    |
| Ralink                                 | 1145     | 1.44%   |
| TP-Link                                | 1123     | 1.41%   |
| Marvell Technology Group               | 920      | 1.16%   |
| Qualcomm Atheros Communications        | 716      | 0.9%    |
| Broadcom Limited                       | 577      | 0.73%   |
| VIA Technologies                       | 551      | 0.69%   |
| D-Link System                          | 537      | 0.68%   |
| Huawei Technologies                    | 517      | 0.65%   |
| D-Link                                 | 484      | 0.61%   |
| NetGear                                | 425      | 0.54%   |
| ASUSTek Computer                       | 385      | 0.48%   |
| Samsung Electronics                    | 380      | 0.48%   |
| Microsoft                              | 369      | 0.46%   |
| Aquantia                               | 266      | 0.34%   |
| Xiaomi                                 | 227      | 0.29%   |
| MediaTek                               | 213      | 0.27%   |
| Edimax Technology                      | 190      | 0.24%   |
| Belkin Components                      | 168      | 0.21%   |
| ASIX Electronics                       | 157      | 0.2%    |
| Linksys                                | 150      | 0.19%   |
| IMC Networks                           | 129      | 0.16%   |
| ZTE WCDMA Technologies MSM             | 115      | 0.14%   |
| 3Com                                   | 109      | 0.14%   |
| Silicon Integrated Systems [SiS]       | 99       | 0.12%   |
| Sundance Technology Inc / IC Plus      | 96       | 0.12%   |
| Motorola PCS                           | 96       | 0.12%   |
| AVM                                    | 76       | 0.1%    |
| Realtek                                | 73       | 0.09%   |
| Gemtek                                 | 71       | 0.09%   |
| Qualcomm                               | 62       | 0.08%   |
| DisplayLink                            | 59       | 0.07%   |
| Mellanox Technologies                  | 55       | 0.07%   |
| Arduino SA                             | 55       | 0.07%   |
| HTC (High Tech Computer)               | 49       | 0.06%   |
| Sitecom Europe                         | 48       | 0.06%   |
| Microchip Technology                   | 48       | 0.06%   |
| Google                                 | 45       | 0.06%   |
| ZyXEL Communications                   | 44       | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 44       | 0.06%   |
| ZyDAS                                  | 41       | 0.05%   |
| JMicron Technology                     | 40       | 0.05%   |
| InterBiometrics                        | 40       | 0.05%   |
| Apple                                  | 39       | 0.05%   |
| realme                                 | 35       | 0.04%   |
| Accton Technology                      | 32       | 0.04%   |
| Texas Instruments                      | 31       | 0.04%   |
| Motorola                               | 30       | 0.04%   |
| Mercucys                               | 30       | 0.04%   |
| ADMtek                                 | 30       | 0.04%   |
| Sony Ericsson Mobile Communications AB | 28       | 0.04%   |
| LSI                                    | 27       | 0.03%   |
| BUFFALO                                | 27       | 0.03%   |
| OnePlus Technology (Shenzhen)          | 26       | 0.03%   |
| Micro Star International               | 25       | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28704    | 32.74%  |
| Intel I211 Gigabit Network Connection                             | 2849     | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1961     | 2.24%   |
| Intel Ethernet Connection (2) I219-V                              | 1923     | 2.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1767     | 2.02%   |
| Intel Wi-Fi 6 AX200                                               | 1763     | 2.01%   |
| Nvidia MCP61 Ethernet                                             | 1378     | 1.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1232     | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1187     | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 1080     | 1.23%   |
| Ralink MT7601U Wireless Adapter                                   | 973      | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 968      | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 846      | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 800      | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 762      | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 736      | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 639      | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 619      | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 615      | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                   | 597      | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 571      | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 541      | 0.62%   |
| Intel Wireless-AC 9260                                            | 538      | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 473      | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 472      | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 470      | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 466      | 0.53%   |
| Ralink RT5370 Wireless Adapter                                    | 442      | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 433      | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 400      | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 396      | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 396      | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 388      | 0.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 388      | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 375      | 0.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 368      | 0.42%   |
| Realtek 802.11ac NIC                                              | 357      | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 356      | 0.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 337      | 0.38%   |
| Intel I210 Gigabit Network Connection                             | 307      | 0.35%   |
| Intel Wireless 7260                                               | 304      | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 299      | 0.34%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 293      | 0.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 270      | 0.31%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 267      | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 265      | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 265      | 0.3%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 264      | 0.3%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 261      | 0.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 259      | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 259      | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 257      | 0.29%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 251      | 0.29%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 238      | 0.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 238      | 0.27%   |
| Intel Wireless 8260                                               | 226      | 0.26%   |
| Intel Wireless 3165                                               | 226      | 0.26%   |
| Nvidia MCP77 Ethernet                                             | 216      | 0.25%   |
| Intel 82578DM Gigabit Network Connection                          | 215      | 0.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 214      | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 5288     | 23.16%  |
| Realtek Semiconductor                 | 5065     | 22.18%  |
| Qualcomm Atheros                      | 2787     | 12.2%   |
| Ralink Technology                     | 2304     | 10.09%  |
| Ralink                                | 1144     | 5.01%   |
| TP-Link                               | 1095     | 4.79%   |
| Broadcom                              | 958      | 4.19%   |
| Qualcomm Atheros Communications       | 716      | 3.14%   |
| D-Link                                | 469      | 2.05%   |
| NetGear                               | 419      | 1.83%   |
| ASUSTek Computer                      | 369      | 1.62%   |
| Microsoft                             | 363      | 1.59%   |
| D-Link System                         | 301      | 1.32%   |
| Edimax Technology                     | 190      | 0.83%   |
| Belkin Components                     | 164      | 0.72%   |
| Linksys                               | 143      | 0.63%   |
| IMC Networks                          | 129      | 0.56%   |
| Broadcom Limited                      | 123      | 0.54%   |
| MediaTek                              | 96       | 0.42%   |
| AVM                                   | 76       | 0.33%   |
| Realtek                               | 73       | 0.32%   |
| Gemtek                                | 52       | 0.23%   |
| Sitecom Europe                        | 48       | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 44       | 0.19%   |
| ZyXEL Communications                  | 40       | 0.18%   |
| ZyDAS                                 | 40       | 0.18%   |
| Marvell Technology Group              | 31       | 0.14%   |
| Mercucys                              | 30       | 0.13%   |
| BUFFALO                               | 27       | 0.12%   |
| Micro Star International              | 25       | 0.11%   |
| Wilocity                              | 24       | 0.11%   |
| TRENDnet                              | 17       | 0.07%   |
| Texas Instruments                     | 17       | 0.07%   |
| Wacom                                 | 14       | 0.06%   |
| Accton Technology                     | 14       | 0.06%   |
| Tenda                                 | 13       | 0.06%   |
| Xiaomi                                | 12       | 0.05%   |
| Guillemot                             | 10       | 0.04%   |
| AboCom Systems                        | 10       | 0.04%   |
| PLANEX                                | 9        | 0.04%   |
| Samsung Electronics                   | 7        | 0.03%   |
| Sagem                                 | 7        | 0.03%   |
| Philips (or NXP)                      | 6        | 0.03%   |
| VIA Technologies                      | 5        | 0.02%   |
| Fujitsu Siemens Computers             | 5        | 0.02%   |
| Senao                                 | 4        | 0.02%   |
| Panasonic (Matsushita)                | 4        | 0.02%   |
| Toshiba                               | 3        | 0.01%   |
| Elecom                                | 3        | 0.01%   |
| CyberTAN Technology                   | 3        | 0.01%   |
| Chu Yuen Enterprise                   | 3        | 0.01%   |
| Belkin                                | 3        | 0.01%   |
| Apple                                 | 3        | 0.01%   |
| Z-Com                                 | 2        | 0.01%   |
| Sierra Wireless                       | 2        | 0.01%   |
| Logitec                               | 2        | 0.01%   |
| Intersil                              | 2        | 0.01%   |
| Hawking Technologies                  | 2        | 0.01%   |
| Fiberline                             | 2        | 0.01%   |
| Encore Electronics                    | 2        | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 1763     | 7.61%   |
| Ralink MT7601U Wireless Adapter                                | 973      | 4.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 800      | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 762      | 3.29%   |
| Qualcomm Atheros AR9271 802.11n                                | 597      | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 571      | 2.46%   |
| Intel Wireless-AC 9260                                         | 538      | 2.32%   |
| Ralink RT5370 Wireless Adapter                                 | 442      | 1.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 433      | 1.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 388      | 1.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 368      | 1.59%   |
| Realtek 802.11ac NIC                                           | 357      | 1.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 356      | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 337      | 1.45%   |
| Intel Wireless 7260                                            | 304      | 1.31%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 293      | 1.26%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 270      | 1.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 267      | 1.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 264      | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 261      | 1.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 238      | 1.03%   |
| Intel Wireless 8260                                            | 226      | 0.98%   |
| Intel Wireless 3165                                            | 226      | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 214      | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 206      | 0.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 205      | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 197      | 0.85%   |
| Microsoft Xbox 360 Wireless Adapter                            | 193      | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 190      | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 189      | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 188      | 0.81%   |
| Intel Wireless 7265                                            | 187      | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 183      | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 178      | 0.77%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 176      | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 173      | 0.75%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 172      | 0.74%   |
| Intel Wireless 8265 / 8275                                     | 171      | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 170      | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 167      | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 164      | 0.71%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 160      | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 159      | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 143      | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 134      | 0.58%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 132      | 0.57%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 122      | 0.53%   |
| Realtek RTL8187 Wireless Adapter                               | 121      | 0.52%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 118      | 0.51%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 118      | 0.51%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 115      | 0.5%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 113      | 0.49%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 112      | 0.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 112      | 0.48%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 112      | 0.48%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 107      | 0.46%   |
| Ralink RT5572 Wireless Adapter                                 | 107      | 0.46%   |
| Ralink RT5372 Wireless Adapter                                 | 106      | 0.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 105      | 0.45%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 101      | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 33257    | 53.88%  |
| Intel                                  | 15875    | 25.72%  |
| Qualcomm Atheros                       | 3771     | 6.11%   |
| Nvidia                                 | 2496     | 4.04%   |
| Broadcom                               | 1501     | 2.43%   |
| Marvell Technology Group               | 891      | 1.44%   |
| VIA Technologies                       | 533      | 0.86%   |
| Broadcom Limited                       | 455      | 0.74%   |
| Samsung Electronics                    | 370      | 0.6%    |
| Aquantia                               | 266      | 0.43%   |
| D-Link System                          | 237      | 0.38%   |
| Huawei Technologies                    | 224      | 0.36%   |
| Xiaomi                                 | 215      | 0.35%   |
| ASIX Electronics                       | 157      | 0.25%   |
| MediaTek                               | 113      | 0.18%   |
| 3Com                                   | 108      | 0.17%   |
| ZTE WCDMA Technologies MSM             | 105      | 0.17%   |
| Silicon Integrated Systems [SiS]       | 97       | 0.16%   |
| Sundance Technology Inc / IC Plus      | 96       | 0.16%   |
| Motorola PCS                           | 60       | 0.1%    |
| DisplayLink                            | 59       | 0.1%    |
| Qualcomm                               | 56       | 0.09%   |
| HTC (High Tech Computer)               | 49       | 0.08%   |
| Mellanox Technologies                  | 43       | 0.07%   |
| JMicron Technology                     | 40       | 0.06%   |
| realme                                 | 35       | 0.06%   |
| Apple                                  | 35       | 0.06%   |
| Google                                 | 34       | 0.06%   |
| TP-Link                                | 30       | 0.05%   |
| ADMtek                                 | 29       | 0.05%   |
| Sony Ericsson Mobile Communications AB | 27       | 0.04%   |
| HMD Global                             | 25       | 0.04%   |
| ICS Advent                             | 24       | 0.04%   |
| T & A Mobile Phones                    | 20       | 0.03%   |
| LG Electronics                         | 20       | 0.03%   |
| Gemtek                                 | 19       | 0.03%   |
| Spreadtrum Communications              | 18       | 0.03%   |
| Accton Technology                      | 18       | 0.03%   |
| OnePlus Technology (Shenzhen)          | 17       | 0.03%   |
| Lenovo                                 | 17       | 0.03%   |
| ASUSTek Computer                       | 16       | 0.03%   |
| D-Link                                 | 15       | 0.02%   |
| Davicom Semiconductor                  | 14       | 0.02%   |
| ULi Electronics                        | 13       | 0.02%   |
| GCT Semiconductor                      | 12       | 0.02%   |
| American Megatrends                    | 11       | 0.02%   |
| QLogic                                 | 10       | 0.02%   |
| Emulex                                 | 9        | 0.01%   |
| Tehuti Networks                        | 8        | 0.01%   |
| Solarflare Communications              | 8        | 0.01%   |
| NetXen Incorporated                    | 8        | 0.01%   |
| Netchip Technology                     | 8        | 0.01%   |
| National Semiconductor                 | 8        | 0.01%   |
| NetGear                                | 7        | 0.01%   |
| Linksys                                | 7        | 0.01%   |
| IBM                                    | 6        | 0.01%   |
| Hangzhou Silan Microelectronics        | 6        | 0.01%   |
| Foxconn / Hon Hai                      | 6        | 0.01%   |
| AMD                                    | 6        | 0.01%   |
| Vimtron Electronics                    | 5        | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28704    | 45.2%   |
| Intel I211 Gigabit Network Connection                             | 2849     | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1961     | 3.09%   |
| Intel Ethernet Connection (2) I219-V                              | 1923     | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1767     | 2.78%   |
| Nvidia MCP61 Ethernet                                             | 1378     | 2.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1232     | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1186     | 1.87%   |
| Intel 82579V Gigabit Network Connection                           | 1073     | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 968      | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 846      | 1.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 736      | 1.16%   |
| Intel Ethernet Connection (2) I218-V                              | 639      | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 619      | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 615      | 0.97%   |
| Intel 82574L Gigabit Network Connection                           | 541      | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 473      | 0.74%   |
| Intel Ethernet Controller I225-V                                  | 472      | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 470      | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 466      | 0.73%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 400      | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 396      | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 396      | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 388      | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 375      | 0.59%   |
| Intel I210 Gigabit Network Connection                             | 307      | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 299      | 0.47%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 265      | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 265      | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 259      | 0.41%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 259      | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 257      | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 251      | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 238      | 0.37%   |
| Nvidia MCP77 Ethernet                                             | 216      | 0.34%   |
| Intel 82578DM Gigabit Network Connection                          | 215      | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 214      | 0.34%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 210      | 0.33%   |
| Nvidia MCP55 Ethernet                                             | 197      | 0.31%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 193      | 0.3%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 190      | 0.3%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 184      | 0.29%   |
| Nvidia MCP51 Ethernet Controller                                  | 180      | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 177      | 0.28%   |
| Nvidia CK804 Ethernet Controller                                  | 176      | 0.28%   |
| Intel 82578DC Gigabit Network Connection                          | 176      | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 171      | 0.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 166      | 0.26%   |
| Intel Ethernet Connection (7) I219-LM                             | 156      | 0.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 151      | 0.24%   |
| Intel 82562V-2 10/100 Network Connection                          | 141      | 0.22%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 141      | 0.22%   |
| Nvidia MCP73 Ethernet                                             | 128      | 0.2%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 128      | 0.2%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 121      | 0.19%   |
| Huawei JAT-LX1                                                    | 116      | 0.18%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 115      | 0.18%   |
| Intel 82567V-2 Gigabit Network Connection                         | 113      | 0.18%   |
| Intel NM10/ICH7 Family LAN Controller                             | 111      | 0.17%   |
| Intel Ethernet Connection (14) I219-V                             | 111      | 0.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56815    | 71.94%  |
| WiFi     | 21201    | 26.84%  |
| Modem    | 793      | 1%      |
| Unknown  | 172      | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49287    | 76.79%  |
| WiFi     | 14859    | 23.15%  |
| Unknown  | 33       | 0.05%   |
| Modem    | 5        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41050    | 70.86%  |
| 2     | 14150    | 24.43%  |
| 3     | 1773     | 3.06%   |
| 0     | 512      | 0.88%   |
| 4     | 268      | 0.46%   |
| 5     | 99       | 0.17%   |
| 6     | 48       | 0.08%   |
| 7     | 8        | 0.01%   |
| 8     | 7        | 0.01%   |
| 18    | 3        | 0.01%   |
| 13    | 3        | 0.01%   |
| 9     | 3        | 0.01%   |
| 10    | 2        | 0.003%  |
| 33    | 1        | 0.002%  |
| 32    | 1        | 0.002%  |
| 21    | 1        | 0.002%  |
| 17    | 1        | 0.002%  |
| 12    | 1        | 0.002%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 48860    | 82.87%  |
| Yes     | 6031     | 10.23%  |
| Unknown | 4066     | 6.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4793     | 36.29%  |
| Cambridge Silicon Radio         | 4025     | 30.47%  |
| ASUSTek Computer                | 1016     | 7.69%   |
| Broadcom                        | 912      | 6.9%    |
| Realtek Semiconductor           | 711      | 5.38%   |
| Qualcomm Atheros Communications | 578      | 4.38%   |
| Apple                           | 204      | 1.54%   |
| IMC Networks                    | 202      | 1.53%   |
| Integrated System Solution      | 135      | 1.02%   |
| Lite-On Technology              | 88       | 0.67%   |
| Belkin Components               | 68       | 0.51%   |
| Dynex                           | 64       | 0.48%   |
| HTC (High Tech Computer)        | 44       | 0.33%   |
| Micro Star International        | 37       | 0.28%   |
| Dell                            | 31       | 0.23%   |
| Ralink                          | 30       | 0.23%   |
| Conwise Technology              | 30       | 0.23%   |
| Logitech                        | 28       | 0.21%   |
| Hewlett-Packard                 | 28       | 0.21%   |
| Edimax Technology               | 27       | 0.2%    |
| MediaTek                        | 23       | 0.17%   |
| Foxconn / Hon Hai               | 14       | 0.11%   |
| TP-Link                         | 13       | 0.1%    |
| Roper                           | 13       | 0.1%    |
| Realtek                         | 11       | 0.08%   |
| Primax Electronics              | 10       | 0.08%   |
| Toshiba                         | 8        | 0.06%   |
| D-Link System                   | 8        | 0.06%   |
| Unknown                         | 5        | 0.04%   |
| Kensington                      | 5        | 0.04%   |
| D-Link                          | 5        | 0.04%   |
| Creative Technology             | 5        | 0.04%   |
| Unknown                         | 4        | 0.03%   |
| Sitecom Europe                  | 3        | 0.02%   |
| Qcom                            | 3        | 0.02%   |
| Motorola PCS                    | 3        | 0.02%   |
| Mobile Action Technology        | 3        | 0.02%   |
| Fujitsu                         | 3        | 0.02%   |
| TRENDnet                        | 2        | 0.02%   |
| SINO WEALTH                     | 2        | 0.02%   |
| Fujitsu Siemens Computers       | 2        | 0.02%   |
| Zeevo                           | 1        | 0.01%   |
| Taiyo Yuden                     | 1        | 0.01%   |
| Ralink Technology               | 1        | 0.01%   |
| National Semiconductor          | 1        | 0.01%   |
| Microsoft                       | 1        | 0.01%   |
| Marvell Semiconductor           | 1        | 0.01%   |
| i.Tech Dynamic Limited          | 1        | 0.01%   |
| Cypress Semiconductor           | 1        | 0.01%   |
| Corsair                         | 1        | 0.01%   |
| Com One                         | 1        | 0.01%   |
| AVM                             | 1        | 0.01%   |
| AboCom Systems                  | 1        | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4024     | 30.41%  |
| Intel AX200 Bluetooth                                                | 1628     | 12.3%   |
| Intel Bluetooth wireless interface                                   | 1116     | 8.43%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 738      | 5.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 518      | 3.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 511      | 3.86%   |
| Realtek Bluetooth Radio                                              | 473      | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 386      | 2.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 377      | 2.85%   |
| Intel Bluetooth Device                                               | 214      | 1.62%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 182      | 1.38%   |
| Qualcomm Atheros  Bluetooth Device                                   | 174      | 1.32%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 165      | 1.25%   |
| ASUS Bluetooth Radio                                                 | 157      | 1.19%   |
| Intel AX210 Bluetooth                                                | 126      | 0.95%   |
| ASUS BCM20702A0                                                      | 112      | 0.85%   |
| IMC Networks Bluetooth Radio                                         | 110      | 0.83%   |
| ASUS Bluetooth Adapter                                               | 105      | 0.79%   |
| Apple Bluetooth USB Host Controller                                  | 92       | 0.7%    |
| ASUS Qualcomm Bluetooth 4.1                                          | 89       | 0.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 78       | 0.59%   |
| Integrated System Solution Bluetooth Device                          | 75       | 0.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 73       | 0.55%   |
| Lite-On Bluetooth Device                                             | 68       | 0.51%   |
| Broadcom BCM2045 Bluetooth                                           | 68       | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 67       | 0.51%   |
| Dynex BCM20702A0                                                     | 64       | 0.48%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 60       | 0.45%   |
| ASUS Bluetooth Device                                                | 59       | 0.45%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 57       | 0.43%   |
| ASUS ASUS USB-BT500                                                  | 55       | 0.42%   |
| Realtek RTL8821A Bluetooth                                           | 50       | 0.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 50       | 0.38%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 44       | 0.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 42       | 0.32%   |
| Apple Bluetooth HCI                                                  | 41       | 0.31%   |
| IMC Networks Bluetooth Device                                        | 40       | 0.3%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 38       | 0.29%   |
| Ralink RT3290 Bluetooth                                              | 30       | 0.23%   |
| Conwise CW6622                                                       | 30       | 0.23%   |
| Micro Star International Bluetooth Device                            | 29       | 0.22%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 29       | 0.22%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 27       | 0.2%    |
| Logitech BT Mini-Receiver (HCI mode)                                 | 26       | 0.2%    |
| Broadcom Bluetooth 3.0 Device                                        | 24       | 0.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 23       | 0.17%   |
| MediaTek Wireless_Device                                             | 23       | 0.17%   |
| IMC Networks BCM20702A0                                              | 23       | 0.17%   |
| Broadcom HP Portable Bumble Bee                                      | 23       | 0.17%   |
| Belkin Components Bluetooth Mini Dongle                              | 22       | 0.17%   |
| Broadcom BCM92045B3 ROM                                              | 21       | 0.16%   |
| IMC Networks Bluetooth Module                                        | 20       | 0.15%   |
| Broadcom Bluetooth 2.0+EDR dongle                                    | 20       | 0.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 19       | 0.14%   |
| Broadcom HP Bluethunder                                              | 19       | 0.14%   |
| Dell BT Mini-Receiver                                                | 16       | 0.12%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                    | 16       | 0.12%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 15       | 0.11%   |
| Broadcom Bluetooth 3.0 Dongle                                        | 15       | 0.11%   |
| Apple Bluetooth Host Controller                                      | 14       | 0.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 34946    | 37.43%  |
| AMD                                             | 23693    | 25.37%  |
| Nvidia                                          | 23104    | 24.74%  |
| C-Media Electronics                             | 2404     | 2.57%   |
| Creative Labs                                   | 1469     | 1.57%   |
| Logitech                                        | 825      | 0.88%   |
| VIA Technologies                                | 519      | 0.56%   |
| Texas Instruments                               | 425      | 0.46%   |
| JMTek                                           | 359      | 0.38%   |
| Creative Technology                             | 319      | 0.34%   |
| Kingston Technology                             | 270      | 0.29%   |
| Corsair                                         | 251      | 0.27%   |
| Generalplus Technology                          | 243      | 0.26%   |
| Focusrite-Novation                              | 236      | 0.25%   |
| Razer USA                                       | 202      | 0.22%   |
| SteelSeries ApS                                 | 198      | 0.21%   |
| Plantronics                                     | 188      | 0.2%    |
| GN Netcom                                       | 184      | 0.2%    |
| ASUSTek Computer                                | 183      | 0.2%    |
| Blue Microphones                                | 157      | 0.17%   |
| Silicon Integrated Systems [SiS]                | 130      | 0.14%   |
| Tenx Technology                                 | 123      | 0.13%   |
| Sennheiser Communications                       | 118      | 0.13%   |
| M-Audio                                         | 92       | 0.1%    |
| Yamaha                                          | 91       | 0.1%    |
| BEHRINGER International                         | 90       | 0.1%    |
| GYROCOM C&C                                     | 89       | 0.1%    |
| Samson Technologies                             | 85       | 0.09%   |
| Sony                                            | 77       | 0.08%   |
| Realtek Semiconductor                           | 77       | 0.08%   |
| Dell                                            | 77       | 0.08%   |
| Ensoniq                                         | 69       | 0.07%   |
| XMOS                                            | 59       | 0.06%   |
| SAVITECH                                        | 57       | 0.06%   |
| Microsoft                                       | 56       | 0.06%   |
| RODE Microphones                                | 55       | 0.06%   |
| Giga-Byte Technology                            | 53       | 0.06%   |
| Unknown                                         | 47       | 0.05%   |
| Licensed by Sony Computer Entertainment America | 46       | 0.05%   |
| Turtle Beach                                    | 43       | 0.05%   |
| Thesycon Systemsoftware & Consulting            | 42       | 0.04%   |
| Cambridge Silicon Radio                         | 41       | 0.04%   |
| Astro Gaming                                    | 40       | 0.04%   |
| Asahi Kasei Microsystems                        | 38       | 0.04%   |
| ATI Technologies                                | 36       | 0.04%   |
| Valve Software                                  | 35       | 0.04%   |
| Micro Star International                        | 34       | 0.04%   |
| AKAI Professional M.I.                          | 34       | 0.04%   |
| ULi Electronics                                 | 32       | 0.03%   |
| Audio-Technica                                  | 32       | 0.03%   |
| PreSonus Audio Electronics                      | 28       | 0.03%   |
| Hewlett-Packard                                 | 28       | 0.03%   |
| Bose                                            | 27       | 0.03%   |
| Native Instruments                              | 24       | 0.03%   |
| FiiO Electronics Technology                     | 24       | 0.03%   |
| ROCCAT                                          | 23       | 0.02%   |
| Guillemot                                       | 22       | 0.02%   |
| Syntek                                          | 21       | 0.02%   |
| Trust                                           | 20       | 0.02%   |
| Alesis                                          | 20       | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 5759     | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5055     | 4.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4494     | 4.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4230     | 3.93%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3709     | 3.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3237     | 3.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3010     | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2779     | 2.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2601     | 2.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2425     | 2.26%   |
| AMD FCH Azalia Controller                                                         | 2288     | 2.13%   |
| Intel 200 Series PCH HD Audio                                                     | 2207     | 2.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2062     | 1.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1907     | 1.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1854     | 1.72%   |
| Nvidia High Definition Audio Controller                                           | 1795     | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1774     | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1743     | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                        | 1589     | 1.48%   |
| Nvidia MCP61 High Definition Audio                                                | 1529     | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1508     | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1502     | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1453     | 1.35%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1269     | 1.18%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1225     | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1198     | 1.11%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1062     | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1032     | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1023     | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1013     | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                                | 958      | 0.89%   |
| AMD Navi 10 HDMI Audio                                                            | 919      | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 882      | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 834      | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                     | 824      | 0.77%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 797      | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                                | 748      | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                                     | 684      | 0.64%   |
| Nvidia GK106 HDMI Audio Controller                                                | 663      | 0.62%   |
| Nvidia GM206 High Definition Audio Controller                                     | 662      | 0.62%   |
| Nvidia GP108 High Definition Audio Controller                                     | 629      | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                     | 611      | 0.57%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 604      | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 600      | 0.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 588      | 0.55%   |
| AMD Trinity HDMI Audio Controller                                                 | 586      | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 577      | 0.54%   |
| Nvidia GF116 High Definition Audio Controller                                     | 573      | 0.53%   |
| Nvidia TU104 HD Audio Controller                                                  | 559      | 0.52%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 535      | 0.5%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 497      | 0.46%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 434      | 0.4%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 430      | 0.4%    |
| Nvidia GP102 HDMI Audio Controller                                                | 414      | 0.39%   |
| AMD Kabini HDMI/DP Audio                                                          | 387      | 0.36%   |
| Intel Comet Lake PCH-V cAVS                                                       | 356      | 0.33%   |
| Intel Comet Lake PCH cAVS                                                         | 355      | 0.33%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 345      | 0.32%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 337      | 0.31%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 331      | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 10756    | 29.07%  |
| Kingston            | 6472     | 17.49%  |
| Corsair             | 3527     | 9.53%   |
| Samsung Electronics | 2853     | 7.71%   |
| Crucial             | 2674     | 7.23%   |
| SK Hynix            | 2329     | 6.3%    |
| G.Skill             | 2188     | 5.91%   |
| Micron Technology   | 1202     | 3.25%   |
| Patriot             | 535      | 1.45%   |
| A-DATA Technology   | 506      | 1.37%   |
| Nanya Technology    | 433      | 1.17%   |
| Team                | 342      | 0.92%   |
| Elpida              | 246      | 0.66%   |
| Transcend           | 223      | 0.6%    |
| AMD                 | 212      | 0.57%   |
| GOODRAM             | 204      | 0.55%   |
| Ramaxel Technology  | 193      | 0.52%   |
| Kingmax             | 150      | 0.41%   |
| Silicon Power       | 141      | 0.38%   |
| Apacer              | 115      | 0.31%   |
| GeIL                | 107      | 0.29%   |
| Unknown             | 95       | 0.26%   |
| Smart               | 88       | 0.24%   |
| Unifosa             | 68       | 0.18%   |
| Goldkey             | 66       | 0.18%   |
| Qumo                | 65       | 0.18%   |
| Qimonda             | 63       | 0.17%   |
| Unknown (ABCD)      | 57       | 0.15%   |
| PNY                 | 57       | 0.15%   |
| Kllisre             | 41       | 0.11%   |
| Avant               | 41       | 0.11%   |
| CSX                 | 36       | 0.1%    |
| KETECH              | 32       | 0.09%   |
| Foxline             | 32       | 0.09%   |
| OCZ                 | 29       | 0.08%   |
| Atermiter           | 27       | 0.07%   |
| ASint Technology    | 26       | 0.07%   |
| Ramos Technology    | 24       | 0.06%   |
| TakeMS              | 23       | 0.06%   |
| Neo Forza           | 22       | 0.06%   |
| Hikvision           | 22       | 0.06%   |
| Hewlett-Packard     | 22       | 0.06%   |
| Exceleram           | 22       | 0.06%   |
| Teikon              | 21       | 0.06%   |
| Multilaser          | 17       | 0.05%   |
| TwinMOS             | 16       | 0.04%   |
| Toshiba             | 16       | 0.04%   |
| Golden Empire       | 15       | 0.04%   |
| Klevv               | 14       | 0.04%   |
| Wilk Elektronik     | 13       | 0.04%   |
| Mushkin             | 13       | 0.04%   |
| Kreton              | 13       | 0.04%   |
| 48spaces            | 13       | 0.04%   |
| TIMETEC             | 12       | 0.03%   |
| Infineon            | 12       | 0.03%   |
| V-Color             | 11       | 0.03%   |
| Super Talent        | 11       | 0.03%   |
| Sesame              | 11       | 0.03%   |
| Axiom               | 11       | 0.03%   |
| HEXON               | 10       | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 624      | 1.48%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 597      | 1.42%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 559      | 1.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 552      | 1.31%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 506      | 1.2%    |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 483      | 1.15%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s              | 368      | 0.88%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 293      | 0.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 293      | 0.7%    |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 290      | 0.69%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 274      | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 272      | 0.65%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s   | 262      | 0.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s    | 225      | 0.54%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1867MT/s   | 224      | 0.53%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 205      | 0.49%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 202      | 0.48%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 198      | 0.47%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 182      | 0.43%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 169      | 0.4%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 167      | 0.4%    |
| Unknown RAM Module 1024MB DIMM                           | 164      | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s        | 164      | 0.39%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s   | 158      | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 151      | 0.36%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 149      | 0.35%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 146      | 0.35%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s     | 145      | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s              | 140      | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 139      | 0.33%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s | 138      | 0.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 136      | 0.32%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 136      | 0.32%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 135      | 0.32%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s | 133      | 0.32%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 129      | 0.31%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                  | 128      | 0.3%    |
| Unknown RAM Module 4096MB DIMM 400MT/s                   | 127      | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 126      | 0.3%    |
| Unknown RAM Module 2GB DIMM SDRAM                        | 125      | 0.3%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 123      | 0.29%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 123      | 0.29%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 122      | 0.29%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s      | 120      | 0.29%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 119      | 0.28%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s   | 112      | 0.27%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s              | 111      | 0.26%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM SDRAM 1867MT/s     | 109      | 0.26%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s | 109      | 0.26%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 108      | 0.26%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 108      | 0.26%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 107      | 0.25%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 106      | 0.25%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 105      | 0.25%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 104      | 0.25%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s              | 100      | 0.24%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 100      | 0.24%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 99       | 0.24%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 97       | 0.23%   |
| Unknown                                                  | 95       | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 11809    | 35.55%  |
| DDR4         | 10101    | 30.41%  |
| Unknown      | 4467     | 13.45%  |
| DDR2         | 3479     | 10.47%  |
| SDRAM        | 2448     | 7.37%   |
| DDR          | 797      | 2.4%    |
| LPDDR4       | 74       | 0.22%   |
| DRAM         | 38       | 0.11%   |
| LPDDR3       | 6        | 0.02%   |
| DDR2 FB-DIMM | 1        | 0.003%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| DIMM            | 31377    | 96.15%  |
| SODIMM          | 1126     | 3.45%   |
| FB-DIMM         | 62       | 0.19%   |
| RIMM            | 52       | 0.16%   |
| Unknown         | 8        | 0.02%   |
| Row Of Chips    | 5        | 0.02%   |
| Proprietary Car | 1        | 0.003%  |
| Chip            | 1        | 0.003%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 4096    | 9956     | 26.84%  |
| 8192    | 9749     | 26.28%  |
| 2048    | 8411     | 22.67%  |
| 1024    | 3923     | 10.58%  |
| 16384   | 3277     | 8.83%   |
| 512     | 896      | 2.42%   |
| 32768   | 659      | 1.78%   |
| 256     | 189      | 0.51%   |
| 128     | 10       | 0.03%   |
| 32      | 7        | 0.02%   |
| 16      | 6        | 0.02%   |
| 65536   | 4        | 0.01%   |
| 1536    | 3        | 0.01%   |
| 64      | 3        | 0.01%   |
| 3072    | 1        | 0.003%  |
| 13      | 1        | 0.003%  |
| Unknown | 1        | 0.003%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6661     | 18.4%   |
| 1333    | 5539     | 15.3%   |
| 800     | 3037     | 8.39%   |
| 3200    | 2211     | 6.11%   |
| Unknown | 2101     | 5.8%    |
| 2400    | 2050     | 5.66%   |
| 667     | 1904     | 5.26%   |
| 2133    | 1502     | 4.15%   |
| 3600    | 1360     | 3.76%   |
| 2667    | 1308     | 3.61%   |
| 1867    | 759      | 2.1%    |
| 400     | 643      | 1.78%   |
| 1066    | 565      | 1.56%   |
| 1866    | 555      | 1.53%   |
| 3000    | 500      | 1.38%   |
| 2933    | 464      | 1.28%   |
| 2666    | 443      | 1.22%   |
| 3466    | 418      | 1.15%   |
| 533     | 393      | 1.09%   |
| 1800    | 312      | 0.86%   |
| 333     | 296      | 0.82%   |
| 1067    | 251      | 0.69%   |
| 3400    | 216      | 0.6%    |
| 2800    | 174      | 0.48%   |
| 3733    | 172      | 0.48%   |
| 3533    | 157      | 0.43%   |
| 2048    | 131      | 0.36%   |
| 266     | 129      | 0.36%   |
| 3800    | 114      | 0.31%   |
| 2000    | 109      | 0.3%    |
| 1639    | 89       | 0.25%   |
| 49926   | 86       | 0.24%   |
| 1400    | 81       | 0.22%   |
| 1334    | 81       | 0.22%   |
| 2134    | 78       | 0.22%   |
| 3333    | 71       | 0.2%    |
| 3334    | 68       | 0.19%   |
| 2733    | 68       | 0.19%   |
| 3100    | 64       | 0.18%   |
| 3151    | 62       | 0.17%   |
| 66      | 60       | 0.17%   |
| 2200    | 57       | 0.16%   |
| 3866    | 52       | 0.14%   |
| 3500    | 48       | 0.13%   |
| 3066    | 48       | 0.13%   |
| 3266    | 47       | 0.13%   |
| 2465    | 45       | 0.12%   |
| 200     | 42       | 0.12%   |
| 4000    | 35       | 0.1%    |
| 3007    | 33       | 0.09%   |
| 3666    | 26       | 0.07%   |
| 3067    | 25       | 0.07%   |
| 2934    | 23       | 0.06%   |
| 4333    | 22       | 0.06%   |
| 1648    | 22       | 0.06%   |
| 2866    | 21       | 0.06%   |
| 133     | 21       | 0.06%   |
| 2747    | 18       | 0.05%   |
| 4199    | 15       | 0.04%   |
| 2187    | 14       | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Hewlett-Packard                    | 1385     | 35.5%   |
| Canon                              | 681      | 17.46%  |
| Brother Industries                 | 559      | 14.33%  |
| Samsung Electronics                | 503      | 12.89%  |
| Seiko Epson                        | 331      | 8.49%   |
| Xerox                              | 58       | 1.49%   |
| Prolific Technology                | 55       | 1.41%   |
| Kyocera                            | 40       | 1.03%   |
| QinHeng Electronics                | 35       | 0.9%    |
| Lexmark International              | 32       | 0.82%   |
| Dymo-CoStar                        | 31       | 0.79%   |
| Panasonic (Matsushita)             | 29       | 0.74%   |
| Ricoh                              | 25       | 0.64%   |
| Pantum                             | 25       | 0.64%   |
| Zebra                              | 15       | 0.38%   |
| Fuji Xerox                         | 11       | 0.28%   |
| Dell                               | 11       | 0.28%   |
| Oki Data                           | 10       | 0.26%   |
| STMicroelectronics                 | 7        | 0.18%   |
| Konica Minolta                     | 5        | 0.13%   |
| Apple                              | 5        | 0.13%   |
| TSC Auto ID Technology             | 4        | 0.1%    |
| WinChipHead                        | 3        | 0.08%   |
| Star Micronics                     | 3        | 0.08%   |
| Sharp                              | 3        | 0.08%   |
| Magic Control Technology           | 3        | 0.08%   |
| ATEN International                 | 3        | 0.08%   |
| Zhuhai Poskey Technology           | 2        | 0.05%   |
| Seiko Instruments                  | 2        | 0.05%   |
| NXP Semiconductors                 | 2        | 0.05%   |
| GODEX INTERNATIONAL                | 2        | 0.05%   |
| Custom Engineering SPA             | 2        | 0.05%   |
| Citizen                            | 2        | 0.05%   |
| cab Produkttechnik GmbH & Co KG    | 2        | 0.05%   |
| Yurex                              | 1        | 0.03%   |
| Toshiba TEC                        | 1        | 0.03%   |
| Sato                               | 1        | 0.03%   |
| Samsung Info. Systems America      | 1        | 0.03%   |
| MIIIW                              | 1        | 0.03%   |
| Kodak                              | 1        | 0.03%   |
| ICS Advent                         | 1        | 0.03%   |
| Datamax-O'Neil                     | 1        | 0.03%   |
| Coopaty                            | 1        | 0.03%   |
| Boca Systems                       | 1        | 0.03%   |
| Bixolon                            | 1        | 0.03%   |
| BeiJing LanXum Computer Technology | 1        | 0.03%   |
| ARGOX                              | 1        | 0.03%   |
| Agere Systems (Lucent)             | 1        | 0.03%   |
| Unknown                            | 1        | 0.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| HP LaserJet 1020                      | 83       | 2.1%    |
| HP LaserJet 1018                      | 56       | 1.42%   |
| Prolific PL2305 Parallel Port         | 55       | 1.39%   |
| HP DeskJet 2620 All-in-One Printer    | 50       | 1.27%   |
| Samsung SCX-4200 series               | 47       | 1.19%   |
| Brother Printer                       | 47       | 1.19%   |
| Seiko Epson Printer                   | 44       | 1.12%   |
| Samsung M2020 Series                  | 42       | 1.06%   |
| HP LaserJet P1102                     | 42       | 1.06%   |
| Samsung SCX-3400 Series               | 40       | 1.01%   |
| Canon LBP2900                         | 38       | 0.96%   |
| Samsung M2070 Series                  | 37       | 0.94%   |
| HP DeskJet 2130 series                | 37       | 0.94%   |
| QinHeng CH340S                        | 35       | 0.89%   |
| HP ENVY 4520 series                   | 34       | 0.86%   |
| HP LaserJet P1005                     | 33       | 0.84%   |
| Canon PIXMA MG2500 Series             | 33       | 0.84%   |
| Brother HL-2030 Laser Printer         | 33       | 0.84%   |
| Samsung ML-1640 Series Laser Printer  | 28       | 0.71%   |
| HP LaserJet 1010                      | 28       | 0.71%   |
| HP DeskJet 3630 series                | 26       | 0.66%   |
| Canon iP7200 series                   | 26       | 0.66%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 25       | 0.63%   |
| Samsung SCX-3200 Series               | 25       | 0.63%   |
| HP Deskjet 2540 series                | 25       | 0.63%   |
| HP Deskjet 2050 J510                  | 25       | 0.63%   |
| Canon PIXMA MX920 Series              | 25       | 0.63%   |
| Canon MF4410                          | 23       | 0.58%   |
| Samsung ML-216x Series Laser Printer  | 22       | 0.56%   |
| HP LaserJet Professional P 1102w      | 22       | 0.56%   |
| HP Deskjet 1050 J410                  | 21       | 0.53%   |
| Brother HL-1110 series                | 21       | 0.53%   |
| Panasonic (Matsushita) KX-MB1500CX    | 20       | 0.51%   |
| Canon MF3010                          | 20       | 0.51%   |
| HP LaserJet P1006                     | 19       | 0.48%   |
| Canon PIXMA MG3600 Series             | 19       | 0.48%   |
| Brother HL-2130 series                | 19       | 0.48%   |
| HP LaserJet 1200                      | 18       | 0.46%   |
| HP LaserJet 1022                      | 18       | 0.46%   |
| HP ENVY 5000 series                   | 18       | 0.46%   |
| HP DeskJet F4200 series               | 18       | 0.46%   |
| Canon MF4010 series                   | 18       | 0.46%   |
| Samsung ML-2010P Mono Laser Printer   | 17       | 0.43%   |
| HP OfficeJet 5200 series              | 17       | 0.43%   |
| HP LaserJet 1320                      | 17       | 0.43%   |
| HP LaserJet 1300                      | 17       | 0.43%   |
| HP Deskjet 3050 J610 series           | 17       | 0.43%   |
| Canon CanoScan LiDE 300               | 17       | 0.43%   |
| Samsung ML-1660 Series                | 16       | 0.41%   |
| Seiko Epson L210 Series               | 15       | 0.38%   |
| HP Officejet 4500 G510g-m             | 15       | 0.38%   |
| Canon LBP810                          | 15       | 0.38%   |
| Seiko Epson L120 Series               | 14       | 0.35%   |
| HP Printing Support                   | 14       | 0.35%   |
| HP LaserJet 1000                      | 14       | 0.35%   |
| HP DeskJet F4100 Printer series       | 14       | 0.35%   |
| HP DeskJet 3700 series                | 14       | 0.35%   |
| Canon PIXMA MP280                     | 14       | 0.35%   |
| Canon LBP6000                         | 14       | 0.35%   |
| Canon LaserShot LBP-1120 Printer      | 14       | 0.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 475      | 49.48%  |
| Seiko Epson                 | 207      | 21.56%  |
| Hewlett-Packard             | 143      | 14.9%   |
| Mustek Systems              | 62       | 6.46%   |
| Ultima Electronics          | 22       | 2.29%   |
| Acer Peripherals (now BenQ) | 17       | 1.77%   |
| AGFA-Gevaert NV             | 11       | 1.15%   |
| KYE Systems (Mouse Systems) | 6        | 0.63%   |
| Plustek                     | 4        | 0.42%   |
| Fujitsu                     | 3        | 0.31%   |
| UMAX                        | 2        | 0.21%   |
| Microtek International      | 2        | 0.21%   |
| Avision                     | 2        | 0.21%   |
| Visioneer                   | 1        | 0.1%    |
| Syscan                      | 1        | 0.1%    |
| Minolta                     | 1        | 0.1%    |
| Canon Electronics           | 1        | 0.1%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 74       | 7.68%   |
| Canon CanoScan LIDE 25                                                                | 67       | 6.96%   |
| Canon CanoScan LiDE 210                                                               | 59       | 6.13%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 47       | 4.88%   |
| Canon CanoScan LiDE 220                                                               | 40       | 4.15%   |
| Canon CanoScan LiDE 120                                                               | 36       | 3.74%   |
| HP ScanJet 2400c                                                                      | 29       | 3.01%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 26       | 2.7%    |
| Canon CanoScan LiDE 100                                                               | 23       | 2.39%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 20       | 2.08%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 20       | 2.08%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 19       | 1.97%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 18       | 1.87%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 17       | 1.77%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 15       | 1.56%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 14       | 1.45%   |
| Canon CanoScan LiDE 60                                                                | 14       | 1.45%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 14       | 1.45%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 12       | 1.25%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 11       | 1.14%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 11       | 1.14%   |
| Mustek Systems SNAPSCAN e22                                                           | 10       | 1.04%   |
| Canon CanoScan LiDE 700F                                                              | 10       | 1.04%   |
| Canon CanoScan LiDE 200                                                               | 10       | 1.04%   |
| HP ScanJet 3800c                                                                      | 8        | 0.83%   |
| Canon CanoScan LiDE 90                                                                | 8        | 0.83%   |
| Seiko Epson Scanner                                                                   | 7        | 0.73%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 7        | 0.73%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 7        | 0.73%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7        | 0.73%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 7        | 0.73%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 7        | 0.73%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 7        | 0.73%   |
| HP ScanJet 3970c                                                                      | 7        | 0.73%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 6        | 0.62%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 6        | 0.62%   |
| HP ScanJet 5590                                                                       | 6        | 0.62%   |
| HP PSC 1200                                                                           | 6        | 0.62%   |
| Canon CanoScan 9000F Mark II                                                          | 6        | 0.62%   |
| Canon CanoScan                                                                        | 6        | 0.62%   |
| Seiko Epson Perfection 660                                                            | 5        | 0.52%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 5        | 0.52%   |
| HP ScanJet G4050                                                                      | 5        | 0.52%   |
| HP ScanJet 82x0C                                                                      | 5        | 0.52%   |
| HP Scanjet 300                                                                        | 5        | 0.52%   |
| HP ScanJet 2200c                                                                      | 5        | 0.52%   |
| Canon CanoScan N650U/N656U                                                            | 5        | 0.52%   |
| Canon CanoScan LiDE 70                                                                | 5        | 0.52%   |
| Canon CanoScan LiDE 600F                                                              | 5        | 0.52%   |
| Canon CanoScan 4400F                                                                  | 5        | 0.52%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 5        | 0.52%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 4        | 0.42%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 4        | 0.42%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 4        | 0.42%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 4        | 0.42%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 4        | 0.42%   |
| HP ScanJet 3670                                                                       | 4        | 0.42%   |
| HP ScanJet 3400cse                                                                    | 4        | 0.42%   |
| HP Scanjet 200                                                                        | 4        | 0.42%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4        | 0.42%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 4073     | 37.9%   |
| Microdia                               | 849      | 7.9%    |
| Z-Star Microelectronics                | 806      | 7.5%    |
| Microsoft                              | 686      | 6.38%   |
| Samsung Electronics                    | 367      | 3.42%   |
| Apple                                  | 259      | 2.41%   |
| Chicony Electronics                    | 257      | 2.39%   |
| KYE Systems (Mouse Systems)            | 239      | 2.22%   |
| Cubeternet                             | 211      | 1.96%   |
| Sunplus Innovation Technology          | 204      | 1.9%    |
| GEMBIRD                                | 190      | 1.77%   |
| Creative Technology                    | 189      | 1.76%   |
| Generalplus Technology                 | 186      | 1.73%   |
| Realtek Semiconductor                  | 181      | 1.68%   |
| Aveo Technology                        | 181      | 1.68%   |
| Arkmicro Technologies                  | 158      | 1.47%   |
| Pixart Imaging                         | 132      | 1.23%   |
| ARC International                      | 105      | 0.98%   |
| Alcor Micro                            | 84       | 0.78%   |
| Hewlett-Packard                        | 78       | 0.73%   |
| MacroSilicon                           | 74       | 0.69%   |
| Jieli Technology                       | 68       | 0.63%   |
| Huawei Technologies                    | 60       | 0.56%   |
| Genesys Logic                          | 60       | 0.56%   |
| LG Electronics                         | 55       | 0.51%   |
| Trust                                  | 53       | 0.49%   |
| Razer USA                              | 45       | 0.42%   |
| Guillemot                              | 45       | 0.42%   |
| IMC Networks                           | 43       | 0.4%    |
| webcam                                 | 37       | 0.34%   |
| Philips (or NXP)                       | 36       | 0.34%   |
| Valve Software                         | 30       | 0.28%   |
| AVerMedia Technologies                 | 28       | 0.26%   |
| Unknown                                | 27       | 0.25%   |
| Sonix Technology                       | 26       | 0.24%   |
| Silicon Motion                         | 25       | 0.23%   |
| A4Tech                                 | 25       | 0.23%   |
| OmniVision Technologies                | 23       | 0.21%   |
| Novatek Microelectronics               | 21       | 0.2%    |
| Google                                 | 21       | 0.2%    |
| Acer                                   | 20       | 0.19%   |
| SiGma Micro                            | 17       | 0.16%   |
| Nokia Mobile Phones                    | 17       | 0.16%   |
| SJ-180517-N                            | 16       | 0.15%   |
| lihappe8                               | 16       | 0.15%   |
| Cheng Uei Precision Industry (Foxlink) | 16       | 0.15%   |
| Lenovo                                 | 14       | 0.13%   |
| WaveRider Communications               | 13       | 0.12%   |
| Xiongmai                               | 12       | 0.11%   |
| Suyin                                  | 12       | 0.11%   |
| Sony                                   | 12       | 0.11%   |
| YGTek                                  | 11       | 0.1%    |
| WCM_USB                                | 11       | 0.1%    |
| Syntek                                 | 11       | 0.1%    |
| Sunplus IT                             | 11       | 0.1%    |
| Intel                                  | 11       | 0.1%    |
| Sunplus Technology                     | 10       | 0.09%   |
| Quanta                                 | 10       | 0.09%   |
| SHENZHEN EMEET TECHNOLOGY              | 9        | 0.08%   |
| Linux Foundation                       | 9        | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 1042     | 9.64%   |
| Logitech HD Pro Webcam C920                       | 551      | 5.1%    |
| Samsung Galaxy A5 (MTP)                           | 357      | 3.3%    |
| Z-Star Venus USB2.0 Camera                        | 355      | 3.29%   |
| Microsoft LifeCam HD-3000                         | 263      | 2.43%   |
| Logitech Webcam C310                              | 257      | 2.38%   |
| Microdia Camera                                   | 250      | 2.31%   |
| Logitech HD Webcam C525                           | 235      | 2.18%   |
| Logitech Webcam C170                              | 224      | 2.07%   |
| Apple iPhone 5/5C/5S/6/SE                         | 220      | 2.04%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 177      | 1.64%   |
| Logitech C922 Pro Stream Webcam                   | 165      | 1.53%   |
| Microdia Webcam Vitade AF                         | 161      | 1.49%   |
| Z-Star Vimicro USB Camera (Altair)                | 155      | 1.43%   |
| Logitech HD Webcam C615                           | 148      | 1.37%   |
| Microdia USB 2.0 Camera                           | 146      | 1.35%   |
| Arkmicro USB2.0 PC CAMERA                         | 136      | 1.26%   |
| Microdia Sonix USB 2.0 Camera                     | 121      | 1.12%   |
| Logitech Webcam C210                              | 117      | 1.08%   |
| ARC International Camera                          | 102      | 0.94%   |
| Generalplus GENERAL WEBCAM                        | 101      | 0.93%   |
| GEMBIRD USB2.0 PC CAMERA                          | 101      | 0.93%   |
| Realtek FULL HD 1080P Webcam                      | 99       | 0.92%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 99       | 0.92%   |
| Logitech HD Webcam C910                           | 97       | 0.9%    |
| Logitech QuickCam Pro 9000                        | 96       | 0.89%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 88       | 0.81%   |
| Microsoft LifeCam Cinema                          | 85       | 0.79%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 85       | 0.79%   |
| Logitech Webcam Pro 9000                          | 84       | 0.78%   |
| Logitech Webcam C930e                             | 82       | 0.76%   |
| Logitech HD Webcam C510                           | 81       | 0.75%   |
| Logitech BRIO                                     | 74       | 0.68%   |
| Aveo USB2.0 Camera                                | 70       | 0.65%   |
| Logitech Webcam C110                              | 68       | 0.63%   |
| Jieli USB PHY 2.0                                 | 68       | 0.63%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 68       | 0.63%   |
| Alcor Micro USB 2.0 PC Camera                     | 67       | 0.62%   |
| Cubeternet USB2.0 Camera                          | 65       | 0.6%    |
| Sunplus Full HD webcam                            | 63       | 0.58%   |
| Huawei UVC Camera                                 | 60       | 0.56%   |
| Microsoft LifeCam VX-2000                         | 58       | 0.54%   |
| MacroSilicon MiraBox Capture                      | 57       | 0.53%   |
| Logitech Webcam C200                              | 57       | 0.53%   |
| Microdia Integrated Camera                        | 56       | 0.52%   |
| Creative Live! Cam Chat HD [VF0700]               | 55       | 0.51%   |
| Logitech Webcam C250                              | 52       | 0.48%   |
| Creative Live! Cam Sync HD [VF0770]               | 52       | 0.48%   |
| Microsoft LifeCam VX-800                          | 51       | 0.47%   |
| Microsoft LifeCam HD-5000                         | 51       | 0.47%   |
| Aveo Camera                                       | 51       | 0.47%   |
| Chicony HP High Definition 1MP Webcam             | 47       | 0.44%   |
| Logitech Webcam C925e                             | 45       | 0.42%   |
| Aveo UVC camera (Bresser microscope)              | 45       | 0.42%   |
| Logitech Logitech Webcam C160                     | 43       | 0.4%    |
| Sunplus FHD Camera Microphone                     | 42       | 0.39%   |
| Razer USA Gaming Webcam [Kiyo]                    | 39       | 0.36%   |
| Logitech StreamCam                                | 39       | 0.36%   |
| webcam webcam                                     | 37       | 0.34%   |
| Logitech Logitech Webcam C100                     | 37       | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 27       | 28.42%  |
| STMicroelectronics         | 11       | 11.58%  |
| Synaptics                  | 10       | 10.53%  |
| Shenzhen Goodix Technology | 9        | 9.47%   |
| AuthenTec                  | 9        | 9.47%   |
| DigitalPersona             | 7        | 7.37%   |
| LighTuning Technology      | 5        | 5.26%   |
| Validity Sensors           | 4        | 4.21%   |
| Upek                       | 4        | 4.21%   |
| Microsoft                  | 4        | 4.21%   |
| Futronic Technology        | 2        | 2.11%   |
| Dell                       | 2        | 2.11%   |
| Suprema                    | 1        | 1.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]                 | 27       | 28.42%  |
| STMicroelectronics Fingerprint Reader                       | 11       | 11.58%  |
| Synaptics  WBDI Fingerprint Reader - USB 052                | 10       | 10.53%  |
| Shenzhen Goodix  Fingerprint Device                         | 9        | 9.47%   |
| DigitalPersona Fingerprint Reader                           | 6        | 6.32%   |
| Microsoft Fingerprint Reader                                | 4        | 4.21%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 3        | 3.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 3        | 3.16%   |
| AuthenTec AES1600                                           | 3        | 3.16%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 2        | 2.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 2        | 2.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 2        | 2.11%   |
| Futronic FS81 Fingerprint Scanner Module                    | 2        | 2.11%   |
| Dell MS819 Wired Mouse With Fingerprint Reader              | 2        | 2.11%   |
| AuthenTec Fingerprint Sensor                                | 2        | 2.11%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 2        | 2.11%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 2        | 2.11%   |
| Upek TCS1C EIM/STM32 Fingerprint sensor                     | 1        | 1.05%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader            | 1        | 1.05%   |
| DigitalPersona Fingerprint Scanner, U.are.U 2000            | 1        | 1.05%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Alcor Micro                             | 68       | 16.67%  |
| Advanced Card Systems                   | 45       | 11.03%  |
| Gemalto (was Gemplus)                   | 38       | 9.31%   |
| OmniKey                                 | 34       | 8.33%   |
| SCM Microsystems                        | 33       | 8.09%   |
| Realtek Semiconductor                   | 24       | 5.88%   |
| Aladdin Knowledge Systems               | 19       | 4.66%   |
| Reiner SCT Kartensysteme                | 18       | 4.41%   |
| VASCO Data Security International       | 14       | 3.43%   |
| Chicony Electronics                     | 12       | 2.94%   |
| Clay Logic                              | 11       | 2.7%    |
| Aktiv                                   | 11       | 2.7%    |
| Yubico.com                              | 10       | 2.45%   |
| Fujitsu Siemens Computers               | 10       | 2.45%   |
| Cherry                                  | 9        | 2.21%   |
| Hewlett-Packard                         | 8        | 1.96%   |
| BIT4ID                                  | 8        | 1.96%   |
| Athena Smartcard Solutions              | 6        | 1.47%   |
| ARDS                                    | 6        | 1.47%   |
| Giesecke & Devrient                     | 4        | 0.98%   |
| Kobil Systems                           | 3        | 0.74%   |
| Watchdata                               | 2        | 0.49%   |
| Castles Technology                      | 2        | 0.49%   |
| Avtor                                   | 2        | 0.49%   |
| ST-Ericsson                             | 1        | 0.25%   |
| Microchip Technology                    | 1        | 0.25%   |
| Mako Technologies                       | 1        | 0.25%   |
| Lenovo                                  | 1        | 0.25%   |
| Jing-Mold Enterprise                    | 1        | 0.25%   |
| In Focus Systems                        | 1        | 0.25%   |
| HID Global                              | 1        | 0.25%   |
| Future Technology Devices International | 1        | 0.25%   |
| Feitian Technologies                    | 1        | 0.25%   |
| C3PO                                    | 1        | 0.25%   |
| BIFIT                                   | 1        | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 44       | 10.76%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 34       | 8.31%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 28       | 6.85%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 24       | 5.87%   |
| Alcor Micro Watchdata W 1981                                               | 24       | 5.87%   |
| Aladdin Knowledge Systems Token JC                                         | 19       | 4.65%   |
| OmniKey CardMan 3021 / 3121                                                | 18       | 4.4%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 16       | 3.91%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 12       | 2.93%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 10       | 2.44%   |
| OmniKey CardMan 1021                                                       | 10       | 2.44%   |
| Aktiv Rutoken lite                                                         | 10       | 2.44%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                              | 8        | 1.96%   |
| Clay Logic Nitrokey Pro                                                    | 8        | 1.96%   |
| Advanced Card Systems ACR122U                                              | 8        | 1.96%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 7        | 1.71%   |
| Reiner SCT Kartensysteme cyberJack one                                     | 7        | 1.71%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 7        | 1.71%   |
| BIT4ID miniLector EVO                                                      | 7        | 1.71%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 6        | 1.47%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 6        | 1.47%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 6        | 1.47%   |
| ARDS JaCarta                                                               | 6        | 1.47%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 5        | 1.22%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 5        | 1.22%   |
| VASCO Data Security International DIGIPASS 870                             | 4        | 0.98%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 4        | 0.98%   |
| Advanced Card Systems ACR39U                                               | 4        | 0.98%   |
| Giesecke & Devrient StarSign CUT S                                         | 3        | 0.73%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                        | 2        | 0.49%   |
| Yubico.com Yubikey 4/5 CCID                                                | 2        | 0.49%   |
| Watchdata USB Key                                                          | 2        | 0.49%   |
| SCM Microsystems SCR3500 A Contact Reader                                  | 2        | 0.49%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                 | 2        | 0.49%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 2        | 0.49%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                            | 2        | 0.49%   |
| OmniKey Smart Card Reader USB                                              | 2        | 0.49%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 2        | 0.49%   |
| OmniKey 3x21 Smart Card Reader                                             | 2        | 0.49%   |
| Kobil Systems KOBIL Class 3 Reader                                         | 2        | 0.49%   |
| Clay Logic Nitrokey HSM                                                    | 2        | 0.49%   |
| Castles Technology EZCCID Smart Card Reader                                | 2        | 0.49%   |
| Avtor SecureToken                                                          | 2        | 0.49%   |
| Advanced Card Systems Token USB 64K                                        | 2        | 0.49%   |
| Advanced Card Systems ACR3901U                                             | 2        | 0.49%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 2        | 0.49%   |
| ST-Ericsson Chipcard Reader                                                | 1        | 0.24%   |
| SCM Microsystems SCR35xx Smart Card Reader                                 | 1        | 0.24%   |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 0.24%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                            | 1        | 0.24%   |
| Microchip Technology SMSC USX101x Reader                                   | 1        | 0.24%   |
| Mako Technologies SZZCS-ZCS80                                              | 1        | 0.24%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 0.24%   |
| Kobil Systems Smart Token                                                  | 1        | 0.24%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard          | 1        | 0.24%   |
| In Focus Systems EMV Smartcard Reader                                      | 1        | 0.24%   |
| HID Global USB Reader V3                                                   | 1        | 0.24%   |
| Giesecke & Devrient StarSign CUT                                           | 1        | 0.24%   |
| Future Technology Devices International Parsec Desktop Reader PR-EH08      | 1        | 0.24%   |
| Fujitsu Siemens Computers Smartcard Reader D323                            | 1        | 0.24%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 49545    | 84.07%  |
| 1     | 8104     | 13.75%  |
| 2     | 976      | 1.66%   |
| 3     | 174      | 0.3%    |
| 4     | 68       | 0.12%   |
| 5     | 36       | 0.06%   |
| 6     | 15       | 0.03%   |
| 7     | 9        | 0.02%   |
| 8     | 4        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4122     | 39.25%  |
| Net/wireless             | 2378     | 22.65%  |
| Communication controller | 981      | 9.34%   |
| Unassigned class         | 666      | 6.34%   |
| Multimedia controller    | 418      | 3.98%   |
| Sound                    | 360      | 3.43%   |
| Chipcard                 | 263      | 2.5%    |
| Camera                   | 259      | 2.47%   |
| Bluetooth                | 175      | 1.67%   |
| Net/ethernet             | 157      | 1.5%    |
| Network                  | 143      | 1.36%   |
| Card reader              | 99       | 0.94%   |
| Modem                    | 95       | 0.9%    |
| Storage/raid             | 80       | 0.76%   |
| Fingerprint reader       | 80       | 0.76%   |
| Storage/ide              | 60       | 0.57%   |
| Dvb card                 | 50       | 0.48%   |
| Firewire controller      | 39       | 0.37%   |
| Tv card                  | 20       | 0.19%   |
| Storage                  | 19       | 0.18%   |
| Storage/ata              | 13       | 0.12%   |
| Video                    | 8        | 0.08%   |
| Storage/nvme             | 8        | 0.08%   |
| Unclassified device      | 5        | 0.05%   |
| Wireless                 | 3        | 0.03%   |

