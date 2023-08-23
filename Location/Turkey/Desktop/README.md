Linux in Turkey - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Turkey.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 625

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 3032h                       | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Gigabyte      | P67A-UD3P-B3                | [a1c6469145](https://linux-hardware.org/?probe=a1c6469145) | Aug 11, 2023 |
| ASUSTek       | PRIME H510M-K               | [3c239efc46](https://linux-hardware.org/?probe=3c239efc46) | Aug 11, 2023 |
| ASUSTek       | M4A87TD/USB3                | [c7c0f2ad91](https://linux-hardware.org/?probe=c7c0f2ad91) | Aug 10, 2023 |
| ASUSTek       | M4A87TD/USB3                | [6aaa92df1c](https://linux-hardware.org/?probe=6aaa92df1c) | Aug 10, 2023 |
| HP            | 3032h                       | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [f29d0b0571](https://linux-hardware.org/?probe=f29d0b0571) | Aug 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [1db8a01118](https://linux-hardware.org/?probe=1db8a01118) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [00311486d2](https://linux-hardware.org/?probe=00311486d2) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [54462345a7](https://linux-hardware.org/?probe=54462345a7) | Jul 31, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| MSI           | B450-A PRO MAX              | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| Gigabyte      | X79-UD3                     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| MSI           | B450 TOMAHAWK               | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| Gigabyte      | B450M H                     | [c659d8d6b5](https://linux-hardware.org/?probe=c659d8d6b5) | Jul 17, 2023 |
| ASUSTek       | PRIME B650M-A II            | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [be97a731d4](https://linux-hardware.org/?probe=be97a731d4) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [a86a73b50c](https://linux-hardware.org/?probe=a86a73b50c) | Jul 13, 2023 |
| Gigabyte      | X79-UD3                     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Gigabyte      | X79-UD3                     | [36fed79d81](https://linux-hardware.org/?probe=36fed79d81) | Jul 01, 2023 |
| Gigabyte      | X79-UD3                     | [5a88d6945d](https://linux-hardware.org/?probe=5a88d6945d) | Jun 29, 2023 |
| MSI           | PRO H410M-B                 | [76dd0fc5f1](https://linux-hardware.org/?probe=76dd0fc5f1) | Jun 24, 2023 |
| Gigabyte      | H81M-S2V                    | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| MSI           | A320M PRO-VD PLUS           | [0cb6da57db](https://linux-hardware.org/?probe=0cb6da57db) | Jun 19, 2023 |
| MSI           | A320M PRO-VD PLUS           | [17a4ba54ac](https://linux-hardware.org/?probe=17a4ba54ac) | Jun 19, 2023 |
| Gigabyte      | X79-UD3                     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | [05923edc6b](https://linux-hardware.org/?probe=05923edc6b) | Jun 15, 2023 |
| MSI           | B450M PRO-VDH MAX           | [e37a7072fd](https://linux-hardware.org/?probe=e37a7072fd) | Jun 13, 2023 |
| MSI           | H510M PRO                   | [08e44766fe](https://linux-hardware.org/?probe=08e44766fe) | Jun 13, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| ASUSTek       | PRIME B560M-K               | [e18c667ddc](https://linux-hardware.org/?probe=e18c667ddc) | Jun 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| ASUSTek       | PRIME B450M-A II            | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Gigabyte      | Z68P-DS3                    | [3371099509](https://linux-hardware.org/?probe=3371099509) | Jun 06, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [ba0e7c7d59](https://linux-hardware.org/?probe=ba0e7c7d59) | Jun 04, 2023 |
| MSI           | H310M PRO-VD PLUS           | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [d61bd0903e](https://linux-hardware.org/?probe=d61bd0903e) | Jun 02, 2023 |
| ASUSTek       | PRIME H510M-K               | [f6f91b620c](https://linux-hardware.org/?probe=f6f91b620c) | May 31, 2023 |
| ASUSTek       | PRIME B450M-A II            | [54bddcb324](https://linux-hardware.org/?probe=54bddcb324) | May 24, 2023 |
| ASUSTek       | Maximus V GENE              | [64085de9fe](https://linux-hardware.org/?probe=64085de9fe) | May 24, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| ASUSTek       | PRIME B560M-A               | [e33e3678c6](https://linux-hardware.org/?probe=e33e3678c6) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [ce2cf2a89a](https://linux-hardware.org/?probe=ce2cf2a89a) | May 15, 2023 |
| Pegatron      | IPXSB-H61                   | [c585628bc8](https://linux-hardware.org/?probe=c585628bc8) | May 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | [71f2dc616d](https://linux-hardware.org/?probe=71f2dc616d) | May 12, 2023 |
| Gigabyte      | H610M H DDR4                | [1c67ba3f8a](https://linux-hardware.org/?probe=1c67ba3f8a) | Apr 30, 2023 |
| ASUSTek       | PRIME B250M-C               | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | [8cbd1dce35](https://linux-hardware.org/?probe=8cbd1dce35) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | [ef0df72346](https://linux-hardware.org/?probe=ef0df72346) | Apr 26, 2023 |
| Pegatron      | IPXSB-H61                   | [2b0ee4d542](https://linux-hardware.org/?probe=2b0ee4d542) | Apr 26, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| MSI           | MAG Z390M MORTAR            | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| Biostar       | G31D-M7                     | [bb518a8623](https://linux-hardware.org/?probe=bb518a8623) | Apr 14, 2023 |
| ASRock        | B450M Pro4                  | [62dd8e069f](https://linux-hardware.org/?probe=62dd8e069f) | Apr 13, 2023 |
| HP            | 18E6                        | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2a108e9eed](https://linux-hardware.org/?probe=2a108e9eed) | Apr 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| Dell          | 057FFP A01                  | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell          | 057FFP A01                  | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte      | H410M H V3                  | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| Gigabyte      | H77M-D3H                    | [31a96824ea](https://linux-hardware.org/?probe=31a96824ea) | Mar 28, 2023 |
| Pegatron      | IPMIP-H55-GEN               | [7dcf9e9b51](https://linux-hardware.org/?probe=7dcf9e9b51) | Mar 27, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Gigabyte      | B450M H                     | [ad5218c0bf](https://linux-hardware.org/?probe=ad5218c0bf) | Mar 19, 2023 |
| HP            | 0A64h                       | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Gigabyte      | B450M S2H                   | [1ccfddfbc0](https://linux-hardware.org/?probe=1ccfddfbc0) | Mar 04, 2023 |
| Casper        | H510 001 G10a               | [95a9cfbf0b](https://linux-hardware.org/?probe=95a9cfbf0b) | Feb 27, 2023 |
| ASUSTek       | M3N78-VM                    | [246492391c](https://linux-hardware.org/?probe=246492391c) | Feb 23, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [29673d3e8f](https://linux-hardware.org/?probe=29673d3e8f) | Feb 22, 2023 |
| ASUSTek       | M3N78-VM                    | [c124cec382](https://linux-hardware.org/?probe=c124cec382) | Feb 19, 2023 |
| Casper        | H510 001 G10a               | [56402bade6](https://linux-hardware.org/?probe=56402bade6) | Feb 17, 2023 |
| MSI           | B350M PRO-VD PLUS           | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| ECS           | G41T-M7                     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| Gigabyte      | G41M-ES2L                   | [ea2304bdfe](https://linux-hardware.org/?probe=ea2304bdfe) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| ASUSTek       | PRIME B250M-K               | [f632cba0a7](https://linux-hardware.org/?probe=f632cba0a7) | Feb 07, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| Pegatron      | IPXSB-H61                   | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| Gigabyte      | B450M H                     | [2d4aa2e1a0](https://linux-hardware.org/?probe=2d4aa2e1a0) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [3be362b4aa](https://linux-hardware.org/?probe=3be362b4aa) | Jan 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [d4a5012f93](https://linux-hardware.org/?probe=d4a5012f93) | Jan 29, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [cba2528a29](https://linux-hardware.org/?probe=cba2528a29) | Jan 28, 2023 |
| ASUSTek       | PRIME H410M-K               | [0cda1a95a2](https://linux-hardware.org/?probe=0cda1a95a2) | Jan 28, 2023 |
| ASUSTek       | P5L-MX                      | [c66369d864](https://linux-hardware.org/?probe=c66369d864) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| MSI           | H510M PRO                   | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Lenovo        | 3132 NOK                    | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [8c8cf26214](https://linux-hardware.org/?probe=8c8cf26214) | Jan 16, 2023 |
| Unknown       | Unknown                     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Gigabyte      | H55M-UD2H                   | [0a323f0cb8](https://linux-hardware.org/?probe=0a323f0cb8) | Jan 15, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [6ff8ef1eb3](https://linux-hardware.org/?probe=6ff8ef1eb3) | Jan 15, 2023 |
| Vestel        | 14MB24A                     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | [14d0dddfc9](https://linux-hardware.org/?probe=14d0dddfc9) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | [eb61471644](https://linux-hardware.org/?probe=eb61471644) | Jan 13, 2023 |
| Dell          | 0Y2K8N A01                  | [46dfb4ddef](https://linux-hardware.org/?probe=46dfb4ddef) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| ASRock        | A320M-HDV R4.0              | [fba9812651](https://linux-hardware.org/?probe=fba9812651) | Jan 08, 2023 |
| ASUSTek       | P5G41C-M LX                 | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek       | P5G41C-M LX                 | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| MSI           | 880GMA-E45                  | [f55d2f2c90](https://linux-hardware.org/?probe=f55d2f2c90) | Jan 03, 2023 |
| Gigabyte      | 970A-UD3P                   | [7d5ca26325](https://linux-hardware.org/?probe=7d5ca26325) | Dec 19, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [58eac3b208](https://linux-hardware.org/?probe=58eac3b208) | Dec 17, 2022 |
| Pegatron      | IPXSB-H61                   | [84c0b45a3b](https://linux-hardware.org/?probe=84c0b45a3b) | Dec 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [6dec5de4a9](https://linux-hardware.org/?probe=6dec5de4a9) | Dec 13, 2022 |
| MSI           | B450 TOMAHAWK               | [b822420d6d](https://linux-hardware.org/?probe=b822420d6d) | Dec 09, 2022 |
| MSI           | H81M-P33                    | [9ba738605c](https://linux-hardware.org/?probe=9ba738605c) | Dec 07, 2022 |
| MSI           | H81M-P33                    | [bb540dbfb1](https://linux-hardware.org/?probe=bb540dbfb1) | Dec 07, 2022 |
| ASUSTek       | PRIME B450M-K II            | [2a7f909902](https://linux-hardware.org/?probe=2a7f909902) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-A               | [f8e78fbf31](https://linux-hardware.org/?probe=f8e78fbf31) | Dec 06, 2022 |
| ASUSTek       | PRIME B250M-K               | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | [4246d4813a](https://linux-hardware.org/?probe=4246d4813a) | Nov 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [76f6ba932f](https://linux-hardware.org/?probe=76f6ba932f) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| ASUSTek       | B85-PRO GAMER               | [6d87497f34](https://linux-hardware.org/?probe=6d87497f34) | Nov 23, 2022 |
| Gigabyte      | Z77-D3H                     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| XDO.AI        | Pantera Pico PC             | [9a588b78c3](https://linux-hardware.org/?probe=9a588b78c3) | Nov 16, 2022 |
| XDO.AI        | Pantera Pico PC             | [70071adfb0](https://linux-hardware.org/?probe=70071adfb0) | Nov 16, 2022 |
| Unknown       | Unknown                     | [ca24381492](https://linux-hardware.org/?probe=ca24381492) | Nov 15, 2022 |
| MSI           | Z97I GAMING AC              | [b0a5c0251f](https://linux-hardware.org/?probe=b0a5c0251f) | Nov 15, 2022 |
| Pegatron      | IPXSB-H61                   | [9de70711ef](https://linux-hardware.org/?probe=9de70711ef) | Nov 15, 2022 |
| ASUSTek       | H81M-K                      | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5GC-MX/1333                | [32bb86a1e6](https://linux-hardware.org/?probe=32bb86a1e6) | Nov 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | [c91e77c03a](https://linux-hardware.org/?probe=c91e77c03a) | Nov 06, 2022 |
| XDO.AI        | Pantera Pico PC             | [8c532d2ad0](https://linux-hardware.org/?probe=8c532d2ad0) | Nov 05, 2022 |
| XDO.AI        | Pantera Pico PC             | [faf3c3a1ae](https://linux-hardware.org/?probe=faf3c3a1ae) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| ASUSTek       | H81M-PLUS                   | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| Gigabyte      | 970A-UD3P                   | [9dffa26de0](https://linux-hardware.org/?probe=9dffa26de0) | Oct 20, 2022 |
| Gigabyte      | M61SME-S2                   | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Gigabyte      | 970A-UD3P                   | [210d7fdd5d](https://linux-hardware.org/?probe=210d7fdd5d) | Oct 17, 2022 |
| Pegatron      | 2A84h                       | [5b46511238](https://linux-hardware.org/?probe=5b46511238) | Oct 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [b8ba7e41c8](https://linux-hardware.org/?probe=b8ba7e41c8) | Oct 14, 2022 |
| Intel         | DH87RL AAG74240-400         | [82d2063927](https://linux-hardware.org/?probe=82d2063927) | Oct 12, 2022 |
| ASUSTek       | P7H55-M LX                  | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| Unknown       | Unknown                     | [a2979dfe6d](https://linux-hardware.org/?probe=a2979dfe6d) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e9928bbd81](https://linux-hardware.org/?probe=e9928bbd81) | Oct 10, 2022 |
| HP            | 81C5 MVB                    | [1f08f2d239](https://linux-hardware.org/?probe=1f08f2d239) | Oct 10, 2022 |
| ASRock        | B450M Pro4                  | [92998a2fa1](https://linux-hardware.org/?probe=92998a2fa1) | Oct 07, 2022 |
| ASRock        | B450M Pro4                  | [87936d87c6](https://linux-hardware.org/?probe=87936d87c6) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| MSI           | H110M GAMING                | [379aaceaab](https://linux-hardware.org/?probe=379aaceaab) | Oct 03, 2022 |
| MSI           | A75A-G35                    | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Casper        | C15B                        | [be4c7469a6](https://linux-hardware.org/?probe=be4c7469a6) | Oct 01, 2022 |
| ASUSTek       | P8Z68-V                     | [c6e67f7643](https://linux-hardware.org/?probe=c6e67f7643) | Oct 01, 2022 |
| ASUSTek       | P8Z68-V                     | [f0d1b90e89](https://linux-hardware.org/?probe=f0d1b90e89) | Sep 29, 2022 |
| ASUSTek       | P8Z68-V                     | [36ff9b8bcb](https://linux-hardware.org/?probe=36ff9b8bcb) | Sep 29, 2022 |
| MSI           | B560M PRO                   | [5949440926](https://linux-hardware.org/?probe=5949440926) | Sep 26, 2022 |
| Casper        | NIRVANA DESKTOP             | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| Foxconn       | G31MXP FAB:1.1              | [d401319e57](https://linux-hardware.org/?probe=d401319e57) | Sep 17, 2022 |
| Gigabyte      | B450M H                     | [5ae6fea41e](https://linux-hardware.org/?probe=5ae6fea41e) | Sep 13, 2022 |
| Gigabyte      | G41M-ES2L                   | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| MSI           | B450M-A PRO MAX             | [6462d2370f](https://linux-hardware.org/?probe=6462d2370f) | Aug 31, 2022 |
| ASUSTek       | PRIME X570-P                | [1337a4c8e9](https://linux-hardware.org/?probe=1337a4c8e9) | Aug 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1f85d6a1b9](https://linux-hardware.org/?probe=1f85d6a1b9) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ccea67d380](https://linux-hardware.org/?probe=ccea67d380) | Aug 19, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [7cd120b2e1](https://linux-hardware.org/?probe=7cd120b2e1) | Aug 14, 2022 |
| MSI           | H410M PRO-VH                | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| ASRock        | H110M-STX                   | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Gigabyte      | H310M S2V                   | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| ASUSTek       | PRIME A520M-E               | [ef6984a3a9](https://linux-hardware.org/?probe=ef6984a3a9) | Jul 26, 2022 |
| Acer          | Veriton ES2740G V:1.0       | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| Unknown       | Unknown                     | [b85c907afc](https://linux-hardware.org/?probe=b85c907afc) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [09bdb4be6a](https://linux-hardware.org/?probe=09bdb4be6a) | Jul 08, 2022 |
| ASRock        | FM2A68M-DG3+                | [825362cafe](https://linux-hardware.org/?probe=825362cafe) | Jul 06, 2022 |
| HP            | 83EE                        | [a49f00b158](https://linux-hardware.org/?probe=a49f00b158) | Jul 05, 2022 |
| Gigabyte      | EP45-DS3                    | [bc316ca4cb](https://linux-hardware.org/?probe=bc316ca4cb) | Jul 02, 2022 |
| Gigabyte      | B450M S2H                   | [63da8fa3b9](https://linux-hardware.org/?probe=63da8fa3b9) | Jul 02, 2022 |
| ASUSTek       | H61M-PRO                    | [48464c0df0](https://linux-hardware.org/?probe=48464c0df0) | Jun 30, 2022 |
| MSI           | B250M GAMING PRO            | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [6e34269277](https://linux-hardware.org/?probe=6e34269277) | Jun 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| ASUSTek       | P5G41T-M                    | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| Lenovo        | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Gigabyte      | 970A-UD3P                   | [7e45eef7ba](https://linux-hardware.org/?probe=7e45eef7ba) | Jun 09, 2022 |
| MSI           | H81M-P33                    | [b48f5d554f](https://linux-hardware.org/?probe=b48f5d554f) | Jun 05, 2022 |
| ASRock        | G31M-VS2                    | [5ecae1ce0d](https://linux-hardware.org/?probe=5ecae1ce0d) | Jun 04, 2022 |
| ASRock        | G31M-VS2                    | [76e1b187df](https://linux-hardware.org/?probe=76e1b187df) | Jun 04, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [eca3bd70a8](https://linux-hardware.org/?probe=eca3bd70a8) | Jun 02, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [dedf695fc6](https://linux-hardware.org/?probe=dedf695fc6) | May 31, 2022 |
| MSI           | B365M PRO-VH                | [a1e7cf7158](https://linux-hardware.org/?probe=a1e7cf7158) | May 30, 2022 |
| MSI           | B365M PRO-VH                | [4d4ea4beec](https://linux-hardware.org/?probe=4d4ea4beec) | May 30, 2022 |
| Gigabyte      | H270-Gaming 3               | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| Lenovo        | 30C7 SDK0J40688 WIN 3424... | [93ffb95e1a](https://linux-hardware.org/?probe=93ffb95e1a) | May 29, 2022 |
| ECS           | G31T-M7                     | [706532d328](https://linux-hardware.org/?probe=706532d328) | May 28, 2022 |
| Gigabyte      | H410M S2H                   | [c7e011235c](https://linux-hardware.org/?probe=c7e011235c) | May 26, 2022 |
| MSI           | MS-7360                     | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| MSI           | B350M PRO-VD PLUS           | [6098005a1a](https://linux-hardware.org/?probe=6098005a1a) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [aac14b5554](https://linux-hardware.org/?probe=aac14b5554) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [6763ad45ce](https://linux-hardware.org/?probe=6763ad45ce) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| Intel         | ChiefRiver                  | [8e4aca2b1f](https://linux-hardware.org/?probe=8e4aca2b1f) | May 19, 2022 |
| Intel         | ChiefRiver                  | [4d38806404](https://linux-hardware.org/?probe=4d38806404) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9c3b90c60d](https://linux-hardware.org/?probe=9c3b90c60d) | May 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | [76c661d512](https://linux-hardware.org/?probe=76c661d512) | May 18, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| ECS           | G41T-R3                     | [ed8d019c1e](https://linux-hardware.org/?probe=ed8d019c1e) | May 14, 2022 |
| ECS           | G41T-R3                     | [1bf10674d0](https://linux-hardware.org/?probe=1bf10674d0) | May 14, 2022 |
| ASUSTek       | P5Q SE/R                    | [c99b0a0683](https://linux-hardware.org/?probe=c99b0a0683) | May 08, 2022 |
| Gigabyte      | H61M-S2PV                   | [f09766a481](https://linux-hardware.org/?probe=f09766a481) | Apr 27, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d74b2d8bb3](https://linux-hardware.org/?probe=d74b2d8bb3) | Apr 26, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [0d4977ae14](https://linux-hardware.org/?probe=0d4977ae14) | Apr 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [a76e953825](https://linux-hardware.org/?probe=a76e953825) | Apr 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [68a04098ec](https://linux-hardware.org/?probe=68a04098ec) | Apr 21, 2022 |
| ASUSTek       | P8H77-M LE                  | [f940c46866](https://linux-hardware.org/?probe=f940c46866) | Apr 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [49c981ee41](https://linux-hardware.org/?probe=49c981ee41) | Apr 17, 2022 |
| MSI           | B560M-A PRO                 | [c394557d17](https://linux-hardware.org/?probe=c394557d17) | Apr 16, 2022 |
| ASUSTek       | A88XM-A                     | [427335d90c](https://linux-hardware.org/?probe=427335d90c) | Apr 16, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| Gigabyte      | Z97X-UD5H                   | [a4b25c87fa](https://linux-hardware.org/?probe=a4b25c87fa) | Apr 13, 2022 |
| MSI           | MS-7360                     | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| ASUSTek       | H61M-PRO                    | [c89c043120](https://linux-hardware.org/?probe=c89c043120) | Apr 10, 2022 |
| ASUSTek       | PRIME B550M-K               | [acff685c08](https://linux-hardware.org/?probe=acff685c08) | Apr 09, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| ASUSTek       | H61M-D                      | [b9c2af0976](https://linux-hardware.org/?probe=b9c2af0976) | Apr 03, 2022 |
| ASUSTek       | B560M-P                     | [d696143851](https://linux-hardware.org/?probe=d696143851) | Apr 03, 2022 |
| MSI           | H81M-P33                    | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| Intel         | Unknown                     | [4689fbf7e1](https://linux-hardware.org/?probe=4689fbf7e1) | Mar 31, 2022 |
| Acer          | Nitro N50-610               | [17f97e88c0](https://linux-hardware.org/?probe=17f97e88c0) | Mar 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | [1c58a58ead](https://linux-hardware.org/?probe=1c58a58ead) | Mar 29, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [656413f7e6](https://linux-hardware.org/?probe=656413f7e6) | Mar 28, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| MSI           | MS-7360                     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [c294e20164](https://linux-hardware.org/?probe=c294e20164) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [5b9b7903ad](https://linux-hardware.org/?probe=5b9b7903ad) | Mar 21, 2022 |
| Pegatron      | 2AC3                        | [d1f5b906e4](https://linux-hardware.org/?probe=d1f5b906e4) | Mar 19, 2022 |
| MSI           | MS-7360                     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [9b2f013b90](https://linux-hardware.org/?probe=9b2f013b90) | Mar 13, 2022 |
| Acer          | Nitro N50-610               | [c24379e7da](https://linux-hardware.org/?probe=c24379e7da) | Mar 13, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [09d876ab23](https://linux-hardware.org/?probe=09d876ab23) | Mar 11, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [e0e30a9273](https://linux-hardware.org/?probe=e0e30a9273) | Mar 11, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [b5a2bf57eb](https://linux-hardware.org/?probe=b5a2bf57eb) | Mar 09, 2022 |
| Dell          | 0JP3NX A01                  | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| Fujitsu Si... | D2598-A1 S26361-D2598-A1    | [b003806a72](https://linux-hardware.org/?probe=b003806a72) | Mar 05, 2022 |
| Gigabyte      | 965P-DS3                    | [71481e0139](https://linux-hardware.org/?probe=71481e0139) | Mar 04, 2022 |
| MSI           | A58M-E33                    | [58f83fb7fc](https://linux-hardware.org/?probe=58f83fb7fc) | Mar 02, 2022 |
| ASUSTek       | A68HM-K                     | [fdbadf4dcb](https://linux-hardware.org/?probe=fdbadf4dcb) | Feb 28, 2022 |
| Gigabyte      | B450M S2H                   | [101d5588d2](https://linux-hardware.org/?probe=101d5588d2) | Feb 26, 2022 |
| Gigabyte      | H410M S2H                   | [399a541ed9](https://linux-hardware.org/?probe=399a541ed9) | Feb 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [ebca133032](https://linux-hardware.org/?probe=ebca133032) | Feb 21, 2022 |
| HP            | 0B54h D                     | [5081de1d10](https://linux-hardware.org/?probe=5081de1d10) | Feb 14, 2022 |
| ASUSTek       | H170M-E D3                  | [e9f4a5b4a8](https://linux-hardware.org/?probe=e9f4a5b4a8) | Feb 14, 2022 |
| Gigabyte      | AB350M-D3V-CF               | [8d0cd32859](https://linux-hardware.org/?probe=8d0cd32859) | Feb 14, 2022 |
| ASRock        | B450M Pro4                  | [3bbcbc62f5](https://linux-hardware.org/?probe=3bbcbc62f5) | Feb 13, 2022 |
| ASUSTek       | PRIME B450M-A               | [daa58b3386](https://linux-hardware.org/?probe=daa58b3386) | Feb 12, 2022 |
| Foxconn       | A88GMV                      | [a1004894e9](https://linux-hardware.org/?probe=a1004894e9) | Feb 11, 2022 |
| HP            | 1998                        | [800ceec2ea](https://linux-hardware.org/?probe=800ceec2ea) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c3bda85409](https://linux-hardware.org/?probe=c3bda85409) | Feb 09, 2022 |
| ECS           | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASRock        | B450M Pro4                  | [9efa6de9c0](https://linux-hardware.org/?probe=9efa6de9c0) | Feb 07, 2022 |
| Lenovo        | 317C SDK0J40688 WIN 3424... | [f6174ebd67](https://linux-hardware.org/?probe=f6174ebd67) | Feb 06, 2022 |
| Gigabyte      | B250-FinTech-CF             | [23c8c7962a](https://linux-hardware.org/?probe=23c8c7962a) | Feb 03, 2022 |
| Gigabyte      | H81M-S2V                    | [4c9a0cdddb](https://linux-hardware.org/?probe=4c9a0cdddb) | Feb 03, 2022 |
| Gigabyte      | F2A55M-DS2                  | [bdb825e963](https://linux-hardware.org/?probe=bdb825e963) | Feb 02, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [069306fc04](https://linux-hardware.org/?probe=069306fc04) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [87c1802929](https://linux-hardware.org/?probe=87c1802929) | Jan 19, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [ef86d029ff](https://linux-hardware.org/?probe=ef86d029ff) | Jan 16, 2022 |
| ASUSTek       | PRIME B450M-A               | [f87a30cc1b](https://linux-hardware.org/?probe=f87a30cc1b) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [a7e3aee849](https://linux-hardware.org/?probe=a7e3aee849) | Jan 15, 2022 |
| Intel         | H55                         | [e774b0ecac](https://linux-hardware.org/?probe=e774b0ecac) | Jan 12, 2022 |
| Intel         | H55                         | [6528de9981](https://linux-hardware.org/?probe=6528de9981) | Jan 12, 2022 |
| Gigabyte      | M61SME-S2                   | [972e998ff5](https://linux-hardware.org/?probe=972e998ff5) | Jan 02, 2022 |
| ASUSTek       | H81-PLUS                    | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [23d8bf2c9d](https://linux-hardware.org/?probe=23d8bf2c9d) | Dec 23, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [992c6c4350](https://linux-hardware.org/?probe=992c6c4350) | Dec 21, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [16017b88bc](https://linux-hardware.org/?probe=16017b88bc) | Dec 19, 2021 |
| Gigabyte      | M61SME-S2                   | [f2380fb2f3](https://linux-hardware.org/?probe=f2380fb2f3) | Dec 18, 2021 |
| ASUSTek       | P9X79 PRO                   | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| Gigabyte      | X58A-UD3R                   | [cc4e06fca3](https://linux-hardware.org/?probe=cc4e06fca3) | Dec 12, 2021 |
| Gigabyte      | H81M-DS2                    | [ddcca3f92c](https://linux-hardware.org/?probe=ddcca3f92c) | Dec 01, 2021 |
| Biostar       | A68N-5600                   | [74211378b7](https://linux-hardware.org/?probe=74211378b7) | Nov 30, 2021 |
| ECS           | A55F-M3                     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| MSI           | H270 GAMING M3              | [d863ad50dd](https://linux-hardware.org/?probe=d863ad50dd) | Nov 16, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [3f989c08c0](https://linux-hardware.org/?probe=3f989c08c0) | Nov 15, 2021 |
| ASUSTek       | M5A78L LE                   | [d342b54224](https://linux-hardware.org/?probe=d342b54224) | Nov 12, 2021 |
| HP            | 8433 11                     | [737e98b3e9](https://linux-hardware.org/?probe=737e98b3e9) | Nov 09, 2021 |
| HP            | 8433 11                     | [ad7a603e07](https://linux-hardware.org/?probe=ad7a603e07) | Nov 09, 2021 |
| MSI           | Z490-A PRO                  | [8055ba32cb](https://linux-hardware.org/?probe=8055ba32cb) | Nov 02, 2021 |
| Gigabyte      | H97M-D3H                    | [6ec4945ffa](https://linux-hardware.org/?probe=6ec4945ffa) | Nov 02, 2021 |
| Gigabyte      | H97M-D3H                    | [05e3caa05c](https://linux-hardware.org/?probe=05e3caa05c) | Nov 02, 2021 |
| ECS           | A55F-M3                     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Gigabyte      | G41M-Combo                  | [a9908463d8](https://linux-hardware.org/?probe=a9908463d8) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| ASUSTek       | PRIME Z270-P                | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| MSI           | Boston                      | [c45a00b3d6](https://linux-hardware.org/?probe=c45a00b3d6) | Oct 22, 2021 |
| HP            | 339A                        | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Lenovo        | 3132 NOK                    | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| ASUSTek       | PRIME B450M-K               | [666c41eb03](https://linux-hardware.org/?probe=666c41eb03) | Oct 01, 2021 |
| MSI           | B350 PC MATE                | [4733967390](https://linux-hardware.org/?probe=4733967390) | Sep 28, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [569dd82022](https://linux-hardware.org/?probe=569dd82022) | Sep 28, 2021 |
| ASUSTek       | A55BM-K                     | [e06893df36](https://linux-hardware.org/?probe=e06893df36) | Sep 24, 2021 |
| MSI           | Boston                      | [d95f0de735](https://linux-hardware.org/?probe=d95f0de735) | Sep 21, 2021 |
| MSI           | Boston                      | [50f3ed26ef](https://linux-hardware.org/?probe=50f3ed26ef) | Sep 21, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [c3074fbb19](https://linux-hardware.org/?probe=c3074fbb19) | Sep 18, 2021 |
| Lenovo        | 3132 NOK                    | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| HP            | 81C5 MVB                    | [b59c9cf621](https://linux-hardware.org/?probe=b59c9cf621) | Sep 10, 2021 |
| Gigabyte      | H97-HD3                     | [0535c42df0](https://linux-hardware.org/?probe=0535c42df0) | Aug 28, 2021 |
| Gigabyte      | H97-HD3                     | [7ab720c75e](https://linux-hardware.org/?probe=7ab720c75e) | Aug 28, 2021 |
| HP            | 0B0Ch                       | [b5933fde35](https://linux-hardware.org/?probe=b5933fde35) | Aug 26, 2021 |
| MSI           | Z370-A PRO                  | [1987e34178](https://linux-hardware.org/?probe=1987e34178) | Aug 26, 2021 |
| MSI           | Z370-A PRO                  | [e88c582d11](https://linux-hardware.org/?probe=e88c582d11) | Aug 26, 2021 |
| Zillion       | Unknown                     | [eca4874a91](https://linux-hardware.org/?probe=eca4874a91) | Aug 16, 2021 |
| ASUSTek       | PRIME B450M-A II            | [bf2833441b](https://linux-hardware.org/?probe=bf2833441b) | Aug 02, 2021 |
| ASUSTek       | Maximus V FORMULA           | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| MSI           | Z390-A PRO                  | [e20ae9878e](https://linux-hardware.org/?probe=e20ae9878e) | Jul 28, 2021 |
| Gigabyte      | Z77X-UD3H                   | [572b814c9a](https://linux-hardware.org/?probe=572b814c9a) | Jul 11, 2021 |
| ASUSTek       | M5A97 EVO                   | [5780498435](https://linux-hardware.org/?probe=5780498435) | Jul 10, 2021 |
| Gigabyte      | X58A-UD3R                   | [8719efbf51](https://linux-hardware.org/?probe=8719efbf51) | Jul 01, 2021 |
| Gigabyte      | X58A-UD3R                   | [7dc621086b](https://linux-hardware.org/?probe=7dc621086b) | Jul 01, 2021 |
| Gigabyte      | P31-DS3L                    | [9e8b678a15](https://linux-hardware.org/?probe=9e8b678a15) | Jun 26, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [7f19e67108](https://linux-hardware.org/?probe=7f19e67108) | Jun 24, 2021 |
| Foxconn       | 2A8C                        | [e4a673b348](https://linux-hardware.org/?probe=e4a673b348) | Jun 22, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [2825afbb58](https://linux-hardware.org/?probe=2825afbb58) | Jun 19, 2021 |
| ASUSTek       | F2A85-M LE                  | [53c57b744c](https://linux-hardware.org/?probe=53c57b744c) | Jun 19, 2021 |
| ASUSTek       | H110M-K                     | [10bd8ec628](https://linux-hardware.org/?probe=10bd8ec628) | Jun 09, 2021 |
| ASUSTek       | H110M-K                     | [1834cd43db](https://linux-hardware.org/?probe=1834cd43db) | Jun 09, 2021 |
| MSI           | Z390-A PRO                  | [bf39077364](https://linux-hardware.org/?probe=bf39077364) | Jun 08, 2021 |
| Acer          | Nitro N50-610               | [0a08acc62d](https://linux-hardware.org/?probe=0a08acc62d) | Jun 02, 2021 |
| Foxconn       | 45GM/45CM/45CM-S            | [d502ee8537](https://linux-hardware.org/?probe=d502ee8537) | May 29, 2021 |
| Huanan        | X58 V1.0                    | [3ec420c60a](https://linux-hardware.org/?probe=3ec420c60a) | May 29, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [9673f97e2a](https://linux-hardware.org/?probe=9673f97e2a) | May 28, 2021 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [4e988af2df](https://linux-hardware.org/?probe=4e988af2df) | May 25, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [de14f99534](https://linux-hardware.org/?probe=de14f99534) | May 24, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [8ecaed3eb2](https://linux-hardware.org/?probe=8ecaed3eb2) | May 24, 2021 |
| ASUSTek       | M5A78L-M LX3                | [3eed0a8556](https://linux-hardware.org/?probe=3eed0a8556) | May 23, 2021 |
| ASUSTek       | M5A78L-M LX3                | [10cd2166f2](https://linux-hardware.org/?probe=10cd2166f2) | May 23, 2021 |
| Acer          | Nitro N50-610               | [a0a5bdf4ea](https://linux-hardware.org/?probe=a0a5bdf4ea) | May 22, 2021 |
| MSI           | Z270 PC MATE                | [da1a4f54be](https://linux-hardware.org/?probe=da1a4f54be) | May 22, 2021 |
| ASUSTek       | Maximus V FORMULA           | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| Huanan        | X99 F8D V1.0                | [3a75b6cf54](https://linux-hardware.org/?probe=3a75b6cf54) | May 19, 2021 |
| ASUSTek       | SABERTOOTH X58              | [0961f5d086](https://linux-hardware.org/?probe=0961f5d086) | May 15, 2021 |
| Unknown       | Unknown                     | [9f5c976e69](https://linux-hardware.org/?probe=9f5c976e69) | May 12, 2021 |
| Gigabyte      | Z97-HD3                     | [2cd574ece5](https://linux-hardware.org/?probe=2cd574ece5) | May 12, 2021 |
| MSI           | H110M GAMING                | [7a9397a33b](https://linux-hardware.org/?probe=7a9397a33b) | May 11, 2021 |
| MSI           | H110M GAMING                | [906ee1d594](https://linux-hardware.org/?probe=906ee1d594) | May 11, 2021 |
| ASUSTek       | M5A78L-M LX3                | [d6af9c1156](https://linux-hardware.org/?probe=d6af9c1156) | May 07, 2021 |
| Dell          | 0FPP7F A00                  | [fe13415ac0](https://linux-hardware.org/?probe=fe13415ac0) | May 07, 2021 |
| HP            | 0AACh                       | [888b5f2f1e](https://linux-hardware.org/?probe=888b5f2f1e) | May 07, 2021 |
| ASUSTek       | PRIME B450M-K               | [9a6fe24ea7](https://linux-hardware.org/?probe=9a6fe24ea7) | May 06, 2021 |
| Gigabyte      | H81M-S2V                    | [57c9671690](https://linux-hardware.org/?probe=57c9671690) | May 05, 2021 |
| Gigabyte      | H81M-S2V                    | [36d4d5ea8f](https://linux-hardware.org/?probe=36d4d5ea8f) | May 05, 2021 |
| Gigabyte      | G41M-ES2L                   | [94b793d9ce](https://linux-hardware.org/?probe=94b793d9ce) | May 05, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [f89317f54a](https://linux-hardware.org/?probe=f89317f54a) | May 02, 2021 |
| ASUSTek       | EX-A320M-GAMING             | [dc100ee99f](https://linux-hardware.org/?probe=dc100ee99f) | May 01, 2021 |
| Foxconn       | 45GM/45CM/45CM-S            | [d2e947f1ad](https://linux-hardware.org/?probe=d2e947f1ad) | Apr 29, 2021 |
| ASUSTek       | Z170M-PLUS                  | [70cd900750](https://linux-hardware.org/?probe=70cd900750) | Apr 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [c07c6f9b12](https://linux-hardware.org/?probe=c07c6f9b12) | Apr 21, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [a063e84120](https://linux-hardware.org/?probe=a063e84120) | Apr 14, 2021 |
| MSI           | B350 TOMAHAWK               | [91b766ed72](https://linux-hardware.org/?probe=91b766ed72) | Apr 13, 2021 |
| Gigabyte      | B450M S2H                   | [003abcb0f1](https://linux-hardware.org/?probe=003abcb0f1) | Apr 12, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [cffc31dc3e](https://linux-hardware.org/?probe=cffc31dc3e) | Apr 10, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [26cb4eb6f1](https://linux-hardware.org/?probe=26cb4eb6f1) | Apr 06, 2021 |
| Dell          | 0JP3NX A01                  | [46c3e293c2](https://linux-hardware.org/?probe=46c3e293c2) | Apr 05, 2021 |
| Dell          | 0JP3NX A01                  | [f7cf61b7bd](https://linux-hardware.org/?probe=f7cf61b7bd) | Apr 04, 2021 |
| ASUSTek       | GRYPHON Z87                 | [2246aad1f7](https://linux-hardware.org/?probe=2246aad1f7) | Apr 03, 2021 |
| Casper        | H410H6-TI2 001              | [02147311b7](https://linux-hardware.org/?probe=02147311b7) | Mar 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | [03b417dc3d](https://linux-hardware.org/?probe=03b417dc3d) | Mar 27, 2021 |
| ASUSTek       | PRIME B450M-K               | [1bf6f627bc](https://linux-hardware.org/?probe=1bf6f627bc) | Mar 25, 2021 |
| Gigabyte      | A320M-S2H-CF                | [3b131ecd1c](https://linux-hardware.org/?probe=3b131ecd1c) | Mar 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [af90642d15](https://linux-hardware.org/?probe=af90642d15) | Mar 18, 2021 |
| MSI           | 760GM-P21                   | [91a13be8c4](https://linux-hardware.org/?probe=91a13be8c4) | Mar 17, 2021 |
| Casper        | NIRVANA DESKTOP 1           | [fe1eeed22d](https://linux-hardware.org/?probe=fe1eeed22d) | Mar 01, 2021 |
| ASUSTek       | X99-PRO/USB                 | [fbf2c32cf1](https://linux-hardware.org/?probe=fbf2c32cf1) | Feb 28, 2021 |
| Gigabyte      | Z97-HD3                     | [d28a00e38e](https://linux-hardware.org/?probe=d28a00e38e) | Feb 23, 2021 |
| ASRock        | G31M-S                      | [0964243e66](https://linux-hardware.org/?probe=0964243e66) | Feb 20, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [32c5fd809b](https://linux-hardware.org/?probe=32c5fd809b) | Feb 18, 2021 |
| ASUSTek       | M3A78-T                     | [bcf63e815c](https://linux-hardware.org/?probe=bcf63e815c) | Feb 16, 2021 |
| Dell          | 0JP3NX A01                  | [5072bb4508](https://linux-hardware.org/?probe=5072bb4508) | Feb 15, 2021 |
| Gigabyte      | A320M-S2H-CF                | [59ecc65bb7](https://linux-hardware.org/?probe=59ecc65bb7) | Feb 10, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [7c76bef1bc](https://linux-hardware.org/?probe=7c76bef1bc) | Feb 10, 2021 |
| ASUSTek       | P8H67-M LE                  | [0830ceb950](https://linux-hardware.org/?probe=0830ceb950) | Jan 31, 2021 |
| ASUSTek       | P5G41C-M LX                 | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| SYWZ          | S210H Series                | [42487ac29c](https://linux-hardware.org/?probe=42487ac29c) | Jan 30, 2021 |
| Dell          | 0FPP7F A00                  | [264f928670](https://linux-hardware.org/?probe=264f928670) | Jan 30, 2021 |
| Gigabyte      | H77M-D3H                    | [f022e9eaaa](https://linux-hardware.org/?probe=f022e9eaaa) | Jan 28, 2021 |
| Gigabyte      | B450M S2H                   | [f253037c81](https://linux-hardware.org/?probe=f253037c81) | Jan 23, 2021 |
| FIC           | GE2 Series                  | [4a92b26339](https://linux-hardware.org/?probe=4a92b26339) | Jan 21, 2021 |
| ASUSTek       | P8H67-M LE                  | [04f488d270](https://linux-hardware.org/?probe=04f488d270) | Jan 18, 2021 |
| Gigabyte      | EP45T-UD3LR                 | [5493d3939d](https://linux-hardware.org/?probe=5493d3939d) | Jan 13, 2021 |
| MSI           | B365M PRO-VH                | [bdb49f2bce](https://linux-hardware.org/?probe=bdb49f2bce) | Jan 12, 2021 |
| MSI           | B365M PRO-VH                | [5251f058d5](https://linux-hardware.org/?probe=5251f058d5) | Jan 11, 2021 |
| Gigabyte      | B75N                        | [48cfc5e6d4](https://linux-hardware.org/?probe=48cfc5e6d4) | Jan 10, 2021 |
| Gigabyte      | EP45T-UD3LR                 | [c10eec8c7d](https://linux-hardware.org/?probe=c10eec8c7d) | Jan 08, 2021 |
| Gigabyte      | EP45T-UD3LR                 | [8bdbe7fb5b](https://linux-hardware.org/?probe=8bdbe7fb5b) | Jan 08, 2021 |
| Gigabyte      | B75N                        | [2d41d731ba](https://linux-hardware.org/?probe=2d41d731ba) | Jan 02, 2021 |
| ABIT          | FP-IN9 SLI                  | [65c9588779](https://linux-hardware.org/?probe=65c9588779) | Dec 29, 2020 |
| Lenovo        | 3708 SDK0J40679 WIN 3273... | [f1e8d2f15b](https://linux-hardware.org/?probe=f1e8d2f15b) | Dec 29, 2020 |
| Gigabyte      | B75N                        | [549cdd3488](https://linux-hardware.org/?probe=549cdd3488) | Dec 28, 2020 |
| Huanan        | B75                         | [271064958a](https://linux-hardware.org/?probe=271064958a) | Dec 28, 2020 |
| Huanan        | B75                         | [c228d16dd8](https://linux-hardware.org/?probe=c228d16dd8) | Dec 28, 2020 |
| MSI           | MS-6570                     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| ASUSTek       | M3A78-T                     | [964df24952](https://linux-hardware.org/?probe=964df24952) | Dec 26, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [b7660e1e29](https://linux-hardware.org/?probe=b7660e1e29) | Dec 22, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [cb334d46a0](https://linux-hardware.org/?probe=cb334d46a0) | Dec 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [00f4ccd76b](https://linux-hardware.org/?probe=00f4ccd76b) | Dec 18, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [75f375567c](https://linux-hardware.org/?probe=75f375567c) | Dec 16, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [2d6a917448](https://linux-hardware.org/?probe=2d6a917448) | Dec 16, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [b77c353ce5](https://linux-hardware.org/?probe=b77c353ce5) | Dec 16, 2020 |
| MSI           | GF615M-P33 V2               | [437d0f7a16](https://linux-hardware.org/?probe=437d0f7a16) | Dec 16, 2020 |
| ASUSTek       | PRIME B350M-A               | [97aa12c990](https://linux-hardware.org/?probe=97aa12c990) | Dec 15, 2020 |
| Gigabyte      | A320M-H-CF                  | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |
| MSI           | H110M GAMING                | [7ceee152fd](https://linux-hardware.org/?probe=7ceee152fd) | Dec 12, 2020 |
| MSI           | H110M GAMING                | [6f568d6cec](https://linux-hardware.org/?probe=6f568d6cec) | Dec 12, 2020 |
| ASUSTek       | H81M-C                      | [cc7ccfac50](https://linux-hardware.org/?probe=cc7ccfac50) | Dec 11, 2020 |
| MSI           | B350 TOMAHAWK               | [d20ccb8aaf](https://linux-hardware.org/?probe=d20ccb8aaf) | Dec 10, 2020 |
| MSI           | H97 PC Mate                 | [22cbad4534](https://linux-hardware.org/?probe=22cbad4534) | Dec 09, 2020 |
| MSI           | H110M PRO-VD                | [ed9345a979](https://linux-hardware.org/?probe=ed9345a979) | Dec 08, 2020 |
| MSI           | MS-16GH                     | [8f5d0b74c4](https://linux-hardware.org/?probe=8f5d0b74c4) | Dec 06, 2020 |
| MSI           | MS-16GH                     | [1fd658b7f4](https://linux-hardware.org/?probe=1fd658b7f4) | Dec 06, 2020 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [7bbb057a12](https://linux-hardware.org/?probe=7bbb057a12) | Dec 05, 2020 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [7c3194b2ac](https://linux-hardware.org/?probe=7c3194b2ac) | Dec 04, 2020 |
| Shuttle       | FX70                        | [e32ab899c0](https://linux-hardware.org/?probe=e32ab899c0) | Dec 04, 2020 |
| Shuttle       | FX70                        | [baacccf39d](https://linux-hardware.org/?probe=baacccf39d) | Dec 04, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [2c52f626c8](https://linux-hardware.org/?probe=2c52f626c8) | Dec 01, 2020 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [e5d7bdea30](https://linux-hardware.org/?probe=e5d7bdea30) | Nov 27, 2020 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [da5f53dfff](https://linux-hardware.org/?probe=da5f53dfff) | Nov 26, 2020 |
| MSI           | 970A-G46                    | [d1dfee705a](https://linux-hardware.org/?probe=d1dfee705a) | Nov 24, 2020 |
| Dell          | 073MMW A02                  | [0bb3cb27dd](https://linux-hardware.org/?probe=0bb3cb27dd) | Nov 18, 2020 |
| Dell          | 073MMW A02                  | [b25225e211](https://linux-hardware.org/?probe=b25225e211) | Nov 17, 2020 |
| Gigabyte      | GA-880GA-UD3H               | [4ac51b2022](https://linux-hardware.org/?probe=4ac51b2022) | Nov 02, 2020 |
| Unknown       | Unknown                     | [01e13eca3a](https://linux-hardware.org/?probe=01e13eca3a) | Oct 27, 2020 |
| ASUSTek       | P5Q SE                      | [1080b0338d](https://linux-hardware.org/?probe=1080b0338d) | Oct 22, 2020 |
| Gigabyte      | GA-MA74GM-S2                | [0db1128411](https://linux-hardware.org/?probe=0db1128411) | Oct 22, 2020 |
| Gigabyte      | 945GM-S2                    | [3b722c2383](https://linux-hardware.org/?probe=3b722c2383) | Oct 12, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [1a34901153](https://linux-hardware.org/?probe=1a34901153) | Oct 12, 2020 |
| MSI           | Z170A GAMING M7             | [0adcb768e0](https://linux-hardware.org/?probe=0adcb768e0) | Oct 11, 2020 |
| MSI           | B450M-A PRO MAX             | [0901294419](https://linux-hardware.org/?probe=0901294419) | Oct 07, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [bcac6bcfaf](https://linux-hardware.org/?probe=bcac6bcfaf) | Oct 03, 2020 |
| ASUSTek       | P5Q SE                      | [298c553263](https://linux-hardware.org/?probe=298c553263) | Oct 03, 2020 |
| ASRock        | Z77 Extreme4                | [b1832be82c](https://linux-hardware.org/?probe=b1832be82c) | Oct 02, 2020 |
| ASRock        | B450M Pro4                  | [a75242fcb6](https://linux-hardware.org/?probe=a75242fcb6) | Sep 30, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [eea0437e0d](https://linux-hardware.org/?probe=eea0437e0d) | Sep 29, 2020 |
| MSI           | Z270 TOMAHAWK               | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| MSI           | Z390-A PRO                  | [b16fff28fe](https://linux-hardware.org/?probe=b16fff28fe) | Sep 27, 2020 |
| MSI           | 970 GAMING                  | [1155ab9a1d](https://linux-hardware.org/?probe=1155ab9a1d) | Sep 22, 2020 |
| MSI           | 970 GAMING                  | [1bd55ba8f2](https://linux-hardware.org/?probe=1bd55ba8f2) | Sep 22, 2020 |
| ASUSTek       | M5A78L-M LX/BR              | [ca91363b61](https://linux-hardware.org/?probe=ca91363b61) | Sep 16, 2020 |
| Gigabyte      | 945GCMX-S2                  | [de93a9609f](https://linux-hardware.org/?probe=de93a9609f) | Sep 10, 2020 |
| Gigabyte      | 945GCMX-S2                  | [cd32a01cf3](https://linux-hardware.org/?probe=cd32a01cf3) | Aug 21, 2020 |
| MSI           | Z390-A PRO                  | [f1f73bc945](https://linux-hardware.org/?probe=f1f73bc945) | Aug 14, 2020 |
| Gigabyte      | GA-MA785GMT-UD2H            | [d437b7916a](https://linux-hardware.org/?probe=d437b7916a) | Aug 09, 2020 |
| Gigabyte      | B450M S2H                   | [f1fa2ce17a](https://linux-hardware.org/?probe=f1fa2ce17a) | Aug 01, 2020 |
| Gigabyte      | B450M S2H                   | [dc136b3989](https://linux-hardware.org/?probe=dc136b3989) | Aug 01, 2020 |
| Gigabyte      | H61M-S2PV                   | [c7216a691e](https://linux-hardware.org/?probe=c7216a691e) | Jul 26, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [1d90d104e8](https://linux-hardware.org/?probe=1d90d104e8) | Jul 23, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [966f47614c](https://linux-hardware.org/?probe=966f47614c) | Jul 22, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [5437b13e2e](https://linux-hardware.org/?probe=5437b13e2e) | Jul 22, 2020 |
| ASUSTek       | P5S-MX SE                   | [342406d36f](https://linux-hardware.org/?probe=342406d36f) | Jul 19, 2020 |
| ASUSTek       | M5A97 R2.0                  | [125eba3c85](https://linux-hardware.org/?probe=125eba3c85) | Jul 17, 2020 |
| ASUSTek       | P8Z77-V LX                  | [3168802419](https://linux-hardware.org/?probe=3168802419) | Jul 14, 2020 |
| ASUSTek       | M5A97 R2.0                  | [08cbac2186](https://linux-hardware.org/?probe=08cbac2186) | Jul 14, 2020 |
| Gigabyte      | G31M-ES2L                   | [bb1d0d1c77](https://linux-hardware.org/?probe=bb1d0d1c77) | Jul 05, 2020 |
| Gigabyte      | G31M-ES2L                   | [4648006d19](https://linux-hardware.org/?probe=4648006d19) | Jul 03, 2020 |
| MSI           | H110M PRO-VD                | [4b484acfb7](https://linux-hardware.org/?probe=4b484acfb7) | Jun 29, 2020 |
| MSI           | H97 PC Mate                 | [9ff9899cf2](https://linux-hardware.org/?probe=9ff9899cf2) | Jun 27, 2020 |
| Gigabyte      | Z68P-DS3                    | [364b017d67](https://linux-hardware.org/?probe=364b017d67) | Jun 27, 2020 |
| ASUSTek       | P9X79 PRO                   | [797a6712a7](https://linux-hardware.org/?probe=797a6712a7) | Jun 25, 2020 |
| Gigabyte      | A320M-S2H-CF                | [3541aaf17d](https://linux-hardware.org/?probe=3541aaf17d) | Jun 09, 2020 |
| Gigabyte      | A320M-S2H-CF                | [befc9e682c](https://linux-hardware.org/?probe=befc9e682c) | Jun 09, 2020 |
| ASUSTek       | PRIME B350M-A               | [5b3ae3f335](https://linux-hardware.org/?probe=5b3ae3f335) | Jun 08, 2020 |
| Gigabyte      | B450M DS3H-CF               | [c4d0b5690e](https://linux-hardware.org/?probe=c4d0b5690e) | Jun 05, 2020 |
| Gigabyte      | B450M DS3H-CF               | [6b494598fd](https://linux-hardware.org/?probe=6b494598fd) | Jun 05, 2020 |
| ASUSTek       | M5A78L-M LX3                | [3c0d62b5b3](https://linux-hardware.org/?probe=3c0d62b5b3) | Jun 05, 2020 |
| ASUSTek       | PRIME B450M-K               | [a114fed701](https://linux-hardware.org/?probe=a114fed701) | Jun 03, 2020 |
| Gigabyte      | Z68P-DS3                    | [b11d0e148f](https://linux-hardware.org/?probe=b11d0e148f) | May 28, 2020 |
| Gigabyte      | B75M-D3H                    | [ee79ec794d](https://linux-hardware.org/?probe=ee79ec794d) | May 25, 2020 |
| ASRock        | A780LM                      | [d2b3819db6](https://linux-hardware.org/?probe=d2b3819db6) | May 24, 2020 |
| Gigabyte      | H61M-DS2                    | [3d3120cc63](https://linux-hardware.org/?probe=3d3120cc63) | May 23, 2020 |
| Gigabyte      | H61M-DS2                    | [2e2c1b2388](https://linux-hardware.org/?probe=2e2c1b2388) | May 20, 2020 |
| Gigabyte      | P31-DS3L                    | [8532521b87](https://linux-hardware.org/?probe=8532521b87) | May 17, 2020 |
| MSI           | GF615M-P33 V2               | [e6c02461aa](https://linux-hardware.org/?probe=e6c02461aa) | May 14, 2020 |
| Gigabyte      | G41M-Combo                  | [536d0211c3](https://linux-hardware.org/?probe=536d0211c3) | May 13, 2020 |
| ASRock        | X370 Taichi                 | [baf6d7acc7](https://linux-hardware.org/?probe=baf6d7acc7) | May 05, 2020 |
| Foxconn       | G31MV/G31MV-K FAB           | [2c079a8323](https://linux-hardware.org/?probe=2c079a8323) | May 05, 2020 |
| ASUSTek       | H61M-K                      | [0adb0b5b10](https://linux-hardware.org/?probe=0adb0b5b10) | May 03, 2020 |
| ASUSTek       | H61M-K                      | [f9ff31abf7](https://linux-hardware.org/?probe=f9ff31abf7) | May 02, 2020 |
| Gigabyte      | GA-MA785GMT-UD2H            | [29beb62339](https://linux-hardware.org/?probe=29beb62339) | Apr 27, 2020 |
| ASUSTek       | VM40B                       | [acf2922656](https://linux-hardware.org/?probe=acf2922656) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | [2fc777ae6a](https://linux-hardware.org/?probe=2fc777ae6a) | Apr 26, 2020 |
| MSI           | 990XA-GD55                  | [bbda0a2590](https://linux-hardware.org/?probe=bbda0a2590) | Apr 25, 2020 |
| MSI           | 970 GAMING                  | [416fc908da](https://linux-hardware.org/?probe=416fc908da) | Apr 23, 2020 |
| MSI           | 970 GAMING                  | [f23275d0e5](https://linux-hardware.org/?probe=f23275d0e5) | Apr 23, 2020 |
| Gigabyte      | G31M-ES2L                   | [3985bbbb7a](https://linux-hardware.org/?probe=3985bbbb7a) | Apr 20, 2020 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | [3712a61f67](https://linux-hardware.org/?probe=3712a61f67) | Apr 17, 2020 |
| Gigabyte      | AX370-Gaming K7             | [61e978a1aa](https://linux-hardware.org/?probe=61e978a1aa) | Apr 14, 2020 |
| Gigabyte      | AX370-Gaming K7             | [ab1712b2a9](https://linux-hardware.org/?probe=ab1712b2a9) | Apr 14, 2020 |
| MSI           | H110M PRO-VD                | [a69e76d844](https://linux-hardware.org/?probe=a69e76d844) | Apr 11, 2020 |
| ASRock        | B450M Pro4                  | [795e66049a](https://linux-hardware.org/?probe=795e66049a) | Apr 09, 2020 |
| Gigabyte      | Z170X-Ultra Gaming-CF       | [d24068a7c3](https://linux-hardware.org/?probe=d24068a7c3) | Apr 07, 2020 |
| ECS           | A780GM-A Ultra              | [428265372a](https://linux-hardware.org/?probe=428265372a) | Apr 03, 2020 |
| Gigabyte      | G31M-S2L                    | [70c42f24c2](https://linux-hardware.org/?probe=70c42f24c2) | Mar 31, 2020 |
| Gigabyte      | M68MT-S2                    | [4e25b158dc](https://linux-hardware.org/?probe=4e25b158dc) | Mar 30, 2020 |
| Gigabyte      | G31M-ES2L                   | [83c2d10d4f](https://linux-hardware.org/?probe=83c2d10d4f) | Mar 28, 2020 |
| ASUSTek       | M2N68-AM SE2                | [1f25ebdc0f](https://linux-hardware.org/?probe=1f25ebdc0f) | Mar 20, 2020 |
| MSI           | 970A-G46                    | [b4bc30bf7c](https://linux-hardware.org/?probe=b4bc30bf7c) | Mar 19, 2020 |
| ASUSTek       | H61M-K                      | [26bf5cdb81](https://linux-hardware.org/?probe=26bf5cdb81) | Mar 17, 2020 |
| ASUSTek       | H81M-D                      | [8eb2da14fe](https://linux-hardware.org/?probe=8eb2da14fe) | Mar 09, 2020 |
| ASUSTek       | H81M-D                      | [11f51a7693](https://linux-hardware.org/?probe=11f51a7693) | Mar 08, 2020 |
| Gigabyte      | EX58-EXTREME                | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
| ASUSTek       | GL12CM                      | [f094f68a37](https://linux-hardware.org/?probe=f094f68a37) | Mar 01, 2020 |
| MSI           | G41M-P33 Combo              | [9d4535f44d](https://linux-hardware.org/?probe=9d4535f44d) | Mar 01, 2020 |
| MSI           | G41M-P33 Combo              | [96df14303e](https://linux-hardware.org/?probe=96df14303e) | Mar 01, 2020 |
| Gigabyte      | EX58-EXTREME                | [2ce62d5ef2](https://linux-hardware.org/?probe=2ce62d5ef2) | Feb 23, 2020 |
| Gigabyte      | G31M-ES2L                   | [104c7c39a7](https://linux-hardware.org/?probe=104c7c39a7) | Feb 16, 2020 |
| Dell          | 0FPP7F A00                  | [b6e88b98f7](https://linux-hardware.org/?probe=b6e88b98f7) | Jan 29, 2020 |
| ASUSTek       | P5B-VM                      | [2097120922](https://linux-hardware.org/?probe=2097120922) | Jan 28, 2020 |
| Gigabyte      | GA-MA785GMT-UD2H            | [5826b362c6](https://linux-hardware.org/?probe=5826b362c6) | Jan 25, 2020 |
| Gigabyte      | B450M S2H                   | [7a526509fc](https://linux-hardware.org/?probe=7a526509fc) | Jan 21, 2020 |
| MSI           | B350M GAMING PRO            | [f686ee5b7f](https://linux-hardware.org/?probe=f686ee5b7f) | Jan 18, 2020 |
| MSI           | B350M GAMING PRO            | [a2078dbc96](https://linux-hardware.org/?probe=a2078dbc96) | Jan 18, 2020 |
| ASUSTek       | M2N                         | [74f56d602e](https://linux-hardware.org/?probe=74f56d602e) | Jan 14, 2020 |
| ASUSTek       | M2N                         | [e70e3be009](https://linux-hardware.org/?probe=e70e3be009) | Jan 14, 2020 |
| Gigabyte      | B450M S2H                   | [536eec1c4f](https://linux-hardware.org/?probe=536eec1c4f) | Jan 03, 2020 |
| MSI           | X370 GAMING PLUS            | [742996f1c9](https://linux-hardware.org/?probe=742996f1c9) | Jan 03, 2020 |
| Gigabyte      | GA-MA785GMT-UD2H            | [fbbf365bf8](https://linux-hardware.org/?probe=fbbf365bf8) | Dec 20, 2019 |
| Unknown       | A780LM-M                    | [0c1e92090b](https://linux-hardware.org/?probe=0c1e92090b) | Dec 10, 2019 |
| Unknown       | A780LM-M                    | [a116be1ddb](https://linux-hardware.org/?probe=a116be1ddb) | Dec 10, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [dcb98cb8e2](https://linux-hardware.org/?probe=dcb98cb8e2) | Dec 05, 2019 |
| Lenovo        | 3098 NOK                    | [62cc7afe5e](https://linux-hardware.org/?probe=62cc7afe5e) | Dec 03, 2019 |
| Lenovo        | 3098 NOK                    | [355d2dd10f](https://linux-hardware.org/?probe=355d2dd10f) | Dec 03, 2019 |
| Lenovo        | 3098 NOK                    | [4c9fff8b94](https://linux-hardware.org/?probe=4c9fff8b94) | Nov 27, 2019 |
| Lenovo        | 3098 NOK                    | [b261a48347](https://linux-hardware.org/?probe=b261a48347) | Nov 27, 2019 |
| ASUSTek       | J1800I-C                    | [0f8348d5a2](https://linux-hardware.org/?probe=0f8348d5a2) | Nov 12, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [8ede99a49a](https://linux-hardware.org/?probe=8ede99a49a) | Nov 12, 2019 |
| HP            | 18E5                        | [cd31c1cbc1](https://linux-hardware.org/?probe=cd31c1cbc1) | Nov 11, 2019 |
| HP            | 18E5                        | [9ae0df93c4](https://linux-hardware.org/?probe=9ae0df93c4) | Nov 10, 2019 |
| MSI           | B350 PC MATE                | [94a2ff5e6c](https://linux-hardware.org/?probe=94a2ff5e6c) | Nov 09, 2019 |
| MSI           | G41M-P26                    | [d6ff689892](https://linux-hardware.org/?probe=d6ff689892) | Oct 29, 2019 |
| MSI           | G41M-P26                    | [57d12187db](https://linux-hardware.org/?probe=57d12187db) | Oct 29, 2019 |
| Foxconn       | A6GMV 0A                    | [fa7720f25a](https://linux-hardware.org/?probe=fa7720f25a) | Oct 23, 2019 |
| ASUSTek       | M5A97 LE R2.0               | [4cd5334584](https://linux-hardware.org/?probe=4cd5334584) | Oct 15, 2019 |
| ASUSTek       | STRIX Z270E GAMING          | [c6e5717425](https://linux-hardware.org/?probe=c6e5717425) | Oct 13, 2019 |
| Foxconn       | A6GMV 0A                    | [bbf96d6701](https://linux-hardware.org/?probe=bbf96d6701) | Oct 11, 2019 |
| Gigabyte      | X58A-UD5                    | [c1cd5017a5](https://linux-hardware.org/?probe=c1cd5017a5) | Oct 05, 2019 |
| ASUSTek       | NODUSM                      | [eedaaea2d7](https://linux-hardware.org/?probe=eedaaea2d7) | Oct 04, 2019 |
| ASUSTek       | NODUSM                      | [352ceaba6f](https://linux-hardware.org/?probe=352ceaba6f) | Oct 04, 2019 |
| MSI           | H81M-P33                    | [5846d2096b](https://linux-hardware.org/?probe=5846d2096b) | Sep 20, 2019 |
| MSI           | H81M-P33                    | [1a759c4848](https://linux-hardware.org/?probe=1a759c4848) | Sep 15, 2019 |
| Gigabyte      | X38-DQ6                     | [fdc304f1cb](https://linux-hardware.org/?probe=fdc304f1cb) | Sep 10, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [53968b7687](https://linux-hardware.org/?probe=53968b7687) | Sep 08, 2019 |
| Intel         | H55                         | [7e7f863e27](https://linux-hardware.org/?probe=7e7f863e27) | Sep 03, 2019 |
| HP            | ProLiant MicroServer Gen... | [6ef39dc5a4](https://linux-hardware.org/?probe=6ef39dc5a4) | Aug 05, 2019 |
| HP            | ProLiant MicroServer Gen... | [fdc910928e](https://linux-hardware.org/?probe=fdc910928e) | Aug 02, 2019 |
| HP            | ProLiant MicroServer Gen... | [2a7ca3c3be](https://linux-hardware.org/?probe=2a7ca3c3be) | Aug 02, 2019 |
| ASUSTek       | P8H61-M LX                  | [1114b40a02](https://linux-hardware.org/?probe=1114b40a02) | Jul 16, 2019 |
| ASUSTek       | M5A78L LE                   | [c9e2f0a4cb](https://linux-hardware.org/?probe=c9e2f0a4cb) | Jul 14, 2019 |
| Gigabyte      | H61M-D2-B3                  | [ab4926fdff](https://linux-hardware.org/?probe=ab4926fdff) | Jun 27, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | [3c4c1e40c5](https://linux-hardware.org/?probe=3c4c1e40c5) | Jun 17, 2019 |
| MSI           | 970A-G43                    | [d6764f0c12](https://linux-hardware.org/?probe=d6764f0c12) | Jun 17, 2019 |
| ASUSTek       | A58M-K                      | [3fd6dbae3e](https://linux-hardware.org/?probe=3fd6dbae3e) | Jun 08, 2019 |
| ASUSTek       | M5A78L-M LX3                | [0a8f265f9a](https://linux-hardware.org/?probe=0a8f265f9a) | May 26, 2019 |
| ASUSTek       | P5LD2EB2-DHS                | [b57105bb3f](https://linux-hardware.org/?probe=b57105bb3f) | May 25, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | [499d7d839c](https://linux-hardware.org/?probe=499d7d839c) | May 19, 2019 |
| Dell          | 0VFD52 A00                  | [b727b9b17d](https://linux-hardware.org/?probe=b727b9b17d) | May 19, 2019 |
| Unknown       | Unknown                     | [9b1b3a3479](https://linux-hardware.org/?probe=9b1b3a3479) | May 13, 2019 |
| ASUSTek       | H81M-K                      | [b2cd0963b2](https://linux-hardware.org/?probe=b2cd0963b2) | Apr 29, 2019 |
| Gigabyte      | GA-780T-D3L                 | [76a32de1f1](https://linux-hardware.org/?probe=76a32de1f1) | Apr 27, 2019 |
| ASUSTek       | P5RD1-VM                    | [ba9ccbd3a5](https://linux-hardware.org/?probe=ba9ccbd3a5) | Apr 22, 2019 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [c156f0ab27](https://linux-hardware.org/?probe=c156f0ab27) | Apr 18, 2019 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [7287c465d1](https://linux-hardware.org/?probe=7287c465d1) | Apr 18, 2019 |
| ASUSTek       | P5G41T-M LX                 | [8eba3d2125](https://linux-hardware.org/?probe=8eba3d2125) | Apr 12, 2019 |
| ASRock        | N68-VS3 FX                  | [10449047da](https://linux-hardware.org/?probe=10449047da) | Apr 10, 2019 |
| ASRock        | N68-VS3 FX                  | [6b99379d75](https://linux-hardware.org/?probe=6b99379d75) | Apr 04, 2019 |
| ASRock        | N68-VS3 FX                  | [7dfc4051f5](https://linux-hardware.org/?probe=7dfc4051f5) | Apr 04, 2019 |
| Intel         | DQ965GF AAD41676-601        | [1847b52353](https://linux-hardware.org/?probe=1847b52353) | Mar 30, 2019 |
| Gigabyte      | G31M-ES2L                   | [7a1280805d](https://linux-hardware.org/?probe=7a1280805d) | Mar 20, 2019 |
| Gigabyte      | G31M-ES2L                   | [2dddfc91ac](https://linux-hardware.org/?probe=2dddfc91ac) | Mar 20, 2019 |
| Gigabyte      | G41M-ES2L                   | [083115b27b](https://linux-hardware.org/?probe=083115b27b) | Mar 18, 2019 |
| MSI           | Z370 GAMING PRO CARBON      | [62128222fa](https://linux-hardware.org/?probe=62128222fa) | Mar 04, 2019 |
| Lenovo        | ThinkCentre M58p 7357A18    | [ae67a79df0](https://linux-hardware.org/?probe=ae67a79df0) | Mar 03, 2019 |
| MSI           | Z170I GAMING PRO AC         | [51bd9824fa](https://linux-hardware.org/?probe=51bd9824fa) | Feb 10, 2019 |
| Gigabyte      | G41M-Combo                  | [f595a31a86](https://linux-hardware.org/?probe=f595a31a86) | Jan 12, 2019 |
| ASUSTek       | PRIME B350M-A               | [80cd54ac1e](https://linux-hardware.org/?probe=80cd54ac1e) | Dec 30, 2018 |
| ECS           | H61H2-M13                   | [442939fe21](https://linux-hardware.org/?probe=442939fe21) | Dec 30, 2018 |
| Foxconn       | G31MV/G31MV-K FAB           | [7f906bdc45](https://linux-hardware.org/?probe=7f906bdc45) | Dec 13, 2018 |
| Acer          | Aspire M3920                | [6e1aa4c979](https://linux-hardware.org/?probe=6e1aa4c979) | Dec 01, 2018 |
| ASUSTek       | Z170-P                      | [8a7bed70fc](https://linux-hardware.org/?probe=8a7bed70fc) | Nov 29, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [d56ba68bc4](https://linux-hardware.org/?probe=d56ba68bc4) | Oct 31, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [672da646fe](https://linux-hardware.org/?probe=672da646fe) | Oct 27, 2018 |
| ASRock        | G41M-VS3                    | [2c1dd09a17](https://linux-hardware.org/?probe=2c1dd09a17) | Oct 26, 2018 |
| Foxconn       | G31MV/G31MV-K FAB           | [8b5216def0](https://linux-hardware.org/?probe=8b5216def0) | Oct 16, 2018 |
| AOpen         | EZ65 9172310001             | [39b1b0e3fe](https://linux-hardware.org/?probe=39b1b0e3fe) | Oct 09, 2018 |
| ASUSTek       | D520MT-K                    | [4bc55612d4](https://linux-hardware.org/?probe=4bc55612d4) | Jun 06, 2018 |
| ASUSTek       | D520MT-K                    | [9e60a0d73e](https://linux-hardware.org/?probe=9e60a0d73e) | Jun 06, 2018 |
| ASUSTek       | P5Q TURBO                   | [08ba62f605](https://linux-hardware.org/?probe=08ba62f605) | Mar 25, 2018 |
| ASUSTek       | P5GC-MX/1333                | [0c4c66358b](https://linux-hardware.org/?probe=0c4c66358b) | Mar 01, 2017 |
| Intel         | DH55TC AAE70932-206         | [92b45f3171](https://linux-hardware.org/?probe=92b45f3171) | Nov 01, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Turkey/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 55       | 12.11%  |
| Ubuntu 18.04       | 45       | 9.91%   |
| Ubuntu 22.04       | 24       | 5.29%   |
| OpenMandriva 4.3   | 18       | 3.96%   |
| Arch Rolling       | 18       | 3.96%   |
| KDE neon 20.04     | 11       | 2.42%   |
| ArcoLinux Rolling  | 10       | 2.2%    |
| Zorin 16           | 8        | 1.76%   |
| Debian 11          | 8        | 1.76%   |
| Linux Mint 20.3    | 7        | 1.54%   |
| Fedora 33          | 7        | 1.54%   |
| Linux Mint 21      | 6        | 1.32%   |
| Linux Mint 20.1    | 6        | 1.32%   |
| Linux Mint 20      | 6        | 1.32%   |
| Fedora 37          | 6        | 1.32%   |
| Fedora 35          | 6        | 1.32%   |
| Arch               | 6        | 1.32%   |
| Ubuntu 16.04       | 5        | 1.1%    |
| ROSA R10           | 5        | 1.1%    |
| Pardus 21.4        | 5        | 1.1%    |
| Pardus 21.2        | 5        | 1.1%    |
| OpenMandriva 4.2   | 5        | 1.1%    |
| OpenMandriva 23.01 | 5        | 1.1%    |
| Manjaro            | 5        | 1.1%    |
| Linux Mint 21.1    | 5        | 1.1%    |
| KDE neon 22.04     | 5        | 1.1%    |
| Fedora 38          | 5        | 1.1%    |
| Fedora 36          | 5        | 1.1%    |
| Fedora 31          | 5        | 1.1%    |
| Debian 10          | 5        | 1.1%    |
| Ubuntu 23.04       | 4        | 0.88%   |
| Ubuntu 20.10       | 4        | 0.88%   |
| Ubuntu 19.04       | 4        | 0.88%   |
| Pop!_OS 20.04      | 4        | 0.88%   |
| Pardus 21.3        | 4        | 0.88%   |
| Xero Rolling       | 3        | 0.66%   |
| OpenMandriva 4.50  | 3        | 0.66%   |
| OpenMandriva 23.03 | 3        | 0.66%   |
| KDE neon 18.04     | 3        | 0.66%   |
| Fedora 34          | 3        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 149      | 33.63%  |
| OpenMandriva | 35       | 7.9%    |
| Linux Mint   | 35       | 7.9%    |
| Fedora       | 34       | 7.67%   |
| Arch         | 23       | 5.19%   |
| KDE neon     | 19       | 4.29%   |
| Debian       | 17       | 3.84%   |
| Pardus       | 16       | 3.61%   |
| Manjaro      | 12       | 2.71%   |
| Zorin        | 10       | 2.26%   |
| ArcoLinux    | 10       | 2.26%   |
| ROSA         | 9        | 2.03%   |
| Pop!_OS      | 9        | 2.03%   |
| Elementary   | 8        | 1.81%   |
| Kubuntu      | 6        | 1.35%   |
| Endless      | 6        | 1.35%   |
| Xubuntu      | 4        | 0.9%    |
| Lubuntu      | 4        | 0.9%    |
| Xero         | 3        | 0.68%   |
| openSUSE     | 3        | 0.68%   |
| Kali         | 3        | 0.68%   |
| EndeavourOS  | 3        | 0.68%   |
| CentOS       | 3        | 0.68%   |
| Ubuntu Unity | 2        | 0.45%   |
| Pisi         | 2        | 0.45%   |
| Nobara       | 2        | 0.45%   |
| LMDE         | 2        | 0.45%   |
| BlackPanther | 2        | 0.45%   |
| Void Linux   | 1        | 0.23%   |
| Ubuntu MATE  | 1        | 0.23%   |
| SteamOS      | 1        | 0.23%   |
| Reborn OS    | 1        | 0.23%   |
| Parrot       | 1        | 0.23%   |
| MX           | 1        | 0.23%   |
| Makulu       | 1        | 0.23%   |
| Garuda Linux | 1        | 0.23%   |
| Drauger OS   | 1        | 0.23%   |
| Clear Linux  | 1        | 0.23%   |
| Artix        | 1        | 0.23%   |
| antergos     | 1        | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 17       | 3.43%   |
| 5.15.0-56-generic        | 8        | 1.61%   |
| 5.8.0-43-generic         | 6        | 1.21%   |
| 5.4.0-42-generic         | 6        | 1.21%   |
| 6.1.1-desktop-1omv2290   | 5        | 1.01%   |
| 5.4.0-48-generic         | 5        | 1.01%   |
| 5.4.0-33-generic         | 5        | 1.01%   |
| 5.10.14-desktop-1omv4002 | 5        | 1.01%   |
| 5.10.0-21-amd64          | 5        | 1.01%   |
| 5.0.0-37-generic         | 5        | 1.01%   |
| 4.18.0-15-generic        | 5        | 1.01%   |
| 5.8.0-48-generic         | 4        | 0.81%   |
| 5.4.0-58-generic         | 4        | 0.81%   |
| 5.4.0-31-generic         | 4        | 0.81%   |
| 5.4.0-26-generic         | 4        | 0.81%   |
| 5.3.0-46-generic         | 4        | 0.81%   |
| 5.15.0-78-generic        | 4        | 0.81%   |
| 5.15.0-58-generic        | 4        | 0.81%   |
| 5.15.0-48-generic        | 4        | 0.81%   |
| 5.13.0-52-generic        | 4        | 0.81%   |
| 6.2.6-desktop-1omv2390   | 3        | 0.6%    |
| 6.2.0-20-generic         | 3        | 0.6%    |
| 5.8.0-14-generic         | 3        | 0.6%    |
| 5.4.0-73-generic         | 3        | 0.6%    |
| 5.4.0-72-generic         | 3        | 0.6%    |
| 5.4.0-56-generic         | 3        | 0.6%    |
| 5.4.0-29-generic         | 3        | 0.6%    |
| 5.3.0-42-generic         | 3        | 0.6%    |
| 5.19.0-43-generic        | 3        | 0.6%    |
| 5.19.0-41-generic        | 3        | 0.6%    |
| 5.15.0-50-generic        | 3        | 0.6%    |
| 5.15.0-27-generic        | 3        | 0.6%    |
| 5.13.0-39-generic        | 3        | 0.6%    |
| 5.11.0-38-generic        | 3        | 0.6%    |
| 5.11.0-37-generic        | 3        | 0.6%    |
| 5.11.0-27-generic        | 3        | 0.6%    |
| 5.10.0-8-amd64           | 3        | 0.6%    |
| 5.10.0-20-amd64          | 3        | 0.6%    |
| 5.10.0-14-amd64          | 3        | 0.6%    |
| 5.10.0-13-amd64          | 3        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 69       | 14.53%  |
| 5.15.0  | 42       | 8.84%   |
| 5.8.0   | 26       | 5.47%   |
| 5.10.0  | 26       | 5.47%   |
| 5.13.0  | 21       | 4.42%   |
| 5.11.0  | 21       | 4.42%   |
| 4.15.0  | 20       | 4.21%   |
| 5.16.7  | 17       | 3.58%   |
| 5.0.0   | 17       | 3.58%   |
| 5.3.0   | 15       | 3.16%   |
| 4.18.0  | 12       | 2.53%   |
| 5.19.0  | 11       | 2.32%   |
| 6.1.1   | 7        | 1.47%   |
| 4.19.0  | 7        | 1.47%   |
| 6.2.0   | 5        | 1.05%   |
| 5.10.14 | 5        | 1.05%   |
| 6.2.6   | 3        | 0.63%   |
| 6.2.10  | 3        | 0.63%   |
| 5.15.14 | 3        | 0.63%   |
| 5.11.10 | 3        | 0.63%   |
| 4.9.60  | 3        | 0.63%   |
| 4.9.124 | 3        | 0.63%   |
| 4.4.0   | 3        | 0.63%   |
| 6.4.3   | 2        | 0.42%   |
| 6.4.2   | 2        | 0.42%   |
| 6.3.8   | 2        | 0.42%   |
| 6.3.6   | 2        | 0.42%   |
| 6.3.5   | 2        | 0.42%   |
| 6.3.1   | 2        | 0.42%   |
| 6.2.9   | 2        | 0.42%   |
| 6.2.11  | 2        | 0.42%   |
| 6.1.9   | 2        | 0.42%   |
| 6.1.8   | 2        | 0.42%   |
| 6.1.7   | 2        | 0.42%   |
| 6.1.0   | 2        | 0.42%   |
| 6.0.9   | 2        | 0.42%   |
| 6.0.0   | 2        | 0.42%   |
| 5.9.11  | 2        | 0.42%   |
| 5.8.6   | 2        | 0.42%   |
| 5.8.11  | 2        | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 71       | 15.11%  |
| 5.15    | 56       | 11.91%  |
| 5.10    | 37       | 7.87%   |
| 5.8     | 30       | 6.38%   |
| 5.11    | 30       | 6.38%   |
| 5.16    | 25       | 5.32%   |
| 5.13    | 21       | 4.47%   |
| 6.1     | 20       | 4.26%   |
| 5.3     | 20       | 4.26%   |
| 4.15    | 20       | 4.26%   |
| 6.2     | 18       | 3.83%   |
| 5.19    | 18       | 3.83%   |
| 5.0     | 17       | 3.62%   |
| 4.18    | 14       | 2.98%   |
| 6.3     | 10       | 2.13%   |
| 4.19    | 9        | 1.91%   |
| 6.4     | 6        | 1.28%   |
| 6.0     | 6        | 1.28%   |
| 5.18    | 6        | 1.28%   |
| 5.9     | 5        | 1.06%   |
| 5.17    | 5        | 1.06%   |
| 5.14    | 5        | 1.06%   |
| 4.9     | 5        | 1.06%   |
| 5.6     | 3        | 0.64%   |
| 5.12    | 3        | 0.64%   |
| 4.4     | 3        | 0.64%   |
| 4.1     | 2        | 0.43%   |
| 5.7     | 1        | 0.21%   |
| 5.5     | 1        | 0.21%   |
| 4.13    | 1        | 0.21%   |
| 4.12    | 1        | 0.21%   |
| 4.10    | 1        | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 413      | 97.41%  |
| i686   | 11       | 2.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 187      | 41.93%  |
| KDE5       | 89       | 19.96%  |
| Unknown    | 55       | 12.33%  |
| XFCE       | 40       | 8.97%   |
| X-Cinnamon | 23       | 5.16%   |
| KDE        | 14       | 3.14%   |
| Pantheon   | 8        | 1.79%   |
| MATE       | 6        | 1.35%   |
| Cinnamon   | 6        | 1.35%   |
| KDE4       | 4        | 0.9%    |
| Unity      | 2        | 0.45%   |
| sway       | 2        | 0.45%   |
| LXQt       | 2        | 0.45%   |
| LXDE       | 2        | 0.45%   |
| Hyprland   | 2        | 0.45%   |
| openbox    | 1        | 0.22%   |
| i3         | 1        | 0.22%   |
| default    | 1        | 0.22%   |
| Deepin     | 1        | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 348      | 79.82%  |
| Wayland | 62       | 14.22%  |
| Unknown | 20       | 4.59%   |
| Tty     | 6        | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 221      | 50.11%  |
| SDDM    | 78       | 17.69%  |
| GDM3    | 48       | 10.88%  |
| LightDM | 41       | 9.3%    |
| GDM     | 37       | 8.39%   |
| TDM     | 9        | 2.04%   |
| KDM     | 4        | 0.91%   |
| SLiM    | 1        | 0.23%   |
| Ly      | 1        | 0.23%   |
| LXDM    | 1        | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| tr_TR   | 187      | 42.89%  |
| en_US   | 172      | 39.45%  |
| Unknown | 57       | 13.07%  |
| en_GB   | 9        | 2.06%   |
| C       | 7        | 1.61%   |
| POSIX   | 1        | 0.23%   |
| es_ES   | 1        | 0.23%   |
| en_AU   | 1        | 0.23%   |
| ar_EG   | 1        | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 260      | 60.05%  |
| EFI  | 173      | 39.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 324      | 73.8%   |
| Btrfs   | 44       | 10.02%  |
| Overlay | 36       | 8.2%    |
| Unknown | 18       | 4.1%    |
| Tmpfs   | 8        | 1.82%   |
| Xfs     | 4        | 0.91%   |
| Ext2    | 3        | 0.68%   |
| Zfs     | 2        | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 244      | 56.09%  |
| GPT     | 142      | 32.64%  |
| MBR     | 49       | 11.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 346      | 80.47%  |
| Yes       | 84       | 19.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 262      | 59.68%  |
| Yes       | 177      | 40.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 140      | 33.02%  |
| Gigabyte Technology | 93       | 21.93%  |
| MSI                 | 82       | 19.34%  |
| Hewlett-Packard     | 15       | 3.54%   |
| ASRock              | 12       | 2.83%   |
| Lenovo              | 8        | 1.89%   |
| Foxconn             | 8        | 1.89%   |
| Dell                | 8        | 1.89%   |
| Unknown             | 8        | 1.89%   |
| Intel               | 7        | 1.65%   |
| ECS                 | 7        | 1.65%   |
| Pegatron            | 6        | 1.42%   |
| Casper              | 6        | 1.42%   |
| Acer                | 4        | 0.94%   |
| Huanan              | 3        | 0.71%   |
| Fujitsu Siemens     | 2        | 0.47%   |
| Fujitsu             | 2        | 0.47%   |
| Biostar             | 2        | 0.47%   |
| Apple               | 2        | 0.47%   |
| Zillion             | 1        | 0.24%   |
| XDO.AI              | 1        | 0.24%   |
| Vestel              | 1        | 0.24%   |
| SYWZ                | 1        | 0.24%   |
| Shuttle             | 1        | 0.24%   |
| IBM                 | 1        | 0.24%   |
| FIC                 | 1        | 0.24%   |
| AOpen               | 1        | 0.24%   |
| ABIT                | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 10       | 2.36%   |
| ASUS All Series              | 9        | 2.12%   |
| Gigabyte B450M S2H           | 7        | 1.65%   |
| MSI MS-7C02                  | 5        | 1.18%   |
| Gigabyte G31M-ES2L           | 5        | 1.18%   |
| Gigabyte A320M-S2H           | 5        | 1.18%   |
| MSI MS-7A34                  | 4        | 0.94%   |
| MSI MS-7817                  | 4        | 0.94%   |
| MSI MS-7693                  | 4        | 0.94%   |
| Gigabyte G41M-ES2L           | 4        | 0.94%   |
| Pegatron IPXSB-H61           | 3        | 0.71%   |
| MSI MS-7C09                  | 3        | 0.71%   |
| MSI MS-7B86                  | 3        | 0.71%   |
| MSI MS-7A38                  | 3        | 0.71%   |
| MSI MS-7996                  | 3        | 0.71%   |
| MSI MS-7360                  | 3        | 0.71%   |
| Gigabyte M61SME-S2           | 3        | 0.71%   |
| ASUS TUF B450-PLUS GAMING    | 3        | 0.71%   |
| ASUS PRIME B450M-K II        | 3        | 0.71%   |
| ASUS PRIME B450M-K           | 3        | 0.71%   |
| ASUS P8H61-M LX3 PLUS R2.0   | 3        | 0.71%   |
| ASUS M5A78L-M LX3            | 3        | 0.71%   |
| MSI MS-7D20                  | 2        | 0.47%   |
| MSI MS-7C91                  | 2        | 0.47%   |
| MSI MS-7C52                  | 2        | 0.47%   |
| MSI MS-7597                  | 2        | 0.47%   |
| MSI MS-7592                  | 2        | 0.47%   |
| Intel H55                    | 2        | 0.47%   |
| HP Z4 G4 Workstation         | 2        | 0.47%   |
| HP ProLiant MicroServer Gen8 | 2        | 0.47%   |
| Gigabyte Z68P-DS3            | 2        | 0.47%   |
| Gigabyte H77M-D3H            | 2        | 0.47%   |
| Gigabyte H61M-S2PV           | 2        | 0.47%   |
| Gigabyte GA-MA785GMT-UD2H    | 2        | 0.47%   |
| Gigabyte G41M-Combo          | 2        | 0.47%   |
| Gigabyte B450M H             | 2        | 0.47%   |
| Gigabyte B450M DS3H          | 2        | 0.47%   |
| Gigabyte B450 AORUS ELITE    | 2        | 0.47%   |
| Foxconn G31MV/G31MV-K FAB    | 2        | 0.47%   |
| Dell Vostro 3670             | 2        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 29       | 6.84%   |
| ASUS TUF           | 13       | 3.07%   |
| Gigabyte B450M     | 11       | 2.59%   |
| ASUS ROG           | 10       | 2.36%   |
| Unknown            | 10       | 2.36%   |
| ASUS All           | 9        | 2.12%   |
| ASUS P8H61-M       | 6        | 1.42%   |
| MSI MS-7C02        | 5        | 1.18%   |
| Gigabyte G31M-ES2L | 5        | 1.18%   |
| Gigabyte A320M-S2H | 5        | 1.18%   |
| ASUS M5A97         | 5        | 1.18%   |
| ASUS M5A78L-M      | 5        | 1.18%   |
| MSI MS-7A34        | 4        | 0.94%   |
| MSI MS-7817        | 4        | 0.94%   |
| MSI MS-7693        | 4        | 0.94%   |
| Lenovo ThinkCentre | 4        | 0.94%   |
| Gigabyte G41M-ES2L | 4        | 0.94%   |
| Pegatron IPXSB-H61 | 3        | 0.71%   |
| MSI MS-7C09        | 3        | 0.71%   |
| MSI MS-7B86        | 3        | 0.71%   |
| MSI MS-7A38        | 3        | 0.71%   |
| MSI MS-7996        | 3        | 0.71%   |
| MSI MS-7360        | 3        | 0.71%   |
| Lenovo IdeaCentre  | 3        | 0.71%   |
| HP Compaq          | 3        | 0.71%   |
| Gigabyte M61SME-S2 | 3        | 0.71%   |
| Dell Vostro        | 3        | 0.71%   |
| Dell OptiPlex      | 3        | 0.71%   |
| Casper NIRVANA     | 3        | 0.71%   |
| ASUS P5Q           | 3        | 0.71%   |
| ASUS P5KPL-AM      | 3        | 0.71%   |
| MSI MS-7D20        | 2        | 0.47%   |
| MSI MS-7C91        | 2        | 0.47%   |
| MSI MS-7C52        | 2        | 0.47%   |
| MSI MS-7597        | 2        | 0.47%   |
| MSI MS-7592        | 2        | 0.47%   |
| Intel H55          | 2        | 0.47%   |
| HP Z4              | 2        | 0.47%   |
| HP ProLiant        | 2        | 0.47%   |
| HP EliteDesk       | 2        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 51       | 12.03%  |
| 2012    | 37       | 8.73%   |
| 2020    | 35       | 8.25%   |
| 2017    | 35       | 8.25%   |
| 2013    | 32       | 7.55%   |
| 2010    | 32       | 7.55%   |
| 2019    | 31       | 7.31%   |
| 2011    | 29       | 6.84%   |
| 2008    | 24       | 5.66%   |
| 2009    | 20       | 4.72%   |
| 2014    | 17       | 4.01%   |
| 2007    | 17       | 4.01%   |
| 2021    | 15       | 3.54%   |
| 2015    | 15       | 3.54%   |
| 2016    | 14       | 3.3%    |
| 2022    | 8        | 1.89%   |
| 2006    | 6        | 1.42%   |
| 2023    | 2        | 0.47%   |
| 2005    | 1        | 0.24%   |
| 2004    | 1        | 0.24%   |
| 2003    | 1        | 0.24%   |
| Unknown | 1        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 424      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 419      | 98.13%  |
| Enabled  | 8        | 1.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 424      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 113      | 26.04%  |
| 8.01-16.0       | 96       | 22.12%  |
| 3.01-4.0        | 64       | 14.75%  |
| 4.01-8.0        | 58       | 13.36%  |
| 32.01-64.0      | 41       | 9.45%   |
| 1.01-2.0        | 29       | 6.68%   |
| 64.01-256.0     | 12       | 2.76%   |
| 24.01-32.0      | 10       | 2.3%    |
| 2.01-3.0        | 8        | 1.84%   |
| 0.51-1.0        | 2        | 0.46%   |
| More than 256.0 | 1        | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 177      | 37.34%  |
| 2.01-3.0   | 115      | 24.26%  |
| 3.01-4.0   | 69       | 14.56%  |
| 4.01-8.0   | 59       | 12.45%  |
| 0.51-1.0   | 26       | 5.49%   |
| 8.01-16.0  | 19       | 4.01%   |
| 0.01-0.5   | 5        | 1.05%   |
| 24.01-32.0 | 2        | 0.42%   |
| 16.01-24.0 | 2        | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 184      | 41.63%  |
| 2      | 134      | 30.32%  |
| 3      | 73       | 16.52%  |
| 4      | 29       | 6.56%   |
| 5      | 12       | 2.71%   |
| 7      | 6        | 1.36%   |
| 6      | 2        | 0.45%   |
| 0      | 2        | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 292      | 67.75%  |
| Yes       | 139      | 32.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 420      | 99.06%  |
| No        | 4        | 0.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 265      | 61.63%  |
| Yes       | 165      | 38.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 309      | 72.03%  |
| Yes       | 120      | 27.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Turkey  | 424      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Istanbul            | 158      | 36.16%  |
| Ankara              | 58       | 13.27%  |
| Izmir               | 37       | 8.47%   |
| Bursa               | 25       | 5.72%   |
| Antalya             | 15       | 3.43%   |
| Konya               | 11       | 2.52%   |
| Kayseri             | 8        | 1.83%   |
| Aydin               | 8        | 1.83%   |
| Adana               | 7        | 1.6%    |
| İzmit              | 6        | 1.37%   |
| Samsun              | 5        | 1.14%   |
| Kosekoy             | 5        | 1.14%   |
| Kırklareli         | 5        | 1.14%   |
| Balıkesir          | 5        | 1.14%   |
| Zonguldak           | 3        | 0.69%   |
| Trabzon             | 3        | 0.69%   |
| Mersin              | 3        | 0.69%   |
| Magnesia ad Sipylum | 3        | 0.69%   |
| Eskişehir          | 3        | 0.69%   |
| Denizli             | 3        | 0.69%   |
| Ulus                | 2        | 0.46%   |
| Tekirdağ           | 2        | 0.46%   |
| Ordu                | 2        | 0.46%   |
| OEdemis             | 2        | 0.46%   |
| Mugla               | 2        | 0.46%   |
| Malatya             | 2        | 0.46%   |
| Erzurum             | 2        | 0.46%   |
| Cankaya             | 2        | 0.46%   |
| Antakya             | 2        | 0.46%   |
| Alanya              | 2        | 0.46%   |
| Adapazarı          | 2        | 0.46%   |
| Yozgat              | 1        | 0.23%   |
| Yenimahalle         | 1        | 0.23%   |
| Yaman               | 1        | 0.23%   |
| Yalova              | 1        | 0.23%   |
| Van                 | 1        | 0.23%   |
| Uşak               | 1        | 0.23%   |
| Tokat Province      | 1        | 0.23%   |
| Skutari             | 1        | 0.23%   |
| Sirnak              | 1        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 155      | 208    | 20.29%  |
| WDC                         | 139      | 215    | 18.19%  |
| Samsung Electronics         | 120      | 195    | 15.71%  |
| SanDisk                     | 69       | 93     | 9.03%   |
| Toshiba                     | 45       | 49     | 5.89%   |
| Kingston                    | 44       | 52     | 5.76%   |
| China                       | 17       | 18     | 2.23%   |
| A-DATA Technology           | 17       | 19     | 2.23%   |
| Crucial                     | 15       | 18     | 1.96%   |
| Hitachi                     | 14       | 16     | 1.83%   |
| Corsair                     | 11       | 18     | 1.44%   |
| KIOXIA                      | 7        | 9      | 0.92%   |
| JAMESDONKEY                 | 7        | 7      | 0.92%   |
| HGST                        | 7        | 8      | 0.92%   |
| KIOXIA-EXCERIA              | 6        | 7      | 0.79%   |
| OCZ                         | 5        | 7      | 0.65%   |
| Intel                       | 5        | 7      | 0.65%   |
| Realtek Semiconductor       | 4        | 5      | 0.52%   |
| Phison Electronics          | 4        | 4      | 0.52%   |
| Phison                      | 4        | 4      | 0.52%   |
| Maxtor                      | 4        | 4      | 0.52%   |
| Kingston Technology Company | 4        | 5      | 0.52%   |
| XPG                         | 3        | 5      | 0.39%   |
| Team                        | 3        | 3      | 0.39%   |
| Netac                       | 3        | 3      | 0.39%   |
| Lexar                       | 3        | 3      | 0.39%   |
| HS-SSD-C100                 | 3        | 3      | 0.39%   |
| Hewlett-Packard             | 3        | 3      | 0.39%   |
| ADATA Technology            | 3        | 3      | 0.39%   |
| Transcend                   | 2        | 2      | 0.26%   |
| Silicon Motion              | 2        | 2      | 0.26%   |
| KingSpec                    | 2        | 2      | 0.26%   |
| JD                          | 2        | 3      | 0.26%   |
| Gigabyte Technology         | 2        | 2      | 0.26%   |
| Apple                       | 2        | 2      | 0.26%   |
| Unknown                     | 1        | 2      | 0.13%   |
| SSSTC                       | 1        | 1      | 0.13%   |
| SSD-S400                    | 1        | 1      | 0.13%   |
| SPCC                        | 1        | 1      | 0.13%   |
| SK hynix                    | 1        | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 15       | 1.74%   |
| Seagate ST1000DM010-2EP102 1TB                      | 15       | 1.74%   |
| SanDisk SSD PLUS 240GB                              | 14       | 1.63%   |
| Seagate ST1000DM003-1ER162 1TB                      | 10       | 1.16%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 9        | 1.05%   |
| Seagate ST3500418AS 500GB                           | 9        | 1.05%   |
| Samsung SSD 860 EVO 250GB                           | 9        | 1.05%   |
| Samsung HD502HJ 500GB                               | 9        | 1.05%   |
| Samsung HD322HJ 320GB                               | 8        | 0.93%   |
| Kingston SV300S37A120G 120GB SSD                    | 8        | 0.93%   |
| A-DATA SU650 120GB SSD                              | 8        | 0.93%   |
| Toshiba DT01ACA100 1TB                              | 7        | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB                      | 7        | 0.81%   |
| Seagate ST1000DM003-1CH162 1TB                      | 7        | 0.81%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 6        | 0.7%    |
| Samsung SSD 850 EVO 250GB                           | 6        | 0.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 6        | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB                            | 5        | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5        | 0.58%   |
| Seagate Expansion 1TB                               | 5        | 0.58%   |
| SanDisk SSD PLUS 480GB                              | 5        | 0.58%   |
| Samsung SSD 870 EVO 500GB                           | 5        | 0.58%   |
| Samsung NVMe SSD Drive 500GB                        | 5        | 0.58%   |
| China SATA SSD 120GB                                | 5        | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4        | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 4        | 0.46%   |
| WDC WD6402AAEX-00Y9A0 640GB                         | 4        | 0.46%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 4        | 0.46%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.46%   |
| Seagate ST3250410AS 250GB                           | 4        | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB                      | 4        | 0.46%   |
| Seagate ST1000DM003-1SB102 1TB                      | 4        | 0.46%   |
| Seagate Expansion Desk 8TB                          | 4        | 0.46%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 4        | 0.46%   |
| SanDisk Ultra II 240GB SSD                          | 4        | 0.46%   |
| SanDisk Ultra 3D NVMe 500GB                         | 4        | 0.46%   |
| SanDisk SDSSDP128G 128GB                            | 4        | 0.46%   |
| SanDisk SDSSDA240G 240GB                            | 4        | 0.46%   |
| Samsung SSD 840 EVO 250GB                           | 4        | 0.46%   |
| Samsung SP0812C 80GB                                | 4        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives  | Percent |
|---------------------|----------|---------|---------|
| Seagate             | 154      | 207     | 38.6%   |
| WDC                 | 125      | 192     | 31.33%  |
| Samsung Electronics | 53       | 75      | 13.28%  |
| Toshiba             | 35       | 37      | 8.77%   |
| Hitachi             | 14       | 16      | 3.51%   |
| HGST                | 7        | 8       | 1.75%   |
| Maxtor              | 4        | 4       | 1%      |
| Intenso             | 1        | 1       | 0.25%   |
| Initio              | 1        | Unknown | 0.25%   |
| Fujitsu             | 1        | 1       | 0.25%   |
| ExcelStor           | 1        | 1       | 0.25%   |
| ASMT                | 1        | 1       | 0.25%   |
| Apple               | 1        | 1       | 0.25%   |
| 128MB               | 1        | 1       | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 55       | 72     | 20.45%  |
| Samsung Electronics | 48       | 72     | 17.84%  |
| Kingston            | 41       | 49     | 15.24%  |
| WDC                 | 17       | 21     | 6.32%   |
| China               | 17       | 18     | 6.32%   |
| Crucial             | 13       | 15     | 4.83%   |
| A-DATA Technology   | 13       | 14     | 4.83%   |
| Toshiba             | 7        | 8      | 2.6%    |
| Corsair             | 7        | 9      | 2.6%    |
| KIOXIA-EXCERIA      | 6        | 7      | 2.23%   |
| JAMESDONKEY         | 6        | 6      | 2.23%   |
| OCZ                 | 5        | 7      | 1.86%   |
| Team                | 3        | 3      | 1.12%   |
| Netac               | 3        | 3      | 1.12%   |
| Lexar               | 3        | 3      | 1.12%   |
| Hewlett-Packard     | 3        | 3      | 1.12%   |
| Transcend           | 2        | 2      | 0.74%   |
| KingSpec            | 2        | 2      | 0.74%   |
| Intel               | 2        | 2      | 0.74%   |
| Gigabyte Technology | 2        | 2      | 0.74%   |
| SSD-S400            | 1        | 1      | 0.37%   |
| Micron Technology   | 1        | 1      | 0.37%   |
| LITEON              | 1        | 1      | 0.37%   |
| KingDian            | 1        | 1      | 0.37%   |
| JD                  | 1        | 1      | 0.37%   |
| HS-SSD-C100         | 1        | 1      | 0.37%   |
| GOODRAM             | 1        | 1      | 0.37%   |
| Colorful            | 1        | 1      | 0.37%   |
| BR                  | 1        | 1      | 0.37%   |
| Apple               | 1        | 1      | 0.37%   |
| Apacer              | 1        | 1      | 0.37%   |
| AFOX                | 1        | 1      | 0.37%   |
| Acer                | 1        | 1      | 0.37%   |
| 120G                | 1        | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 309      | 545    | 47.47%  |
| SSD     | 231      | 332    | 35.48%  |
| NVMe    | 99       | 143    | 15.21%  |
| Unknown | 12       | 16     | 1.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 392      | 867    | 76.56%  |
| NVMe | 99       | 143    | 19.34%  |
| SAS  | 21       | 26     | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 328      | 551    | 60.63%  |
| 0.51-1.0   | 149      | 230    | 27.54%  |
| 1.01-2.0   | 36       | 52     | 6.65%   |
| 3.01-4.0   | 12       | 20     | 2.22%   |
| 2.01-3.0   | 9        | 13     | 1.66%   |
| 4.01-10.0  | 7        | 11     | 1.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 127      | 27.97%  |
| 251-500        | 93       | 20.48%  |
| 501-1000       | 57       | 12.56%  |
| 1001-2000      | 42       | 9.25%   |
| 1-20           | 37       | 8.15%   |
| 51-100         | 35       | 7.71%   |
| More than 3000 | 24       | 5.29%   |
| 2001-3000      | 18       | 3.96%   |
| 21-50          | 13       | 2.86%   |
| Unknown        | 8        | 1.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 167      | 36.3%   |
| 21-50          | 81       | 17.61%  |
| 51-100         | 55       | 11.96%  |
| 101-250        | 52       | 11.3%   |
| 251-500        | 41       | 8.91%   |
| 501-1000       | 28       | 6.09%   |
| 1001-2000      | 12       | 2.61%   |
| More than 3000 | 9        | 1.96%   |
| Unknown        | 8        | 1.74%   |
| 2001-3000      | 7        | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 6        | 6      | 8.45%   |
| Kingston SV300S37A120G 120GB SSD      | 4        | 5      | 5.63%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 2.82%   |
| Seagate ST3500630AS 500GB             | 2        | 2      | 2.82%   |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 3      | 2.82%   |
| Samsung Electronics HD161HJ 160GB     | 2        | 2      | 2.82%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 1.41%   |
| WDC WD5000AAKX-001CA0 500GB           | 1        | 2      | 1.41%   |
| WDC WD400JB-00ENA0 40GB               | 1        | 1      | 1.41%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 1        | 1      | 1.41%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1        | 1      | 1.41%   |
| WDC WD3200BEVT-60A23T0 320GB          | 1        | 1      | 1.41%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1        | 1      | 1.41%   |
| WDC WD3200AACS-00M6B0 320GB           | 1        | 1      | 1.41%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1        | 1      | 1.41%   |
| WDC WD2500JS-55NCB1 250GB             | 1        | 1      | 1.41%   |
| WDC WD2003FYYS-05T9B0 2TB             | 1        | 1      | 1.41%   |
| WDC WD10EZEX-00MFCA0 1TB              | 1        | 2      | 1.41%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 2      | 1.41%   |
| Toshiba MQ01ABD100 1TB                | 1        | 1      | 1.41%   |
| SSD-S400 SSD 120GB                    | 1        | 1      | 1.41%   |
| Seagate ST500DM009-2F110A 500GB       | 1        | 2      | 1.41%   |
| Seagate ST380215AS 80GB               | 1        | 1      | 1.41%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 1.41%   |
| Seagate ST3500413AS 500GB             | 1        | 1      | 1.41%   |
| Seagate ST3250410AS 250GB             | 1        | 1      | 1.41%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 1.41%   |
| Seagate ST3160812AS 160GB             | 1        | 1      | 1.41%   |
| Seagate ST3160215AS 160GB             | 1        | 1      | 1.41%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1        | 1      | 1.41%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB        | 1        | 1      | 1.41%   |
| Seagate ST1000LM014-SSHD-8GB          | 1        | 1      | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 2      | 1.41%   |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 1      | 1.41%   |
| SanDisk SSD PLUS 240GB                | 1        | 1      | 1.41%   |
| SanDisk SDSSDX240GG25 240GB           | 1        | 1      | 1.41%   |
| SanDisk SDSSDA120G 120GB              | 1        | 1      | 1.41%   |
| SanDisk SD8SBAT128G1122 128GB SSD     | 1        | 1      | 1.41%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 27     | 32.35%  |
| WDC                 | 12       | 16     | 17.65%  |
| Samsung Electronics | 9        | 11     | 13.24%  |
| Kingston            | 6        | 7      | 8.82%   |
| SanDisk             | 4        | 4      | 5.88%   |
| Toshiba             | 3        | 3      | 4.41%   |
| A-DATA Technology   | 3        | 3      | 4.41%   |
| Maxtor              | 2        | 2      | 2.94%   |
| Hitachi             | 2        | 2      | 2.94%   |
| SSD-S400            | 1        | 1      | 1.47%   |
| OCZ                 | 1        | 2      | 1.47%   |
| HGST                | 1        | 1      | 1.47%   |
| Crucial             | 1        | 1      | 1.47%   |
| China               | 1        | 1      | 1.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 27     | 44%     |
| WDC                 | 12       | 16     | 24%     |
| Samsung Electronics | 8        | 10     | 16%     |
| Toshiba             | 3        | 3      | 6%      |
| Maxtor              | 2        | 2      | 4%      |
| Hitachi             | 2        | 2      | 4%      |
| HGST                | 1        | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 43       | 61     | 70.49%  |
| SSD  | 17       | 19     | 27.87%  |
| NVMe | 1        | 1      | 1.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 273      | 609    | 57.11%  |
| Works    | 144      | 345    | 30.13%  |
| Malfunc  | 60       | 81     | 12.55%  |
| Failed   | 1        | 1      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 254      | 44.17%  |
| AMD                              | 151      | 26.26%  |
| Samsung Electronics              | 35       | 6.09%   |
| JMicron Technology               | 18       | 3.13%   |
| SanDisk                          | 16       | 2.78%   |
| Marvell Technology Group         | 15       | 2.61%   |
| ASMedia Technology               | 14       | 2.43%   |
| Phison Electronics               | 13       | 2.26%   |
| Nvidia                           | 13       | 2.26%   |
| KIOXIA                           | 7        | 1.22%   |
| ADATA Technology                 | 7        | 1.22%   |
| Realtek Semiconductor            | 6        | 1.04%   |
| Kingston Technology Company      | 6        | 1.04%   |
| Silicon Motion                   | 5        | 0.87%   |
| Micron/Crucial Technology        | 4        | 0.7%    |
| VIA Technologies                 | 3        | 0.52%   |
| Toshiba America Info Systems     | 2        | 0.35%   |
| LSI Logic / Symbios Logic        | 2        | 0.35%   |
| ULi Electronics                  | 1        | 0.17%   |
| SK hynix                         | 1        | 0.17%   |
| Silicon Integrated Systems [SiS] | 1        | 0.17%   |
| Promise Technology               | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 80       | 10.32%  |
| AMD 400 Series Chipset SATA Controller                                                  | 51       | 6.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 42       | 5.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 28       | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 3.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 26       | 3.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 23       | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 22       | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19       | 2.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18       | 2.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 16       | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 16       | 2.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 2.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 1.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 1.55%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 1.55%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 1.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 1.16%   |
| Nvidia MCP61 SATA Controller                                                            | 9        | 1.16%   |
| AMD FCH SATA Controller D                                                               | 9        | 1.16%   |
| Phison E12 NVMe Controller                                                              | 8        | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 8        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 1.03%   |
| Samsung NVMe SSD Controller 980                                                         | 7        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 0.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 0.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 7        | 0.9%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 7        | 0.9%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7        | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6        | 0.77%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 6        | 0.77%   |
| KIOXIA NVMe SSD                                                                         | 6        | 0.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 0.65%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 313      | 54.34%  |
| IDE  | 144      | 25%     |
| NVMe | 100      | 17.36%  |
| RAID | 17       | 2.95%   |
| SCSI | 2        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 258      | 60.85%  |
| AMD          | 165      | 38.92%  |
| CentaurHauls | 1        | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 2.34%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 1.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 7        | 1.64%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 1.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.41%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 6        | 1.41%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 6        | 1.41%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 1.41%   |
| AMD FX-6300 Six-Core Processor              | 6        | 1.41%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 5        | 1.17%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 5        | 1.17%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 1.17%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 5        | 1.17%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 5        | 1.17%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 0.94%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 4        | 0.94%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 4        | 0.94%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.94%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.94%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.94%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 4        | 0.94%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 4        | 0.94%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 4        | 0.94%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.94%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 4        | 0.94%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 0.94%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 3        | 0.7%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.7%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 0.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.7%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.7%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.7%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 0.7%    |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 3        | 0.7%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3        | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 60       | 14.08%  |
| AMD Ryzen 5             | 53       | 12.44%  |
| Intel Core i7           | 45       | 10.56%  |
| Intel Core i3           | 38       | 8.92%   |
| AMD Ryzen 7             | 26       | 6.1%    |
| Intel Core 2 Quad       | 20       | 4.69%   |
| AMD FX                  | 20       | 4.69%   |
| Intel Xeon              | 17       | 3.99%   |
| Intel Core 2 Duo        | 16       | 3.76%   |
| Other                   | 15       | 3.52%   |
| Intel Pentium           | 14       | 3.29%   |
| Intel Pentium Dual-Core | 10       | 2.35%   |
| AMD Ryzen 3             | 10       | 2.35%   |
| Intel Pentium Dual      | 7        | 1.64%   |
| Intel Celeron           | 7        | 1.64%   |
| AMD Phenom II X4        | 7        | 1.64%   |
| AMD Ryzen 9             | 4        | 0.94%   |
| AMD Athlon II X3        | 4        | 0.94%   |
| AMD Athlon II X2        | 4        | 0.94%   |
| AMD Athlon 64 X2        | 4        | 0.94%   |
| AMD Athlon              | 4        | 0.94%   |
| Intel Pentium 4         | 3        | 0.7%    |
| Intel Core i9           | 3        | 0.7%    |
| Intel Core 2            | 3        | 0.7%    |
| AMD Ryzen 5 PRO         | 3        | 0.7%    |
| AMD Phenom II X6        | 3        | 0.7%    |
| AMD Phenom              | 3        | 0.7%    |
| AMD Athlon II X4        | 3        | 0.7%    |
| AMD A4                  | 3        | 0.7%    |
| AMD A10                 | 3        | 0.7%    |
| AMD Sempron             | 2        | 0.47%   |
| AMD Ryzen Threadripper  | 2        | 0.47%   |
| AMD Athlon X4           | 2        | 0.47%   |
| AMD A8                  | 2        | 0.47%   |
| Intel Pentium D         | 1        | 0.23%   |
| Intel Atom              | 1        | 0.23%   |
| CentaurHauls VIA Eden   | 1        | 0.23%   |
| AMD Phenom II X2        | 1        | 0.23%   |
| AMD Athlon XP           | 1        | 0.23%   |
| AMD A6                  | 1        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 152      | 35.68%  |
| 2      | 114      | 26.76%  |
| 6      | 80       | 18.78%  |
| 8      | 37       | 8.69%   |
| 1      | 16       | 3.76%   |
| 3      | 13       | 3.05%   |
| 12     | 8        | 1.88%   |
| 24     | 2        | 0.47%   |
| 10     | 2        | 0.47%   |
| 64     | 1        | 0.23%   |
| 16     | 1        | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 421      | 99.29%  |
| 2      | 3        | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 232      | 54.72%  |
| 1      | 191      | 45.05%  |
| 8      | 1        | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 414      | 97.18%  |
| Unknown        | 8        | 1.88%   |
| 32-bit         | 4        | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 100      | 22.57%  |
| 0x306c3    | 27       | 6.09%   |
| 0x306a9    | 23       | 5.19%   |
| 0x1067a    | 23       | 5.19%   |
| 0x906e9    | 20       | 4.51%   |
| 0x206a7    | 17       | 3.84%   |
| 0x08701021 | 14       | 3.16%   |
| 0x06000852 | 13       | 2.93%   |
| 0x0800820d | 12       | 2.71%   |
| 0x506e3    | 11       | 2.48%   |
| 0x08001138 | 10       | 2.26%   |
| 0x010000c8 | 10       | 2.26%   |
| 0x6fd      | 9        | 2.03%   |
| 0x10676    | 9        | 2.03%   |
| 0x08101016 | 7        | 1.58%   |
| 0x906ea    | 6        | 1.35%   |
| 0x08108109 | 6        | 1.35%   |
| 0x08001137 | 6        | 1.35%   |
| 0x06001119 | 6        | 1.35%   |
| 0xa0655    | 5        | 1.13%   |
| 0xa0653    | 5        | 1.13%   |
| 0x6fb      | 5        | 1.13%   |
| 0x106a5    | 4        | 0.9%    |
| 0x0a50000d | 4        | 0.9%    |
| 0x0a20120a | 4        | 0.9%    |
| 0x010000dc | 4        | 0.9%    |
| 0x010000db | 4        | 0.9%    |
| 0xa0671    | 3        | 0.68%   |
| 0x906eb    | 3        | 0.68%   |
| 0x6f6      | 3        | 0.68%   |
| 0x206c2    | 3        | 0.68%   |
| 0x20655    | 3        | 0.68%   |
| 0x20652    | 3        | 0.68%   |
| 0x08701013 | 3        | 0.68%   |
| 0x01000083 | 3        | 0.68%   |
| 0x906ed    | 2        | 0.45%   |
| 0x906ec    | 2        | 0.45%   |
| 0x306f2    | 2        | 0.45%   |
| 0x306e4    | 2        | 0.45%   |
| 0x206d7    | 2        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 40       | 9.39%   |
| KabyLake         | 39       | 9.15%   |
| Haswell          | 35       | 8.22%   |
| Zen 2            | 32       | 7.51%   |
| IvyBridge        | 32       | 7.51%   |
| Zen              | 27       | 6.34%   |
| K10              | 27       | 6.34%   |
| SandyBridge      | 26       | 6.1%    |
| Zen+             | 25       | 5.87%   |
| Piledriver       | 24       | 5.63%   |
| Core             | 22       | 5.16%   |
| Zen 3            | 17       | 3.99%   |
| CometLake        | 15       | 3.52%   |
| Skylake          | 14       | 3.29%   |
| Westmere         | 10       | 2.35%   |
| Unknown          | 9        | 2.11%   |
| Nehalem          | 5        | 1.17%   |
| NetBurst         | 4        | 0.94%   |
| K8 Hammer        | 4        | 0.94%   |
| Icelake          | 4        | 0.94%   |
| Bulldozer        | 3        | 0.7%    |
| Alderlake Hybrid | 3        | 0.7%    |
| Steamroller      | 2        | 0.47%   |
| K10 Llano        | 2        | 0.47%   |
| Silvermont       | 1        | 0.23%   |
| K6               | 1        | 0.23%   |
| Goldmont plus    | 1        | 0.23%   |
| Excavator        | 1        | 0.23%   |
| Bonnell          | 1        | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 176      | 38.94%  |
| Nvidia                           | 167      | 36.95%  |
| Intel                            | 104      | 23.01%  |
| VIA Technologies                 | 2        | 0.44%   |
| Matrox Electronics Systems       | 2        | 0.44%   |
| Silicon Integrated Systems [SiS] | 1        | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 26       | 5.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 19       | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 18       | 3.81%   |
| Intel HD Graphics 630                                                       | 11       | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 2.33%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 10       | 2.12%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 10       | 2.12%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 10       | 2.12%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 1.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 1.48%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 1.48%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.48%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 6        | 1.27%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.27%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 1.27%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 6        | 1.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 1.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 1.27%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 5        | 1.06%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.06%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 1.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 1.06%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 5        | 1.06%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 5        | 1.06%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 1.06%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.85%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4        | 0.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 0.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.85%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.64%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 3        | 0.64%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 3        | 0.64%   |
| Nvidia GF108 [GeForce GT 420]                                               | 3        | 0.64%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.64%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 3        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 162      | 37.59%  |
| 1 x Nvidia      | 159      | 36.89%  |
| 1 x Intel       | 80       | 18.56%  |
| 2 x AMD         | 8        | 1.86%   |
| Intel + Nvidia  | 7        | 1.62%   |
| Intel + AMD     | 5        | 1.16%   |
| 1 x VIA         | 2        | 0.46%   |
| 1 x Matrox      | 2        | 0.46%   |
| AMD + Nvidia    | 2        | 0.46%   |
| Other           | 1        | 0.23%   |
| 2 x Nvidia      | 1        | 0.23%   |
| 1 x SiS         | 1        | 0.23%   |
| Intel + 2 x AMD | 1        | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 312      | 72.56%  |
| Proprietary | 100      | 23.26%  |
| Unknown     | 18       | 4.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 162      | 36.4%   |
| 0.51-1.0   | 62       | 13.93%  |
| 3.01-4.0   | 60       | 13.48%  |
| 1.01-2.0   | 59       | 13.26%  |
| 0.01-0.5   | 38       | 8.54%   |
| 7.01-8.0   | 22       | 4.94%   |
| 5.01-6.0   | 20       | 4.49%   |
| 8.01-16.0  | 15       | 3.37%   |
| 2.01-3.0   | 5        | 1.12%   |
| 4.01-5.0   | 1        | 0.22%   |
| 16.01-24.0 | 1        | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 73       | 17.38%  |
| Philips              | 44       | 10.48%  |
| Goldstar             | 43       | 10.24%  |
| Ancor Communications | 28       | 6.67%   |
| Dell                 | 26       | 6.19%   |
| AOC                  | 25       | 5.95%   |
| Acer                 | 24       | 5.71%   |
| Hewlett-Packard      | 17       | 4.05%   |
| ViewSonic            | 14       | 3.33%   |
| BenQ                 | 11       | 2.62%   |
| ASUSTek Computer     | 11       | 2.62%   |
| Lenovo               | 7        | 1.67%   |
| SAC                  | 5        | 1.19%   |
| MSI                  | 5        | 1.19%   |
| LG Electronics       | 5        | 1.19%   |
| HKC                  | 5        | 1.19%   |
| AGO                  | 5        | 1.19%   |
| Unknown              | 4        | 0.95%   |
| Sony                 | 4        | 0.95%   |
| SANYO                | 4        | 0.95%   |
| Plain Tree Systems   | 4        | 0.95%   |
| KTC                  | 4        | 0.95%   |
| Unknown              | 4        | 0.95%   |
| VIE                  | 3        | 0.71%   |
| Vestel Elektronik    | 3        | 0.71%   |
| Mi                   | 3        | 0.71%   |
| Apple                | 3        | 0.71%   |
| Sharp                | 2        | 0.48%   |
| RTK                  | 2        | 0.48%   |
| Microstep            | 2        | 0.48%   |
| LYC                  | 2        | 0.48%   |
| HPN                  | 2        | 0.48%   |
| Cbox                 | 2        | 0.48%   |
| CASIO                | 2        | 0.48%   |
| ___                  | 1        | 0.24%   |
| Sun                  | 1        | 0.24%   |
| NXP                  | 1        | 0.24%   |
| NCS                  | 1        | 0.24%   |
| MNR                  | 1        | 0.24%   |
| Lite-On              | 1        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 7        | 1.59%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 4        | 0.91%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 4        | 0.91%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                       | 4        | 0.91%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 4        | 0.91%   |
| Unknown                                                                | 4        | 0.91%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.68%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 3        | 0.68%   |
| Plain Tree Systems Monitor PTS06A5 1280x1024 337x270mm 17.0-inch       | 3        | 0.68%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 3        | 0.68%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 3        | 0.68%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 3        | 0.68%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                   | 3        | 0.68%   |
| Ancor Communications VX229 ACI22E5 1920x1080 476x268mm 21.5-inch       | 3        | 0.68%   |
| Ancor Communications VK228 ACI22D1 1920x1080 480x270mm 21.7-inch       | 3        | 0.68%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                  | 3        | 0.68%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                       | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch    | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 2        | 0.46%   |
| Samsung Electronics C27JG5x SAM0FDB 2560x1440 597x336mm 27.0-inch      | 2        | 0.46%   |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                     | 2        | 0.46%   |
| LYC GPR27C1MS144 LYC0001 1920x1080 597x336mm 27.0-inch                 | 2        | 0.46%   |
| KTC 55'TV KTC5500 1920x1080 1209x680mm 54.6-inch                       | 2        | 0.46%   |
| HKC LCD Monitor HKC1850 1360x768 304x228mm 15.0-inch                   | 2        | 0.46%   |
| Hewlett-Packard 2311gt HWP2981 1920x1080 510x287mm 23.0-inch           | 2        | 0.46%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                   | 2        | 0.46%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 2        | 0.46%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.46%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 2        | 0.46%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                     | 2        | 0.46%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 2        | 0.46%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                      | 2        | 0.46%   |
| Cbox HD240M HAN2400 1920x1080 531x299mm 24.0-inch                      | 2        | 0.46%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 2        | 0.46%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch           | 2        | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 210      | 51.09%  |
| 1280x1024 (SXGA)   | 27       | 6.57%   |
| 2560x1440 (QHD)    | 25       | 6.08%   |
| 3840x2160 (4K)     | 24       | 5.84%   |
| 1366x768 (WXGA)    | 23       | 5.6%    |
| 1440x900 (WXGA+)   | 18       | 4.38%   |
| 1680x1050 (WSXGA+) | 15       | 3.65%   |
| Unknown            | 14       | 3.41%   |
| 1600x900 (HD+)     | 12       | 2.92%   |
| 1360x768           | 8        | 1.95%   |
| 2560x1080          | 7        | 1.7%    |
| 3440x1440          | 6        | 1.46%   |
| 3840x1080          | 4        | 0.97%   |
| 2560x1600          | 3        | 0.73%   |
| 4480x1440          | 2        | 0.49%   |
| 1024x768 (XGA)     | 2        | 0.49%   |
| 7920x1440          | 1        | 0.24%   |
| 6000x1440          | 1        | 0.24%   |
| 5760x2160          | 1        | 0.24%   |
| 3840x1200          | 1        | 0.24%   |
| 3750x1280          | 1        | 0.24%   |
| 3360x1050          | 1        | 0.24%   |
| 2390x768           | 1        | 0.24%   |
| 1920x540           | 1        | 0.24%   |
| 1920x1200 (WUXGA)  | 1        | 0.24%   |
| 1600x1200          | 1        | 0.24%   |
| 1152x864           | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 67       | 16.14%  |
| 23      | 66       | 15.9%   |
| Unknown | 53       | 12.77%  |
| 27      | 43       | 10.36%  |
| 24      | 32       | 7.71%   |
| 18      | 27       | 6.51%   |
| 19      | 24       | 5.78%   |
| 17      | 17       | 4.1%    |
| 20      | 14       | 3.37%   |
| 34      | 13       | 3.13%   |
| 22      | 8        | 1.93%   |
| 15      | 8        | 1.93%   |
| 31      | 7        | 1.69%   |
| 72      | 5        | 1.2%    |
| 12      | 5        | 1.2%    |
| 84      | 4        | 0.96%   |
| 54      | 3        | 0.72%   |
| 29      | 3        | 0.72%   |
| 26      | 3        | 0.72%   |
| 60      | 2        | 0.48%   |
| 40      | 2        | 0.48%   |
| 65      | 1        | 0.24%   |
| 64      | 1        | 0.24%   |
| 57      | 1        | 0.24%   |
| 55      | 1        | 0.24%   |
| 47      | 1        | 0.24%   |
| 46      | 1        | 0.24%   |
| 43      | 1        | 0.24%   |
| 33      | 1        | 0.24%   |
| 28      | 1        | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 141      | 34.64%  |
| 501-600     | 126      | 30.96%  |
| Unknown     | 53       | 13.02%  |
| 301-350     | 23       | 5.65%   |
| 701-800     | 14       | 3.44%   |
| 601-700     | 14       | 3.44%   |
| 1001-1500   | 11       | 2.7%    |
| 1501-2000   | 9        | 2.21%   |
| 351-400     | 8        | 1.97%   |
| 201-300     | 5        | 1.23%   |
| 801-900     | 2        | 0.49%   |
| 901-1000    | 1        | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 255      | 64.72%  |
| Unknown | 47       | 11.93%  |
| 16/10   | 37       | 9.39%   |
| 5/4     | 20       | 5.08%   |
| 4/3     | 15       | 3.81%   |
| 21/9    | 13       | 3.3%    |
| 3/2     | 7        | 1.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 152      | 37.07%  |
| 151-200        | 56       | 13.66%  |
| Unknown        | 53       | 12.93%  |
| 301-350        | 43       | 10.49%  |
| 141-150        | 36       | 8.78%   |
| 351-500        | 25       | 6.1%    |
| More than 1000 | 18       | 4.39%   |
| 251-300        | 9        | 2.2%    |
| 101-110        | 6        | 1.46%   |
| 71-80          | 5        | 1.22%   |
| 501-1000       | 5        | 1.22%   |
| 111-120        | 2        | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 229      | 56.54%  |
| 101-120 | 93       | 22.96%  |
| Unknown | 53       | 13.09%  |
| 1-50    | 16       | 3.95%   |
| 161-240 | 7        | 1.73%   |
| 121-160 | 7        | 1.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 360      | 83.14%  |
| 2     | 49       | 11.32%  |
| 0     | 21       | 4.85%   |
| 3     | 3        | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 292      | 50.34%  |
| Intel                                  | 102      | 17.59%  |
| Qualcomm Atheros                       | 44       | 7.59%   |
| Ralink Technology                      | 34       | 5.86%   |
| ASUSTek Computer                       | 15       | 2.59%   |
| Qualcomm Atheros Communications        | 13       | 2.24%   |
| TP-Link                                | 12       | 2.07%   |
| Nvidia                                 | 11       | 1.9%    |
| Broadcom                               | 11       | 1.9%    |
| Ralink                                 | 5        | 0.86%   |
| Samsung Electronics                    | 4        | 0.69%   |
| ZyXEL Communications                   | 3        | 0.52%   |
| Xiaomi                                 | 3        | 0.52%   |
| Huawei Technologies                    | 3        | 0.52%   |
| Tenda                                  | 2        | 0.34%   |
| OPPO Electronics                       | 2        | 0.34%   |
| Marvell Technology Group               | 2        | 0.34%   |
| Broadcom Limited                       | 2        | 0.34%   |
| Aquantia                               | 2        | 0.34%   |
| Apple                                  | 2        | 0.34%   |
| Wilocity                               | 1        | 0.17%   |
| VIA Technologies                       | 1        | 0.17%   |
| ULi Electronics                        | 1        | 0.17%   |
| T & A Mobile Phones                    | 1        | 0.17%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.17%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.17%   |
| Sangoma Technologies                   | 1        | 0.17%   |
| MediaTek                               | 1        | 0.17%   |
| JMicron Technology                     | 1        | 0.17%   |
| ICS Advent                             | 1        | 0.17%   |
| HTC (High Tech Computer)               | 1        | 0.17%   |
| Edimax Technology                      | 1        | 0.17%   |
| BroadLogic                             | 1        | 0.17%   |
| ASIX Electronics                       | 1        | 0.17%   |
| AirTies Wireless Networks              | 1        | 0.17%   |
| Accton Technology                      | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 238      | 37.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 24       | 3.76%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 17       | 2.66%   |
| Intel Ethernet Connection (2) I219-V                                                 | 17       | 2.66%   |
| Ralink MT7601U Wireless Adapter                                                      | 16       | 2.51%   |
| Intel Wi-Fi 6 AX200                                                                  | 13       | 2.04%   |
| Intel I211 Gigabit Network Connection                                                | 13       | 2.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 12       | 1.88%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 9        | 1.41%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                      | 9        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                              | 8        | 1.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                             | 7        | 1.1%    |
| Nvidia MCP61 Ethernet                                                                | 7        | 1.1%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6        | 0.94%   |
| Intel Ethernet Connection I217-V                                                     | 6        | 0.94%   |
| Intel Ethernet Connection I217-LM                                                    | 6        | 0.94%   |
| Intel Ethernet Connection (14) I219-V                                                | 5        | 0.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 4        | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 4        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 4        | 0.63%   |
| Realtek 802.11ac NIC                                                                 | 4        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 4        | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 4        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 4        | 0.63%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                         | 3        | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 0.47%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 3        | 0.47%   |
| Ralink RT5370 Wireless Adapter                                                       | 3        | 0.47%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 3        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                            | 3        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                            | 3        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                            | 3        | 0.47%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 0.47%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                           | 3        | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                                 | 3        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                                | 3        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                                                | 3        | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 3        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 39       | 22.03%  |
| Ralink Technology               | 34       | 19.21%  |
| Intel                           | 34       | 19.21%  |
| ASUSTek Computer                | 15       | 8.47%   |
| Qualcomm Atheros Communications | 13       | 7.34%   |
| TP-Link                         | 12       | 6.78%   |
| Qualcomm Atheros                | 11       | 6.21%   |
| Broadcom                        | 6        | 3.39%   |
| Ralink                          | 5        | 2.82%   |
| ZyXEL Communications            | 3        | 1.69%   |
| Wilocity                        | 1        | 0.56%   |
| MediaTek                        | 1        | 0.56%   |
| Edimax Technology               | 1        | 0.56%   |
| AirTies Wireless Networks       | 1        | 0.56%   |
| Accton Technology               | 1        | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                      | 16       | 8.99%   |
| Intel Wi-Fi 6 AX200                                                                  | 13       | 7.3%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 12       | 6.74%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 9        | 5.06%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                      | 9        | 5.06%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6        | 3.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 4        | 2.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 4        | 2.25%   |
| Realtek 802.11ac NIC                                                                 | 4        | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4        | 2.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 4        | 2.25%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                         | 3        | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 1.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 1.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 3        | 1.69%   |
| Ralink RT5370 Wireless Adapter                                                       | 3        | 1.69%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 3        | 1.69%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 3        | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 1.12%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 2        | 1.12%   |
| TP-Link 802.11n NIC                                                                  | 2        | 1.12%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 2        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 2        | 1.12%   |
| Realtek RTL8187 Wireless Adapter                                                     | 2        | 1.12%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                | 2        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 1.12%   |
| Intel Wireless-AC 9260                                                               | 2        | 1.12%   |
| Intel Wireless 8260                                                                  | 2        | 1.12%   |
| Intel Wireless 3160                                                                  | 2        | 1.12%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 2        | 1.12%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                                   | 2        | 1.12%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                                  | 2        | 1.12%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                            | 2        | 1.12%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                   | 1        | 0.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.56%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 1        | 0.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 285      | 63.62%  |
| Intel                                  | 83       | 18.53%  |
| Qualcomm Atheros                       | 34       | 7.59%   |
| Nvidia                                 | 11       | 2.46%   |
| Broadcom                               | 6        | 1.34%   |
| Xiaomi                                 | 3        | 0.67%   |
| Huawei Technologies                    | 3        | 0.67%   |
| Tenda                                  | 2        | 0.45%   |
| Samsung Electronics                    | 2        | 0.45%   |
| OPPO Electronics                       | 2        | 0.45%   |
| Marvell Technology Group               | 2        | 0.45%   |
| Broadcom Limited                       | 2        | 0.45%   |
| Aquantia                               | 2        | 0.45%   |
| Apple                                  | 2        | 0.45%   |
| VIA Technologies                       | 1        | 0.22%   |
| ULi Electronics                        | 1        | 0.22%   |
| T & A Mobile Phones                    | 1        | 0.22%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.22%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.22%   |
| JMicron Technology                     | 1        | 0.22%   |
| ICS Advent                             | 1        | 0.22%   |
| HTC (High Tech Computer)               | 1        | 0.22%   |
| ASIX Electronics                       | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 238      | 52.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24       | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17       | 3.73%   |
| Intel Ethernet Connection (2) I219-V                              | 17       | 3.73%   |
| Intel I211 Gigabit Network Connection                             | 13       | 2.85%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 1.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7        | 1.54%   |
| Nvidia MCP61 Ethernet                                             | 7        | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 6        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.32%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.66%   |
| Huawei WLZ-AN00                                                   | 3        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.44%   |
| Tenda U12                                                         | 2        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 0.44%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 2        | 0.44%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.44%   |
| Intel Ethernet Controller X550                                    | 2        | 0.44%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.44%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.44%   |
| Apple iPad 4/Mini1                                                | 2        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 420      | 71.31%  |
| WiFi     | 165      | 28.01%  |
| Modem    | 2        | 0.34%   |
| Unknown  | 2        | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 322      | 74.71%  |
| WiFi     | 109      | 25.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 339      | 79.58%  |
| 2     | 75       | 17.61%  |
| 3     | 10       | 2.35%   |
| 5     | 1        | 0.23%   |
| 0     | 1        | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 417      | 98.35%  |
| Yes  | 7        | 1.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 53       | 42.4%   |
| Intel                           | 31       | 24.8%   |
| ASUSTek Computer                | 12       | 9.6%    |
| Realtek Semiconductor           | 9        | 7.2%    |
| TP-Link                         | 6        | 4.8%    |
| Qualcomm Atheros Communications | 6        | 4.8%    |
| Broadcom                        | 2        | 1.6%    |
| Apple                           | 2        | 1.6%    |
| MediaTek                        | 1        | 0.8%    |
| Integrated System Solution      | 1        | 0.8%    |
| IMC Networks                    | 1        | 0.8%    |
| HTC (High Tech Computer)        | 1        | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 53       | 42.4%   |
| Intel AX200 Bluetooth                                                | 12       | 9.6%    |
| Intel Bluetooth wireless interface                                   | 7        | 5.6%    |
| TP-Link UB500 Adapter                                                | 6        | 4.8%    |
| Realtek Bluetooth Radio                                              | 6        | 4.8%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 4        | 3.2%    |
| Intel AX201 Bluetooth                                                | 4        | 3.2%    |
| ASUS Bluetooth Adapter                                               | 4        | 3.2%    |
| Realtek RTL8821A Bluetooth                                           | 2        | 1.6%    |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.6%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 2        | 1.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 1.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 1.6%    |
| ASUS Qualcomm Bluetooth 4.1                                          | 2        | 1.6%    |
| ASUS Bluetooth Radio                                                 | 2        | 1.6%    |
| ASUS BCM20702A0                                                      | 2        | 1.6%    |
| Apple Bluetooth USB Host Controller                                  | 2        | 1.6%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 1        | 0.8%    |
| MediaTek Wireless_Device                                             | 1        | 0.8%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.8%    |
| IMC Networks Bluetooth                                               | 1        | 0.8%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 0.8%    |
| Broadcom BCM2035B3 Bluetooth Adapter                                 | 1        | 0.8%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                | 1        | 0.8%    |
| ASUS Bluetooth Device                                                | 1        | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 248      | 34.83%  |
| AMD                                             | 228      | 32.02%  |
| Nvidia                                          | 153      | 21.49%  |
| C-Media Electronics                             | 18       | 2.53%   |
| Creative Labs                                   | 6        | 0.84%   |
| JMTek                                           | 5        | 0.7%    |
| Generalplus Technology                          | 5        | 0.7%    |
| Barco Display Systems                           | 5        | 0.7%    |
| VIA Technologies                                | 4        | 0.56%   |
| Tenx Technology                                 | 4        | 0.56%   |
| Logitech                                        | 3        | 0.42%   |
| Yamaha                                          | 2        | 0.28%   |
| Texas Instruments                               | 2        | 0.28%   |
| SteelSeries ApS                                 | 2        | 0.28%   |
| M-Audio                                         | 2        | 0.28%   |
| Kingston Technology                             | 2        | 0.28%   |
| Focusrite-Novation                              | 2        | 0.28%   |
| ASUSTek Computer                                | 2        | 0.28%   |
| ULi Electronics                                 | 1        | 0.14%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.14%   |
| Sony                                            | 1        | 0.14%   |
| Silicon Integrated Systems [SiS]                | 1        | 0.14%   |
| RODE Microphones                                | 1        | 0.14%   |
| Native Instruments                              | 1        | 0.14%   |
| Micro Star International                        | 1        | 0.14%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.14%   |
| GN Netcom                                       | 1        | 0.14%   |
| Global Sun Technology                           | 1        | 0.14%   |
| Evolution Electronics                           | 1        | 0.14%   |
| Earth Computer Technologies                     | 1        | 0.14%   |
| Creative Technology                             | 1        | 0.14%   |
| Corsair                                         | 1        | 0.14%   |
| Bose                                            | 1        | 0.14%   |
| Blue Microphones                                | 1        | 0.14%   |
| Astro Gaming                                    | 1        | 0.14%   |
| Apple                                           | 1        | 0.14%   |
| Alesis                                          | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 45       | 5.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 39       | 4.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 38       | 4.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 37       | 4.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 35       | 4.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 3.26%   |
| Intel 200 Series PCH HD Audio                                              | 27       | 3.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 26       | 3.14%   |
| AMD Family 17h/19h HD Audio Controller                                     | 24       | 2.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 21       | 2.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 20       | 2.42%   |
| Nvidia TU116 High Definition Audio Controller                              | 18       | 2.18%   |
| Nvidia GF108 High Definition Audio Controller                              | 18       | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17       | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 2.06%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 17       | 2.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 1.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13       | 1.57%   |
| AMD FCH Azalia Controller                                                  | 12       | 1.45%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 11       | 1.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 11       | 1.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                              | 9        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                         | 9        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9        | 1.09%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 9        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 0.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 0.97%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7        | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 6        | 0.73%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6        | 0.73%   |
| C-Media Electronics USB Audio Device                                       | 6        | 0.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.6%    |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.6%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 0.6%    |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 49       | 21.3%   |
| Unknown             | 43       | 18.7%   |
| Corsair             | 30       | 13.04%  |
| G.Skill             | 28       | 12.17%  |
| Samsung Electronics | 16       | 6.96%   |
| Crucial             | 15       | 6.52%   |
| A-DATA Technology   | 10       | 4.35%   |
| Micron Technology   | 9        | 3.91%   |
| SK hynix            | 5        | 2.17%   |
| Team                | 4        | 1.74%   |
| Goldkey             | 4        | 1.74%   |
| Unknown             | 4        | 1.74%   |
| Neo Forza           | 2        | 0.87%   |
| Nanya Technology    | 2        | 0.87%   |
| Unknown (ABCD)      | 1        | 0.43%   |
| Unknown (07FB)      | 1        | 0.43%   |
| Kllisre             | 1        | 0.43%   |
| Hikvision           | 1        | 0.43%   |
| Golden Empire       | 1        | 0.43%   |
| Gold Key            | 1        | 0.43%   |
| Avant               | 1        | 0.43%   |
| ASint Technology    | 1        | 0.43%   |
| Apacer              | 1        | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s   | 6        | 2.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 5        | 1.96%   |
| G.Skill RAM F4-3000C16-8GVRB 8GB DIMM DDR4 3200MT/s    | 5        | 1.96%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 4        | 1.57%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 4        | 1.57%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 4        | 1.57%   |
| Unknown                                                | 4        | 1.57%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 3        | 1.18%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 3        | 1.18%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 3        | 1.18%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1867MT/s      | 3        | 1.18%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s   | 3        | 1.18%   |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s   | 3        | 1.18%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s           | 3        | 1.18%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 2        | 0.78%   |
| Unknown RAM Module 2GB DIMM                            | 2        | 0.78%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 2        | 0.78%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 2        | 0.78%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s     | 2        | 0.78%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s     | 2        | 0.78%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 2        | 0.78%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s   | 2        | 0.78%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 2        | 0.78%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s    | 2        | 0.78%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 2        | 0.78%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 2        | 0.78%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 0.78%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s  | 2        | 0.78%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 0.78%   |
| Kingston RAM 9905403-400.A00LF 4GB DIMM 1600MT/s       | 2        | 0.78%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 2        | 0.78%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s  | 2        | 0.78%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s       | 2        | 0.78%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8192MB DIMM                         | 1        | 0.39%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 1        | 0.39%   |
| Unknown RAM Module 512MB DIMM 50410MT/s                | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s             | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 105      | 51.98%  |
| DDR3    | 51       | 25.25%  |
| Unknown | 25       | 12.38%  |
| SDRAM   | 9        | 4.46%   |
| DDR2    | 8        | 3.96%   |
| LPDDR4  | 2        | 0.99%   |
| DDR5    | 2        | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 188      | 94.47%  |
| SODIMM | 11       | 5.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 93       | 41.52%  |
| 4096  | 42       | 18.75%  |
| 16384 | 37       | 16.52%  |
| 2048  | 30       | 13.39%  |
| 32768 | 10       | 4.46%   |
| 1024  | 9        | 4.02%   |
| 512   | 2        | 0.89%   |
| 65536 | 1        | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 34       | 14.91%  |
| 1600    | 31       | 13.6%   |
| 2400    | 20       | 8.77%   |
| 3600    | 18       | 7.89%   |
| 1333    | 18       | 7.89%   |
| 800     | 11       | 4.82%   |
| 3000    | 9        | 3.95%   |
| 2667    | 9        | 3.95%   |
| 2133    | 9        | 3.95%   |
| Unknown | 9        | 3.95%   |
| 667     | 8        | 3.51%   |
| 1867    | 7        | 3.07%   |
| 2800    | 6        | 2.63%   |
| 3400    | 5        | 2.19%   |
| 400     | 4        | 1.75%   |
| 3866    | 3        | 1.32%   |
| 3733    | 3        | 1.32%   |
| 1066    | 3        | 1.32%   |
| 3466    | 2        | 0.88%   |
| 1866    | 2        | 0.88%   |
| 50410   | 1        | 0.44%   |
| 6000    | 1        | 0.44%   |
| 5808    | 1        | 0.44%   |
| 4133    | 1        | 0.44%   |
| 3800    | 1        | 0.44%   |
| 3266    | 1        | 0.44%   |
| 3151    | 1        | 0.44%   |
| 3100    | 1        | 0.44%   |
| 2933    | 1        | 0.44%   |
| 2733    | 1        | 0.44%   |
| 2666    | 1        | 0.44%   |
| 2048    | 1        | 0.44%   |
| 1639    | 1        | 0.44%   |
| 1400    | 1        | 0.44%   |
| 1334    | 1        | 0.44%   |
| 1067    | 1        | 0.44%   |
| 333     | 1        | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 31.82%  |
| Canon               | 7        | 31.82%  |
| Zebra               | 3        | 13.64%  |
| Seiko Epson         | 3        | 13.64%  |
| Samsung Electronics | 1        | 4.55%   |
| Brother Industries  | 1        | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Zebra TLP2844                    | 2        | 8.7%    |
| HP LaserJet P2055 series         | 2        | 8.7%    |
| Canon E410 series                | 2        | 8.7%    |
| Zebra Zebra GC420d Label Printer | 1        | 4.35%   |
| Seiko Epson L405 Series          | 1        | 4.35%   |
| Seiko Epson L3110 Series         | 1        | 4.35%   |
| Seiko Epson L210 Series          | 1        | 4.35%   |
| Samsung M2020 Series             | 1        | 4.35%   |
| HP LaserJet M101-M106            | 1        | 4.35%   |
| HP LaserJet 1020                 | 1        | 4.35%   |
| HP LaserJet 1010                 | 1        | 4.35%   |
| HP DeskJet F2100 Printer series  | 1        | 4.35%   |
| HP DeskJet 3830 series           | 1        | 4.35%   |
| HP DeskJet 2130 series           | 1        | 4.35%   |
| Canon PIXMA MG3000 series        | 1        | 4.35%   |
| Canon LBP6000                    | 1        | 4.35%   |
| Canon G3020 series               | 1        | 4.35%   |
| Canon G3010 series               | 1        | 4.35%   |
| Canon E460 series                | 1        | 4.35%   |
| Brother DCP-1510                 | 1        | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 1        | 50%     |
| Canon          | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1        | 50%     |
| Canon CanoScan LiDE 210            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 14       | 25%     |
| Z-Star Microelectronics  | 6        | 10.71%  |
| Samsung Electronics      | 5        | 8.93%   |
| Alcor Micro              | 4        | 7.14%   |
| Microdia                 | 3        | 5.36%   |
| Jieli Technology         | 3        | 5.36%   |
| Arkmicro Technologies    | 3        | 5.36%   |
| Novatek Microelectronics | 2        | 3.57%   |
| Microsoft                | 2        | 3.57%   |
| Apple                    | 2        | 3.57%   |
| Sonix Technology         | 1        | 1.79%   |
| Realtek Semiconductor    | 1        | 1.79%   |
| Novatel Wireless         | 1        | 1.79%   |
| MacroSilicon             | 1        | 1.79%   |
| Google                   | 1        | 1.79%   |
| Genesys Logic            | 1        | 1.79%   |
| Generalplus Technology   | 1        | 1.79%   |
| GEMBIRD                  | 1        | 1.79%   |
| eMPIA Technology         | 1        | 1.79%   |
| Creative Technology      | 1        | 1.79%   |
| Chicony Electronics      | 1        | 1.79%   |
| Allwinner Technology     | 1        | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)     | 5        | 8.93%   |
| Alcor Micro USB 2.0 PC Camera               | 4        | 7.14%   |
| Logitech C922 Pro Stream Webcam             | 3        | 5.36%   |
| Jieli USB PHY 2.0                           | 3        | 5.36%   |
| Z-Star Venus USB2.0 Camera                  | 2        | 3.57%   |
| Logitech Webcam C310                        | 2        | 3.57%   |
| Logitech Webcam C270                        | 2        | 3.57%   |
| Logitech HD Webcam C525                     | 2        | 3.57%   |
| Arkmicro USB2.0 PC CAMERA                   | 2        | 3.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X             | 2        | 3.57%   |
| Z-Star Vimicro USB Camera (Altair)          | 1        | 1.79%   |
| Z-Star Vega USB 2.0 Camera.                 | 1        | 1.79%   |
| Z-Star Sirius USB2.0 Camera                 | 1        | 1.79%   |
| Z-Star A4 TECH HD PC Camera                 | 1        | 1.79%   |
| Sonix USB 2.0 Camera                        | 1        | 1.79%   |
| Realtek HP 2.0MP High Definition Webcam     | 1        | 1.79%   |
| Novatel Wireless Merlin U740 (non-Vodafone) | 1        | 1.79%   |
| Novatek USB HD Camera                       | 1        | 1.79%   |
| Novatek HP High Definition 2MP Webcam       | 1        | 1.79%   |
| Microsoft LifeCam Studio                    | 1        | 1.79%   |
| Microsoft LifeCam HD-5000                   | 1        | 1.79%   |
| Microdia Webcam Vitade AF                   | 1        | 1.79%   |
| Microdia Sonix USB 2.0 Camera               | 1        | 1.79%   |
| Microdia Integrated Camera                  | 1        | 1.79%   |
| MacroSilicon USB Video                      | 1        | 1.79%   |
| Logitech Webcam C300                        | 1        | 1.79%   |
| Logitech Webcam C110                        | 1        | 1.79%   |
| Logitech QuickCam Communicate MP/S5500      | 1        | 1.79%   |
| Logitech HD Webcam C910                     | 1        | 1.79%   |
| Logitech HD Pro Webcam C920                 | 1        | 1.79%   |
| Google Nexus/Pixel Device (MTP + debug)     | 1        | 1.79%   |
| Genesys Logic USB2.0 UVC PC Camera          | 1        | 1.79%   |
| Generalplus GENERAL WEBCAM                  | 1        | 1.79%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 1.79%   |
| eMPIA USB 2.0 Webcam                        | 1        | 1.79%   |
| Creative Live! Cam Sync 1080p V2            | 1        | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                | 1        | 1.79%   |
| Arkmicro Webcam Carrefour                   | 1        | 1.79%   |
| Allwinner TP1005                            | 1        | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 3        | 50%     |
| Alcor Micro           | 2        | 33.33%  |
| Gemalto (was Gemplus) | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader              | 2        | 33.33%  |
| Advanced Card Systems ACR38 SmartCard Reader     | 2        | 33.33%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1        | 16.67%  |
| Advanced Card Systems ACR39U                     | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 375      | 86.81%  |
| 1     | 51       | 11.81%  |
| 2     | 5        | 1.16%   |
| 3     | 1        | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 25       | 39.68%  |
| Net/wireless             | 10       | 15.87%  |
| Chipcard                 | 5        | 7.94%   |
| Multimedia controller    | 4        | 6.35%   |
| Sound                    | 3        | 4.76%   |
| Network                  | 3        | 4.76%   |
| Communication controller | 3        | 4.76%   |
| Camera                   | 3        | 4.76%   |
| Unassigned class         | 2        | 3.17%   |
| Storage/raid             | 1        | 1.59%   |
| Storage/ide              | 1        | 1.59%   |
| Net/ethernet             | 1        | 1.59%   |
| Fingerprint reader       | 1        | 1.59%   |
| Bluetooth                | 1        | 1.59%   |

