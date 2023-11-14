AlmaLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/AlmaLinux/Desktop/README.md) and [notebooks](/Dist/AlmaLinux/Notebook/README.md).

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

Total: 285

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Supermicro    | H12SSL-i                    | Server      | [0bcc882e05](https://linux-hardware.org/?probe=0bcc882e05) | Nov 06, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [963acb5f2b](https://linux-hardware.org/?probe=963acb5f2b) | Nov 06, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [e3760a331a](https://linux-hardware.org/?probe=e3760a331a) | Oct 31, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [ad21a28397](https://linux-hardware.org/?probe=ad21a28397) | Oct 28, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [166a51fa8d](https://linux-hardware.org/?probe=166a51fa8d) | Oct 27, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [492563a83c](https://linux-hardware.org/?probe=492563a83c) | Oct 24, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3e4b32b047](https://linux-hardware.org/?probe=3e4b32b047) | Oct 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3880cb8ecf](https://linux-hardware.org/?probe=3880cb8ecf) | Oct 22, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [7cdd3de48b](https://linux-hardware.org/?probe=7cdd3de48b) | Oct 22, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8deecaac39](https://linux-hardware.org/?probe=8deecaac39) | Oct 21, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [a0ebc9b489](https://linux-hardware.org/?probe=a0ebc9b489) | Oct 21, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [de8a8232ba](https://linux-hardware.org/?probe=de8a8232ba) | Oct 19, 2023 |
| Dell          | Precision 7760              | Notebook    | [4b42c6c7f1](https://linux-hardware.org/?probe=4b42c6c7f1) | Oct 14, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [d9bbe8269c](https://linux-hardware.org/?probe=d9bbe8269c) | Oct 10, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [27ce5f6a61](https://linux-hardware.org/?probe=27ce5f6a61) | Oct 06, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [ccdf9d0cfa](https://linux-hardware.org/?probe=ccdf9d0cfa) | Oct 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [527518057b](https://linux-hardware.org/?probe=527518057b) | Oct 02, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [88e4c09c2f](https://linux-hardware.org/?probe=88e4c09c2f) | Oct 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [53fec3f094](https://linux-hardware.org/?probe=53fec3f094) | Oct 01, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9115ea465f](https://linux-hardware.org/?probe=9115ea465f) | Oct 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ce97609be](https://linux-hardware.org/?probe=6ce97609be) | Sep 30, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [da0e120624](https://linux-hardware.org/?probe=da0e120624) | Sep 30, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [1b72177563](https://linux-hardware.org/?probe=1b72177563) | Sep 26, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [2527f2a9fc](https://linux-hardware.org/?probe=2527f2a9fc) | Sep 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3e533c5366](https://linux-hardware.org/?probe=3e533c5366) | Sep 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d37c8958bf](https://linux-hardware.org/?probe=d37c8958bf) | Sep 25, 2023 |
| HP            | Laptop 14-ep0xxx            | Notebook    | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| Dell          | Latitude E5420              | Notebook    | [0b1b042a5b](https://linux-hardware.org/?probe=0b1b042a5b) | Sep 19, 2023 |
| HP            | Notebook                    | Notebook    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac96127f34](https://linux-hardware.org/?probe=ac96127f34) | Sep 08, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [779e2ad458](https://linux-hardware.org/?probe=779e2ad458) | Sep 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c0498360ff](https://linux-hardware.org/?probe=c0498360ff) | Sep 07, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [6cc92a61b2](https://linux-hardware.org/?probe=6cc92a61b2) | Sep 07, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f06bf24212](https://linux-hardware.org/?probe=f06bf24212) | Sep 05, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [167ab1eb1c](https://linux-hardware.org/?probe=167ab1eb1c) | Sep 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [dc9d1ca231](https://linux-hardware.org/?probe=dc9d1ca231) | Sep 04, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b980688633](https://linux-hardware.org/?probe=b980688633) | Sep 04, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| Dell          | Latitude 5490               | Notebook    | [058fba578a](https://linux-hardware.org/?probe=058fba578a) | Aug 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Dell          | 00WGD1 A01                  | Server      | [d288d87ab5](https://linux-hardware.org/?probe=d288d87ab5) | Aug 14, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d61d7e9135](https://linux-hardware.org/?probe=d61d7e9135) | Aug 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d319474025](https://linux-hardware.org/?probe=d319474025) | Aug 13, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0b7f8d13d9](https://linux-hardware.org/?probe=0b7f8d13d9) | Aug 12, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [8a896a42c0](https://linux-hardware.org/?probe=8a896a42c0) | Aug 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b7245ccb6f](https://linux-hardware.org/?probe=b7245ccb6f) | Aug 11, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [cff9e815b3](https://linux-hardware.org/?probe=cff9e815b3) | Aug 11, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d8939be040](https://linux-hardware.org/?probe=d8939be040) | Aug 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [35b274571c](https://linux-hardware.org/?probe=35b274571c) | Aug 05, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [92d07e2cae](https://linux-hardware.org/?probe=92d07e2cae) | Aug 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [592e977971](https://linux-hardware.org/?probe=592e977971) | Aug 04, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d05269baea](https://linux-hardware.org/?probe=d05269baea) | Aug 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [e5659701d5](https://linux-hardware.org/?probe=e5659701d5) | Jul 26, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b84ef586e7](https://linux-hardware.org/?probe=b84ef586e7) | Jul 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [68cf987c86](https://linux-hardware.org/?probe=68cf987c86) | Jul 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [8dc4e130f9](https://linux-hardware.org/?probe=8dc4e130f9) | Jul 25, 2023 |
| HP            | 17-ak041ur                  | Notebook    | [5881affa24](https://linux-hardware.org/?probe=5881affa24) | Jul 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [058672ddad](https://linux-hardware.org/?probe=058672ddad) | Jul 18, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [757ed62cbc](https://linux-hardware.org/?probe=757ed62cbc) | Jul 14, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [41261aa128](https://linux-hardware.org/?probe=41261aa128) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ab93f5aa6e](https://linux-hardware.org/?probe=ab93f5aa6e) | Jul 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59f9ee3ee8](https://linux-hardware.org/?probe=59f9ee3ee8) | Jul 09, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2ee9eaf9d4](https://linux-hardware.org/?probe=2ee9eaf9d4) | Jul 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a686a6eed6](https://linux-hardware.org/?probe=a686a6eed6) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b7e8961ef5](https://linux-hardware.org/?probe=b7e8961ef5) | Jul 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da271abdd3](https://linux-hardware.org/?probe=da271abdd3) | Jul 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2beb4fa40d](https://linux-hardware.org/?probe=2beb4fa40d) | Jul 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92bf7e658e](https://linux-hardware.org/?probe=92bf7e658e) | Jul 02, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c86548f8aa](https://linux-hardware.org/?probe=c86548f8aa) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [57424619e8](https://linux-hardware.org/?probe=57424619e8) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70ed50862c](https://linux-hardware.org/?probe=70ed50862c) | Jun 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [52b4c086dc](https://linux-hardware.org/?probe=52b4c086dc) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c7e845c965](https://linux-hardware.org/?probe=c7e845c965) | Jun 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f36489e090](https://linux-hardware.org/?probe=f36489e090) | Jun 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d56f78f3ca](https://linux-hardware.org/?probe=d56f78f3ca) | Jun 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cf3b44c0b6](https://linux-hardware.org/?probe=cf3b44c0b6) | Jun 25, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2256046a01](https://linux-hardware.org/?probe=2256046a01) | Jun 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8738063b30](https://linux-hardware.org/?probe=8738063b30) | Jun 11, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15fb7b8736](https://linux-hardware.org/?probe=15fb7b8736) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a777ee9e06](https://linux-hardware.org/?probe=a777ee9e06) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7b384a40ce](https://linux-hardware.org/?probe=7b384a40ce) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [1243c65107](https://linux-hardware.org/?probe=1243c65107) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15e410d9f7](https://linux-hardware.org/?probe=15e410d9f7) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b1d9682c13](https://linux-hardware.org/?probe=b1d9682c13) | May 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [399cce0d30](https://linux-hardware.org/?probe=399cce0d30) | May 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15d9c6fce4](https://linux-hardware.org/?probe=15d9c6fce4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [531455206b](https://linux-hardware.org/?probe=531455206b) | May 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [5726f59661](https://linux-hardware.org/?probe=5726f59661) | May 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [12a444a75a](https://linux-hardware.org/?probe=12a444a75a) | May 23, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9cc4cbef4a](https://linux-hardware.org/?probe=9cc4cbef4a) | May 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0f9deafb62](https://linux-hardware.org/?probe=0f9deafb62) | May 22, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [3d9b02954b](https://linux-hardware.org/?probe=3d9b02954b) | May 16, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [40aa9853c4](https://linux-hardware.org/?probe=40aa9853c4) | May 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [465488c540](https://linux-hardware.org/?probe=465488c540) | May 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8d933d6988](https://linux-hardware.org/?probe=8d933d6988) | May 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [413d3b7b92](https://linux-hardware.org/?probe=413d3b7b92) | May 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f074512a99](https://linux-hardware.org/?probe=f074512a99) | May 13, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a69d13961](https://linux-hardware.org/?probe=2a69d13961) | May 13, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [afd35343ad](https://linux-hardware.org/?probe=afd35343ad) | May 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [208afe074a](https://linux-hardware.org/?probe=208afe074a) | May 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac5899bc10](https://linux-hardware.org/?probe=ac5899bc10) | May 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [64bd100bb5](https://linux-hardware.org/?probe=64bd100bb5) | May 09, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [55af41b298](https://linux-hardware.org/?probe=55af41b298) | May 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [28a1f44a1e](https://linux-hardware.org/?probe=28a1f44a1e) | May 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0f5dab42d2](https://linux-hardware.org/?probe=0f5dab42d2) | May 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2849b9a200](https://linux-hardware.org/?probe=2849b9a200) | May 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [028a3c3b0b](https://linux-hardware.org/?probe=028a3c3b0b) | May 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [34e7df2c84](https://linux-hardware.org/?probe=34e7df2c84) | May 01, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [457abef5d3](https://linux-hardware.org/?probe=457abef5d3) | May 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [31789f9473](https://linux-hardware.org/?probe=31789f9473) | Apr 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f46e9f6ba7](https://linux-hardware.org/?probe=f46e9f6ba7) | Apr 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [be2089d630](https://linux-hardware.org/?probe=be2089d630) | Apr 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9fdfb825c7](https://linux-hardware.org/?probe=9fdfb825c7) | Apr 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9465aab832](https://linux-hardware.org/?probe=9465aab832) | Apr 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b24f39801d](https://linux-hardware.org/?probe=b24f39801d) | Apr 26, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [ddf678b11a](https://linux-hardware.org/?probe=ddf678b11a) | Apr 20, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c370821f44](https://linux-hardware.org/?probe=c370821f44) | Apr 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [6e9640e9c2](https://linux-hardware.org/?probe=6e9640e9c2) | Apr 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6eb92e0ea0](https://linux-hardware.org/?probe=6eb92e0ea0) | Apr 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9dd9a74143](https://linux-hardware.org/?probe=9dd9a74143) | Apr 12, 2023 |
| MSI           | B85-G43                     | Desktop     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac75c58117](https://linux-hardware.org/?probe=ac75c58117) | Apr 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d699519c30](https://linux-hardware.org/?probe=d699519c30) | Apr 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9ef8e7a3d6](https://linux-hardware.org/?probe=9ef8e7a3d6) | Apr 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fbd686e3e2](https://linux-hardware.org/?probe=fbd686e3e2) | Apr 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [61297d4bc4](https://linux-hardware.org/?probe=61297d4bc4) | Apr 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [3c3474d69b](https://linux-hardware.org/?probe=3c3474d69b) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [21f6af6f50](https://linux-hardware.org/?probe=21f6af6f50) | Mar 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [586decd061](https://linux-hardware.org/?probe=586decd061) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [56d537b480](https://linux-hardware.org/?probe=56d537b480) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0fc5cf1944](https://linux-hardware.org/?probe=0fc5cf1944) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [173e6ad8bf](https://linux-hardware.org/?probe=173e6ad8bf) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [43b58e51b4](https://linux-hardware.org/?probe=43b58e51b4) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6b87ac7144](https://linux-hardware.org/?probe=6b87ac7144) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f98fe964b2](https://linux-hardware.org/?probe=f98fe964b2) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [da9d93a7ea](https://linux-hardware.org/?probe=da9d93a7ea) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [81c9f3a796](https://linux-hardware.org/?probe=81c9f3a796) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ff1f611cc9](https://linux-hardware.org/?probe=ff1f611cc9) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [975790ee68](https://linux-hardware.org/?probe=975790ee68) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3b0e50edda](https://linux-hardware.org/?probe=3b0e50edda) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [126100b078](https://linux-hardware.org/?probe=126100b078) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| Google        | Kefka                       | Notebook    | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ecc72101c](https://linux-hardware.org/?probe=6ecc72101c) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cf977da464](https://linux-hardware.org/?probe=cf977da464) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0001e56a68](https://linux-hardware.org/?probe=0001e56a68) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [016e12b43e](https://linux-hardware.org/?probe=016e12b43e) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [4599836936](https://linux-hardware.org/?probe=4599836936) | Feb 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | 8455                        | Desktop     | [ffc8587d29](https://linux-hardware.org/?probe=ffc8587d29) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [84ba50b16d](https://linux-hardware.org/?probe=84ba50b16d) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ee7dbe4f81](https://linux-hardware.org/?probe=ee7dbe4f81) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| AZW           | SER                         | Mini pc     | [dd0c654d95](https://linux-hardware.org/?probe=dd0c654d95) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a0f53917f9](https://linux-hardware.org/?probe=a0f53917f9) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [04a26e636e](https://linux-hardware.org/?probe=04a26e636e) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [5b505d5d7a](https://linux-hardware.org/?probe=5b505d5d7a) | Feb 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cca8d74416](https://linux-hardware.org/?probe=cca8d74416) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f0884ec1aa](https://linux-hardware.org/?probe=f0884ec1aa) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [89430aeb82](https://linux-hardware.org/?probe=89430aeb82) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6d079ed3ca](https://linux-hardware.org/?probe=6d079ed3ca) | Jan 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d81d33bda5](https://linux-hardware.org/?probe=d81d33bda5) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [091b3e37fb](https://linux-hardware.org/?probe=091b3e37fb) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [49654976af](https://linux-hardware.org/?probe=49654976af) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d41a70cbf5](https://linux-hardware.org/?probe=d41a70cbf5) | Jan 28, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [af868046e3](https://linux-hardware.org/?probe=af868046e3) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7c026252d0](https://linux-hardware.org/?probe=7c026252d0) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [bd3f6fa130](https://linux-hardware.org/?probe=bd3f6fa130) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [477f1a3aad](https://linux-hardware.org/?probe=477f1a3aad) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | Falco                       | Notebook    | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [2b4b7560b7](https://linux-hardware.org/?probe=2b4b7560b7) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [56758aeb6f](https://linux-hardware.org/?probe=56758aeb6f) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ec3b130618](https://linux-hardware.org/?probe=ec3b130618) | Jan 07, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| HP            | Falco                       | Notebook    | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4571b799f0](https://linux-hardware.org/?probe=4571b799f0) | Dec 20, 2022 |
| Optimized ... | KVM                         | Desktop     | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [ef43d1f352](https://linux-hardware.org/?probe=ef43d1f352) | Nov 03, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| Acer          | TravelMate 5735Z            | Notebook    | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e56cce9c8](https://linux-hardware.org/?probe=7e56cce9c8) | Sep 17, 2022 |
| HP            | Falco                       | Notebook    | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP            | ENVY dv6                    | Notebook    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google        | Kohaku                      | Notebook    | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google        | Kohaku                      | Notebook    | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo        | ThinkPad T440s 20ARS32P0... | Notebook    | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Dell          | 060K5C A06                  | Server      | [c8be539d80](https://linux-hardware.org/?probe=c8be539d80) | May 14, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| Dell          | 0R4CNN A02                  | Server      | [c701d3a15f](https://linux-hardware.org/?probe=c701d3a15f) | Feb 07, 2022 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c28c41bdd4](https://linux-hardware.org/?probe=c28c41bdd4) | Nov 05, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [972f935578](https://linux-hardware.org/?probe=972f935578) | Aug 23, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.1 | 22        | 23.66%  |
| AlmaLinux 9.2 | 18        | 19.35%  |
| AlmaLinux 8.7 | 10        | 10.75%  |
| AlmaLinux 8.6 | 10        | 10.75%  |
| AlmaLinux 9.0 | 9         | 9.68%   |
| AlmaLinux 8.4 | 9         | 9.68%   |
| AlmaLinux 8.8 | 8         | 8.6%    |
| AlmaLinux 8.3 | 4         | 4.3%    |
| AlmaLinux 8.5 | 3         | 3.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 88        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64   | 9         | 8.57%   |
| 5.14.0-284.30.1.el9_2.x86_64  | 7         | 6.67%   |
| 5.14.0-162.12.1.el9_1.x86_64  | 6         | 5.71%   |
| 4.18.0-425.3.1.el8.x86_64     | 6         | 5.71%   |
| 4.18.0-477.21.1.el8_8.x86_64  | 5         | 4.76%   |
| 5.14.0-284.25.1.el9_2.x86_64  | 4         | 3.81%   |
| 4.18.0-477.13.1.el8_8.x86_64  | 4         | 3.81%   |
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 2.86%   |
| 5.14.0-284.18.1.el9_2.x86_64  | 3         | 2.86%   |
| 5.14.0-284.11.1.el9_2.x86_64  | 3         | 2.86%   |
| 5.14.0-162.18.1.el9_1.x86_64  | 3         | 2.86%   |
| 4.18.0-477.27.2.el8_8.x86_64  | 3         | 2.86%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 2.86%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 2.86%   |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 1.9%    |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 1.9%    |
| 5.14.0-162.22.2.el9_1.x86_64  | 2         | 1.9%    |
| 4.18.0-477.27.1.el8_8.x86_64  | 2         | 1.9%    |
| 4.18.0-477.15.1.el8_8.x86_64  | 2         | 1.9%    |
| 4.18.0-477.10.1.el8_8.x86_64  | 2         | 1.9%    |
| 4.18.0-425.19.2.el8_7.x86_64  | 2         | 1.9%    |
| 4.18.0-425.13.1.el8_7.x86_64  | 2         | 1.9%    |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 1.9%    |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 1.9%    |
| 4.18.0-305.el8.x86_64         | 2         | 1.9%    |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 1.9%    |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 1.9%    |
| 6.4.0-1.el8.elrepo.x86_64     | 1         | 0.95%   |
| 6.3.0-2.el9.elrepo.x86_64     | 1         | 0.95%   |
| 6.1.24-1kx.el9.x86_64         | 1         | 0.95%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 0.95%   |
| 5.15.45-v8.1.el8              | 1         | 0.95%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 1         | 0.95%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 0.95%   |
| 5.14.0-162.23.1.el9_1.x86_64  | 1         | 0.95%   |
| 5.10.60-v8.1.el8              | 1         | 0.95%   |
| 4.18.0-425.10.1.el8_7.x86_64  | 1         | 0.95%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 0.95%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 0.95%   |
| 4.18.0-348.el8.x86_64         | 1         | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 47        | 52.22%  |
| 4.18.0  | 37        | 41.11%  |
| 6.4.0   | 1         | 1.11%   |
| 6.3.0   | 1         | 1.11%   |
| 6.1.24  | 1         | 1.11%   |
| 5.4.175 | 1         | 1.11%   |
| 5.15.45 | 1         | 1.11%   |
| 5.10.60 | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 47        | 52.22%  |
| 4.18    | 37        | 41.11%  |
| 6.4     | 1         | 1.11%   |
| 6.3     | 1         | 1.11%   |
| 6.1     | 1         | 1.11%   |
| 5.4     | 1         | 1.11%   |
| 5.15    | 1         | 1.11%   |
| 5.10    | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 85        | 96.59%  |
| aarch64 | 3         | 3.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 52        | 59.09%  |
| Unknown         | 20        | 22.73%  |
| XFCE            | 5         | 5.68%   |
| KDE5            | 5         | 5.68%   |
| MATE            | 3         | 3.41%   |
| GNOME Classic   | 2         | 2.27%   |
| GNOME Flashback | 1         | 1.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 42        | 47.19%  |
| X11     | 35        | 39.33%  |
| Unknown | 8         | 8.99%   |
| Tty     | 4         | 4.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 52        | 59.09%  |
| GDM     | 31        | 35.23%  |
| LightDM | 3         | 3.41%   |
| SDDM    | 2         | 2.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 47        | 51.65%  |
| en_GB   | 10        | 10.99%  |
| de_DE   | 7         | 7.69%   |
| fr_FR   | 4         | 4.4%    |
| en_CA   | 4         | 4.4%    |
| C       | 4         | 4.4%    |
| Unknown | 3         | 3.3%    |
| ru_RU   | 2         | 2.2%    |
| pl_PL   | 2         | 2.2%    |
| uk_UA   | 1         | 1.1%    |
| ru_UA   | 1         | 1.1%    |
| hu_HU   | 1         | 1.1%    |
| es_VE   | 1         | 1.1%    |
| es_ES   | 1         | 1.1%    |
| en_IN   | 1         | 1.1%    |
| en_AU   | 1         | 1.1%    |
| da_DK   | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 61        | 67.78%  |
| BIOS | 29        | 32.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 68        | 77.27%  |
| Ext4    | 19        | 21.59%  |
| Overlay | 1         | 1.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 48        | 54.55%  |
| Unknown | 31        | 35.23%  |
| MBR     | 9         | 10.23%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 86.36%  |
| Yes       | 12        | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 82.95%  |
| Yes       | 15        | 17.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 17        | 19.32%  |
| Lenovo                  | 16        | 18.18%  |
| Dell                    | 12        | 13.64%  |
| ASUSTek Computer        | 7         | 7.95%   |
| Gigabyte Technology     | 6         | 6.82%   |
| MSI                     | 5         | 5.68%   |
| Intel                   | 4         | 4.55%   |
| Supermicro              | 3         | 3.41%   |
| ASRockRack              | 3         | 3.41%   |
| Raspberry Pi Foundation | 2         | 2.27%   |
| Google                  | 2         | 2.27%   |
| ASRock                  | 2         | 2.27%   |
| Acer                    | 2         | 2.27%   |
| TUXEDO                  | 1         | 1.14%   |
| Toshiba                 | 1         | 1.14%   |
| Timi                    | 1         | 1.14%   |
| Optimized Hosting       | 1         | 1.14%   |
| Notebook                | 1         | 1.14%   |
| Maibenben               | 1         | 1.14%   |
| AZW                     | 1         | 1.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 2.27%   |
| TUXEDO Aura 15 Gen1                  | 1         | 1.14%   |
| Toshiba Satellite L50-C              | 1         | 1.14%   |
| Timi RedmiBook 14-APCS               | 1         | 1.14%   |
| Supermicro Super Server              | 1         | 1.14%   |
| Supermicro PIO-617R-TLN4F+-ST031     | 1         | 1.14%   |
| Supermicro motherboard-H12 Series    | 1         | 1.14%   |
| Optimized Hosting KVM                | 1         | 1.14%   |
| Notebook NS50_70MU                   | 1         | 1.14%   |
| MSI MS-7D07                          | 1         | 1.14%   |
| MSI MS-7C95                          | 1         | 1.14%   |
| MSI MS-7900                          | 1         | 1.14%   |
| MSI MS-7816                          | 1         | 1.14%   |
| MSI GL75 9SE                         | 1         | 1.14%   |
| Maibenben MaiBook X series           | 1         | 1.14%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.14%   |
| Lenovo V14-ARE 82DQ                  | 1         | 1.14%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 1.14%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 1.14%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 1.14%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS | 1         | 1.14%   |
| Lenovo ThinkPad E14 Gen 2 20TBS0CK00 | 1         | 1.14%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 1.14%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 1.14%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS    | 1         | 1.14%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 1.14%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 1.14%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.14%   |
| Lenovo H520S 10093                   | 1         | 1.14%   |
| Lenovo G580 20157                    | 1         | 1.14%   |
| Lenovo B50-30 20382                  | 1         | 1.14%   |
| Intel TTL TEKNOPRO                   | 1         | 1.14%   |
| Intel powered classmate PC           | 1         | 1.14%   |
| Intel NUC8i5BEH                      | 1         | 1.14%   |
| Intel NUC6i5SYB H81131-503           | 1         | 1.14%   |
| HP ZBook 17 G2                       | 1         | 1.14%   |
| HP Z820 Workstation                  | 1         | 1.14%   |
| HP Z620 Workstation                  | 1         | 1.14%   |
| HP Z600 Workstation                  | 1         | 1.14%   |
| HP Z4 G4 Workstation                 | 1         | 1.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo ThinkPad                  | 4         | 4.55%   |
| Lenovo IdeaPad                   | 3         | 3.41%   |
| HP Laptop                        | 3         | 3.41%   |
| HP EliteBook                     | 3         | 3.41%   |
| Dell Latitude                    | 3         | 3.41%   |
| Dell Inspiron                    | 3         | 3.41%   |
| RPi Raspberry                    | 2         | 2.27%   |
| Lenovo Legion                    | 2         | 2.27%   |
| Dell Precision                   | 2         | 2.27%   |
| Dell PowerEdge                   | 2         | 2.27%   |
| TUXEDO Aura                      | 1         | 1.14%   |
| Toshiba Satellite                | 1         | 1.14%   |
| Timi RedmiBook                   | 1         | 1.14%   |
| Supermicro Super                 | 1         | 1.14%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1         | 1.14%   |
| Supermicro motherboard-H12       | 1         | 1.14%   |
| Optimized Hosting KVM            | 1         | 1.14%   |
| Notebook NS50                    | 1         | 1.14%   |
| MSI MS-7D07                      | 1         | 1.14%   |
| MSI MS-7C95                      | 1         | 1.14%   |
| MSI MS-7900                      | 1         | 1.14%   |
| MSI MS-7816                      | 1         | 1.14%   |
| MSI GL75                         | 1         | 1.14%   |
| Maibenben MaiBook                | 1         | 1.14%   |
| Lenovo Yoga                      | 1         | 1.14%   |
| Lenovo V14-ARE                   | 1         | 1.14%   |
| Lenovo ThinkStation              | 1         | 1.14%   |
| Lenovo IdeaPadFlex               | 1         | 1.14%   |
| Lenovo H520S                     | 1         | 1.14%   |
| Lenovo G580                      | 1         | 1.14%   |
| Lenovo B50-30                    | 1         | 1.14%   |
| Intel TTL                        | 1         | 1.14%   |
| Intel powered                    | 1         | 1.14%   |
| Intel NUC8i5BEH                  | 1         | 1.14%   |
| Intel NUC6i5SYB                  | 1         | 1.14%   |
| HP ZBook                         | 1         | 1.14%   |
| HP Z820                          | 1         | 1.14%   |
| HP Z620                          | 1         | 1.14%   |
| HP Z600                          | 1         | 1.14%   |
| HP Z4                            | 1         | 1.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 18        | 20.45%  |
| 2012    | 10        | 11.36%  |
| 2021    | 9         | 10.23%  |
| 2019    | 8         | 9.09%   |
| 2022    | 7         | 7.95%   |
| 2018    | 7         | 7.95%   |
| 2014    | 5         | 5.68%   |
| 2015    | 4         | 4.55%   |
| 2013    | 4         | 4.55%   |
| 2011    | 4         | 4.55%   |
| 2023    | 3         | 3.41%   |
| 2017    | 2         | 2.27%   |
| 2016    | 2         | 2.27%   |
| 2010    | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |
| 2009    | 1         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 43        | 48.86%  |
| Desktop        | 29        | 32.95%  |
| Server         | 9         | 10.23%  |
| Mini pc        | 3         | 3.41%   |
| System on chip | 2         | 2.27%   |
| Convertible    | 2         | 2.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 88.76%  |
| Enabled  | 10        | 11.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 85        | 96.59%  |
| Yes  | 3         | 3.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 21        | 23.6%   |
| 4.01-8.0        | 19        | 21.35%  |
| 64.01-256.0     | 14        | 15.73%  |
| 3.01-4.0        | 8         | 8.99%   |
| 16.01-24.0      | 7         | 7.87%   |
| More than 256.0 | 6         | 6.74%   |
| 32.01-64.0      | 6         | 6.74%   |
| 24.01-32.0      | 4         | 4.49%   |
| 1.01-2.0        | 2         | 2.25%   |
| 0.51-1.0        | 2         | 2.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 24        | 26.09%  |
| 3.01-4.0        | 17        | 18.48%  |
| 1.01-2.0        | 16        | 17.39%  |
| 4.01-8.0        | 15        | 16.3%   |
| 8.01-16.0       | 4         | 4.35%   |
| 32.01-64.0      | 3         | 3.26%   |
| 16.01-24.0      | 3         | 3.26%   |
| 0.51-1.0        | 3         | 3.26%   |
| 24.01-32.0      | 2         | 2.17%   |
| 64.01-256.0     | 2         | 2.17%   |
| 0.01-0.5        | 2         | 2.17%   |
| More than 256.0 | 1         | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 44.44%  |
| 2      | 26        | 28.89%  |
| 3      | 8         | 8.89%   |
| 4      | 6         | 6.67%   |
| 6      | 3         | 3.33%   |
| 5      | 2         | 2.22%   |
| 0      | 2         | 2.22%   |
| 12     | 1         | 1.11%   |
| 11     | 1         | 1.11%   |
| 10     | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 75.28%  |
| Yes       | 22        | 24.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 84.09%  |
| No        | 14        | 15.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 64.77%  |
| No        | 31        | 35.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 57.95%  |
| No        | 37        | 42.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 22        | 25%     |
| Germany      | 8         | 9.09%   |
| France       | 7         | 7.95%   |
| UK           | 5         | 5.68%   |
| Russia       | 5         | 5.68%   |
| Canada       | 5         | 5.68%   |
| Netherlands  | 3         | 3.41%   |
| Hungary      | 3         | 3.41%   |
| Ukraine      | 2         | 2.27%   |
| Switzerland  | 2         | 2.27%   |
| Spain        | 2         | 2.27%   |
| South Africa | 2         | 2.27%   |
| Romania      | 2         | 2.27%   |
| Poland       | 2         | 2.27%   |
| Indonesia    | 2         | 2.27%   |
| India        | 2         | 2.27%   |
| China        | 2         | 2.27%   |
| Venezuela    | 1         | 1.14%   |
| Sweden       | 1         | 1.14%   |
| Puerto Rico  | 1         | 1.14%   |
| Pakistan     | 1         | 1.14%   |
| Mexico       | 1         | 1.14%   |
| Kazakhstan   | 1         | 1.14%   |
| Greenland    | 1         | 1.14%   |
| Finland      | 1         | 1.14%   |
| Bulgaria     | 1         | 1.14%   |
| Belgium      | 1         | 1.14%   |
| Austria      | 1         | 1.14%   |
| Australia    | 1         | 1.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Hamburg          | 3         | 3.33%   |
| Tunari           | 2         | 2.22%   |
| Saint-Brieuc     | 2         | 2.22%   |
| Queens           | 2         | 2.22%   |
| Johannesburg     | 2         | 2.22%   |
| Dallas           | 2         | 2.22%   |
| Zaporizhzhia     | 1         | 1.11%   |
| Zandvoort        | 1         | 1.11%   |
| Winterswijk      | 1         | 1.11%   |
| Wilmington       | 1         | 1.11%   |
| Wejherowo        | 1         | 1.11%   |
| Warsaw           | 1         | 1.11%   |
| Vienna           | 1         | 1.11%   |
| Varosfoeld       | 1         | 1.11%   |
| Uppsala          | 1         | 1.11%   |
| Tuusula          | 1         | 1.11%   |
| Tampa            | 1         | 1.11%   |
| Suzhou           | 1         | 1.11%   |
| Strasbourg       | 1         | 1.11%   |
| Stadtilm         | 1         | 1.11%   |
| St. Paul         | 1         | 1.11%   |
| South Tangerang  | 1         | 1.11%   |
| Sofia            | 1         | 1.11%   |
| Shimanovsk       | 1         | 1.11%   |
| Shanghai         | 1         | 1.11%   |
| San Diego        | 1         | 1.11%   |
| Saint-Cloud      | 1         | 1.11%   |
| Rothwell         | 1         | 1.11%   |
| Rochester        | 1         | 1.11%   |
| Regina           | 1         | 1.11%   |
| Redlands         | 1         | 1.11%   |
| Penza            | 1         | 1.11%   |
| Parla            | 1         | 1.11%   |
| Paris            | 1         | 1.11%   |
| Nizhniy Novgorod | 1         | 1.11%   |
| Moscow           | 1         | 1.11%   |
| Miami            | 1         | 1.11%   |
| Mangalore        | 1         | 1.11%   |
| Los Angeles      | 1         | 1.11%   |
| London           | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 21        | 28     | 15.91%  |
| Seagate                     | 18        | 30     | 13.64%  |
| WDC                         | 17        | 34     | 12.88%  |
| Sandisk                     | 7         | 10     | 5.3%    |
| SK hynix                    | 6         | 6      | 4.55%   |
| Kingston                    | 6         | 8      | 4.55%   |
| Intel                       | 6         | 7      | 4.55%   |
| Kingston Technology Company | 5         | 27     | 3.79%   |
| Unknown                     | 4         | 6      | 3.03%   |
| Micron Technology           | 4         | 5      | 3.03%   |
| Crucial                     | 4         | 12     | 3.03%   |
| Toshiba                     | 3         | 4      | 2.27%   |
| Netac                       | 3         | 3      | 2.27%   |
| LITEONIT                    | 2         | 4      | 1.52%   |
| KIOXIA                      | 2         | 2      | 1.52%   |
| Hitachi                     | 2         | 2      | 1.52%   |
| HGST                        | 2         | 2      | 1.52%   |
| Hewlett-Packard             | 2         | 9      | 1.52%   |
| Dell                        | 2         | 3      | 1.52%   |
| Union Memory                | 1         | 1      | 0.76%   |
| Transcend                   | 1         | 1      | 0.76%   |
| Team                        | 1         | 1      | 0.76%   |
| SSSTC                       | 1         | 1      | 0.76%   |
| Silicon Motion              | 1         | 14     | 0.76%   |
| QEMU                        | 1         | 1      | 0.76%   |
| Plextor                     | 1         | 1      | 0.76%   |
| Phison                      | 1         | 1      | 0.76%   |
| LITEON                      | 1         | 1      | 0.76%   |
| Emtec                       | 1         | 2      | 0.76%   |
| DELLBOSS                    | 1         | 1      | 0.76%   |
| China                       | 1         | 1      | 0.76%   |
| ASMT                        | 1         | 2      | 0.76%   |
| AMD                         | 1         | 10     | 0.76%   |
| A-DATA Technology           | 1         | 1      | 0.76%   |
| Unknown                     | 1         | 10     | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 1.9%    |
| WDC WD10SPZX-24Z10 1TB                            | 2         | 1.27%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2         | 1.27%   |
| SK hynix SC311 SATA 256GB SSD                     | 2         | 1.27%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                    | 2         | 1.27%   |
| Kingston Company KC2000 NVMe SSD 1TB              | 2         | 1.27%   |
| Kingston Company A2000 NVMe SSD 250GB             | 2         | 1.27%   |
| Kingston SA400S37480G 480GB SSD                   | 2         | 1.27%   |
| Crucial CT240BX500SSD1 240GB                      | 2         | 1.27%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 0.63%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 0.63%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.63%   |
| WDC WD40EZRX-00SPEB0 4TB                          | 1         | 0.63%   |
| WDC WD40EFZX-68AWUN0 4TB                          | 1         | 0.63%   |
| WDC WD40EFRX-68N32N0 4TB                          | 1         | 0.63%   |
| WDC WD4000FYYZ-01UL1B2 4TB                        | 1         | 0.63%   |
| WDC WD4000FYYZ-01UL1B1 4TB                        | 1         | 0.63%   |
| WDC WD4000FDYZ-27YA5B0 4TB                        | 1         | 0.63%   |
| WDC WD4000F9YZ-09N20L1 4TB                        | 1         | 0.63%   |
| WDC WD3600FYYZ-01UL1B3 4TB                        | 1         | 0.63%   |
| WDC WD3600FYYZ-01UL1B1 4TB                        | 1         | 0.63%   |
| WDC WD35EFRX-68WT0N0 4TB                          | 1         | 0.63%   |
| WDC WD20EZBX-60AYRA0 2TB                          | 1         | 0.63%   |
| WDC WD20EARS-00J2GB0 2TB                          | 1         | 0.63%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 0.63%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.63%   |
| WDC WD10JPVX-00JC3T0 1TB                          | 1         | 0.63%   |
| WDC WD10EZEX-75M2NA0 1TB                          | 1         | 0.63%   |
| WDC WD10EZEX-00KUWA0 1TB                          | 1         | 0.63%   |
| WDC RAT035VWHG-GTK4D7 4TB                         | 1         | 0.63%   |
| WDC RAT035VQHR-GTK4D7 4TB                         | 1         | 0.63%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB              | 1         | 0.63%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 0.63%   |
| Unknown SD64G  64GB                               | 1         | 0.63%   |
| Unknown SD/MMC/MS PRO 16GB                        | 1         | 0.63%   |
| Unknown MMC Card  16GB                            | 1         | 0.63%   |
| Unknown EC2QT  64GB                               | 1         | 0.63%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB           | 1         | 0.63%   |
| Transcend TS256GMTE220S 256GB                     | 1         | 0.63%   |
| Toshiba MK6475GSX 640GB                           | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 26     | 39.53%  |
| WDC                 | 14        | 29     | 32.56%  |
| Toshiba             | 3         | 4      | 6.98%   |
| Hitachi             | 2         | 2      | 4.65%   |
| HGST                | 2         | 2      | 4.65%   |
| Unknown             | 1         | 2      | 2.33%   |
| Samsung Electronics | 1         | 1      | 2.33%   |
| QEMU                | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 8      | 2.33%   |
| DELLBOSS            | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 17.5%   |
| Kingston            | 5         | 5      | 12.5%   |
| Intel               | 4         | 5      | 10%     |
| SK hynix            | 3         | 3      | 7.5%    |
| Micron Technology   | 3         | 4      | 7.5%    |
| Crucial             | 3         | 10     | 7.5%    |
| SanDisk             | 2         | 2      | 5%      |
| Netac               | 2         | 2      | 5%      |
| LITEONIT            | 2         | 4      | 5%      |
| WDC                 | 1         | 3      | 2.5%    |
| Team                | 1         | 1      | 2.5%    |
| Plextor             | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| Hewlett-Packard     | 1         | 1      | 2.5%    |
| Dell                | 1         | 2      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| ASMT                | 1         | 2      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 43        | 113    | 35.25%  |
| HDD     | 38        | 76     | 31.15%  |
| SSD     | 37        | 56     | 30.33%  |
| MMC     | 3         | 4      | 2.46%   |
| Unknown | 1         | 2      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 60        | 125    | 54.05%  |
| NVMe | 43        | 113    | 38.74%  |
| SAS  | 5         | 9      | 4.5%    |
| MMC  | 3         | 4      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 46     | 46.25%  |
| 0.51-1.0   | 26        | 42     | 32.5%   |
| 1.01-2.0   | 7         | 12     | 8.75%   |
| 3.01-4.0   | 6         | 20     | 7.5%    |
| 4.01-10.0  | 3         | 11     | 3.75%   |
| 2.01-3.0   | 1         | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 27.78%  |
| 251-500        | 14        | 15.56%  |
| 501-1000       | 13        | 14.44%  |
| More than 3000 | 8         | 8.89%   |
| 51-100         | 7         | 7.78%   |
| Unknown        | 7         | 7.78%   |
| 1001-2000      | 6         | 6.67%   |
| 2001-3000      | 5         | 5.56%   |
| 1-20           | 3         | 3.33%   |
| 21-50          | 2         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 38.54%  |
| 21-50          | 18        | 18.75%  |
| 51-100         | 11        | 11.46%  |
| 101-250        | 10        | 10.42%  |
| Unknown        | 7         | 7.29%   |
| 251-500        | 5         | 5.21%   |
| 501-1000       | 3         | 3.13%   |
| More than 3000 | 2         | 2.08%   |
| 1001-2000      | 2         | 2.08%   |
| 2001-3000      | 1         | 1.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD4000FDYZ-27YA5B0 4TB        | 1         | 1      | 14.29%  |
| WDC WD20EARS-00J2GB0 2TB          | 1         | 1      | 14.29%  |
| SK hynix SH920 2.5 7MM 256GB SSD  | 1         | 1      | 14.29%  |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2      | 14.29%  |
| Samsung Electronics HD642JJ 640GB | 1         | 1      | 14.29%  |
| LITEONIT LSS-16L6G-HP 16GB SSD    | 1         | 3      | 14.29%  |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 28.57%  |
| SK hynix            | 1         | 1      | 14.29%  |
| Seagate             | 1         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| LITEONIT            | 1         | 3      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Seagate             | 1         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 71.43%  |
| SSD  | 2         | 4      | 28.57%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 51        | 149    | 51.52%  |
| Detected | 41        | 92     | 41.41%  |
| Malfunc  | 7         | 10     | 7.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 50        | 39.06%  |
| AMD                            | 24        | 18.75%  |
| Samsung Electronics            | 14        | 10.94%  |
| Kingston Technology Company    | 7         | 5.47%   |
| SanDisk                        | 6         | 4.69%   |
| LSI Logic / Symbios Logic      | 4         | 3.13%   |
| Union Memory (Shenzhen)        | 2         | 1.56%   |
| SK hynix                       | 2         | 1.56%   |
| Silicon Motion                 | 2         | 1.56%   |
| Marvell Technology Group       | 2         | 1.56%   |
| Broadcom / LSI                 | 2         | 1.56%   |
| ASMedia Technology             | 2         | 1.56%   |
| Toshiba America Info Systems   | 1         | 0.78%   |
| Solid State Storage Technology | 1         | 0.78%   |
| Seagate Technology             | 1         | 0.78%   |
| Red Hat                        | 1         | 0.78%   |
| Phison Electronics             | 1         | 0.78%   |
| Nextorage                      | 1         | 0.78%   |
| Netac Technology               | 1         | 0.78%   |
| Micron/Crucial Technology      | 1         | 0.78%   |
| Micron Technology              | 1         | 0.78%   |
| KIOXIA                         | 1         | 0.78%   |
| Hewlett-Packard                | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 13.19%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.47%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 3.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 2.78%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 4         | 2.78%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 2.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.08%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.39%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 1.39%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                               | 2         | 1.39%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 2         | 1.39%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.39%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 1.39%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2         | 1.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.39%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 0.69%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.69%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.69%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.69%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.69%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.69%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                             | 1         | 0.69%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 0.69%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.69%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.69%   |
| Red Hat Virtio 1.0 SCSI                                                        | 1         | 0.69%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.69%   |
| Nextorage NE1N NVMe SSD                                                        | 1         | 0.69%   |
| Netac PCIe 3 NVMe SSD (DRAM-less)                                              | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 60        | 47.24%  |
| NVMe | 42        | 33.07%  |
| RAID | 12        | 9.45%   |
| IDE  | 7         | 5.51%   |
| SAS  | 5         | 3.94%   |
| SCSI | 1         | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 56        | 63.64%  |
| AMD    | 29        | 32.95%  |
| ARM    | 3         | 3.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 3.37%   |
| ARM Processor                               | 3         | 3.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.25%   |
| AMD EPYC 7282 16-Core Processor             | 2         | 2.25%   |
| Intel Xeon W-2223 CPU @ 3.60GHz             | 1         | 1.12%   |
| Intel Xeon W-1350 @ 3.30GHz                 | 1         | 1.12%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 1.12%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz        | 1         | 1.12%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz         | 1         | 1.12%   |
| Intel Xeon E-2144G CPU @ 3.60GHz            | 1         | 1.12%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1         | 1.12%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 1.12%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1         | 1.12%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz          | 1         | 1.12%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 1.12%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.12%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.12%   |
| Intel Pentium CPU 3825U @ 1.90GHz           | 1         | 1.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.12%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.12%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.12%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.12%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.12%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.12%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.12%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.12%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 1.12%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.12%   |
| Intel Core i5-6260U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 1.12%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.12%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.12%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.12%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.12%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 18.18%  |
| Other                   | 13        | 14.77%  |
| Intel Xeon              | 9         | 10.23%  |
| Intel Core i7           | 8         | 9.09%   |
| Intel Core i3           | 6         | 6.82%   |
| AMD Ryzen 7             | 6         | 6.82%   |
| AMD Ryzen 5             | 5         | 5.68%   |
| AMD EPYC                | 5         | 5.68%   |
| AMD Ryzen 9             | 4         | 4.55%   |
| Intel Pentium           | 2         | 2.27%   |
| Intel Celeron           | 2         | 2.27%   |
| AMD Ryzen Threadripper  | 2         | 2.27%   |
| AMD A10                 | 2         | 2.27%   |
| Intel Xeon Silver       | 1         | 1.14%   |
| Intel Xeon Gold         | 1         | 1.14%   |
| Intel Pentium Dual-Core | 1         | 1.14%   |
| Intel Atom              | 1         | 1.14%   |
| AMD Ryzen 3             | 1         | 1.14%   |
| AMD FX                  | 1         | 1.14%   |
| AMD A6                  | 1         | 1.14%   |
| AMD A12                 | 1         | 1.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 27        | 30.34%  |
| 2       | 23        | 25.84%  |
| 6       | 10        | 11.24%  |
| 16      | 7         | 7.87%   |
| 8       | 7         | 7.87%   |
| 12      | 5         | 5.62%   |
| 32      | 2         | 2.25%   |
| 24      | 2         | 2.25%   |
| Unknown | 2         | 2.25%   |
| 80      | 1         | 1.12%   |
| 48      | 1         | 1.12%   |
| 10      | 1         | 1.12%   |
| 1       | 1         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 79        | 89.77%  |
| 2       | 6         | 6.82%   |
| Unknown | 2         | 2.27%   |
| 4       | 1         | 1.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 72        | 81.82%  |
| 1       | 14        | 15.91%  |
| Unknown | 2         | 2.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 96.59%  |
| Unknown        | 3         | 3.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 13.04%  |
| 0x306a9    | 5         | 5.43%   |
| 0x806ec    | 4         | 4.35%   |
| 0x806c1    | 4         | 4.35%   |
| 0xa0671    | 3         | 3.26%   |
| 0x40651    | 3         | 3.26%   |
| 0x306c3    | 3         | 3.26%   |
| 0x206a7    | 3         | 3.26%   |
| 0x08701021 | 3         | 3.26%   |
| 0x906ea    | 2         | 2.17%   |
| 0x806ea    | 2         | 2.17%   |
| 0x806d1    | 2         | 2.17%   |
| 0x50657    | 2         | 2.17%   |
| 0x406e3    | 2         | 2.17%   |
| 0x306e4    | 2         | 2.17%   |
| 0x08600106 | 2         | 2.17%   |
| 0x0830107a | 2         | 2.17%   |
| 0x08301055 | 2         | 2.17%   |
| 0x08108109 | 2         | 2.17%   |
| 0xb06a3    | 1         | 1.09%   |
| 0xa0655    | 1         | 1.09%   |
| 0xa0652    | 1         | 1.09%   |
| 0x906ed    | 1         | 1.09%   |
| 0x906e9    | 1         | 1.09%   |
| 0x90672    | 1         | 1.09%   |
| 0x806e9    | 1         | 1.09%   |
| 0x506e3    | 1         | 1.09%   |
| 0x50654    | 1         | 1.09%   |
| 0x406c4    | 1         | 1.09%   |
| 0x306d4    | 1         | 1.09%   |
| 0x30678    | 1         | 1.09%   |
| 0x206d7    | 1         | 1.09%   |
| 0x20655    | 1         | 1.09%   |
| 0x106ca    | 1         | 1.09%   |
| 0x106a5    | 1         | 1.09%   |
| 0x1067a    | 1         | 1.09%   |
| 0x0a601203 | 1         | 1.09%   |
| 0x0a50000d | 1         | 1.09%   |
| 0x0a50000c | 1         | 1.09%   |
| 0x0a20120a | 1         | 1.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 12        | 13.64%  |
| KabyLake         | 12        | 13.64%  |
| IvyBridge        | 7         | 7.95%   |
| Skylake          | 6         | 6.82%   |
| Haswell          | 6         | 6.82%   |
| SandyBridge      | 5         | 5.68%   |
| Icelake          | 5         | 5.68%   |
| Unknown          | 5         | 5.68%   |
| Zen 3            | 4         | 4.55%   |
| TigerLake        | 4         | 4.55%   |
| Excavator        | 4         | 4.55%   |
| Zen+             | 3         | 3.41%   |
| Zen              | 2         | 2.27%   |
| Silvermont       | 2         | 2.27%   |
| CometLake        | 2         | 2.27%   |
| Alderlake Hybrid | 2         | 2.27%   |
| Westmere         | 1         | 1.14%   |
| Steamroller      | 1         | 1.14%   |
| Piledriver       | 1         | 1.14%   |
| Penryn           | 1         | 1.14%   |
| Nehalem          | 1         | 1.14%   |
| Broadwell        | 1         | 1.14%   |
| Bonnell          | 1         | 1.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 40        | 41.24%  |
| Nvidia                     | 25        | 25.77%  |
| AMD                        | 21        | 21.65%  |
| ASPEED Technology          | 6         | 6.19%   |
| Matrox Electronics Systems | 4         | 4.12%   |
| Red Hat                    | 1         | 1.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                  | 6         | 6.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 4.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 3.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 3.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 3.06%   |
| Nvidia GA106 [Geforce RTX 3050]                                           | 2         | 2.04%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 2         | 2.04%   |
| Intel UHD Graphics 620                                                    | 2         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.04%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 2.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 2.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 2.04%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 2         | 2.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.04%   |
| Red Hat QXL paravirtual graphic card                                      | 1         | 1.02%   |
| Nvidia TU117GLM [Quadro T400 Mobile]                                      | 1         | 1.02%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 1.02%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.02%   |
| Nvidia GP107GL [Quadro P620]                                              | 1         | 1.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1         | 1.02%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1         | 1.02%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 1.02%   |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 1.02%   |
| Nvidia GM107GL [Quadro K2200]                                             | 1         | 1.02%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1         | 1.02%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 1.02%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.02%   |
| Nvidia GK104 [GeForce GTX 770]                                            | 1         | 1.02%   |
| Nvidia GF119 [GeForce GT 610]                                             | 1         | 1.02%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.02%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 1.02%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.02%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                        | 1         | 1.02%   |
| Nvidia GA102GL [RTX A6000]                                                | 1         | 1.02%   |
| Nvidia AD102 [GeForce RTX 4090]                                           | 1         | 1.02%   |
| Matrox Electronics Systems MGA G200eW WPCM450                             | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 35.23%  |
| 1 x Nvidia     | 17        | 19.32%  |
| 1 x AMD        | 17        | 19.32%  |
| Intel + Nvidia | 7         | 7.95%   |
| 1 x Matrox     | 4         | 4.55%   |
| 1 x ASPEED     | 4         | 4.55%   |
| Other          | 2         | 2.27%   |
| 2 x AMD        | 1         | 1.14%   |
| 1 x Red Hat    | 1         | 1.14%   |
| Intel + ASPEED | 1         | 1.14%   |
| Intel + AMD    | 1         | 1.14%   |
| AMD + Nvidia   | 1         | 1.14%   |
| AMD + ASPEED   | 1         | 1.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 67        | 76.14%  |
| Unknown     | 12        | 13.64%  |
| Proprietary | 9         | 10.23%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 57.3%   |
| 0.01-0.5   | 11        | 12.36%  |
| 1.01-2.0   | 8         | 8.99%   |
| 7.01-8.0   | 5         | 5.62%   |
| 5.01-6.0   | 5         | 5.62%   |
| 3.01-4.0   | 4         | 4.49%   |
| 0.51-1.0   | 3         | 3.37%   |
| 32.01-64.0 | 1         | 1.12%   |
| 16.01-24.0 | 1         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 14.67%  |
| Samsung Electronics     | 10        | 13.33%  |
| LG Display              | 8         | 10.67%  |
| BOE                     | 7         | 9.33%   |
| Dell                    | 5         | 6.67%   |
| Chimei Innolux          | 5         | 6.67%   |
| Eizo                    | 4         | 5.33%   |
| PANDA                   | 3         | 4%      |
| BenQ                    | 3         | 4%      |
| ViewSonic               | 2         | 2.67%   |
| Sharp                   | 2         | 2.67%   |
| Philips                 | 2         | 2.67%   |
| InfoVision              | 2         | 2.67%   |
| Goldstar                | 2         | 2.67%   |
| TopView                 | 1         | 1.33%   |
| STD                     | 1         | 1.33%   |
| Seiki                   | 1         | 1.33%   |
| Medion                  | 1         | 1.33%   |
| Lenovo                  | 1         | 1.33%   |
| Chi Mei Optoelectronics | 1         | 1.33%   |
| ASUSTek Computer        | 1         | 1.33%   |
| AOC                     | 1         | 1.33%   |
| Acer                    | 1         | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 2.56%   |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch            | 1         | 1.28%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch         | 1         | 1.28%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                   | 1         | 1.28%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                     | 1         | 1.28%   |
| Sharp LCD Monitor SHP146B 3200x1800 290x170mm 13.2-inch               | 1         | 1.28%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch               | 1         | 1.28%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                   | 1         | 1.28%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch  | 1         | 1.28%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1         | 1.28%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 1.28%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor S32B80P                               | 1         | 1.28%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 1.28%   |
| Philips PHL 272B7QU PHL0926 2560x1440 597x336mm 27.0-inch             | 1         | 1.28%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                     | 1         | 1.28%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch               | 1         | 1.28%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 1.28%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.28%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                 | 1         | 1.28%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch           | 1         | 1.28%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1         | 1.28%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch          | 1         | 1.28%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.28%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 1         | 1.28%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                 | 1         | 1.28%   |
| Eizo RX220 ENC2146 1600x1200 432x324mm 21.3-inch                      | 1         | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 51.32%  |
| 1366x768 (WXGA)    | 12        | 15.79%  |
| 1280x1024 (SXGA)   | 5         | 6.58%   |
| 3840x2160 (4K)     | 4         | 5.26%   |
| 2560x1440 (QHD)    | 3         | 3.95%   |
| 1920x1200 (WUXGA)  | 3         | 3.95%   |
| 1600x900 (HD+)     | 2         | 2.63%   |
| 5760x2160          | 1         | 1.32%   |
| 3200x1800 (QHD+)   | 1         | 1.32%   |
| 2560x1600          | 1         | 1.32%   |
| 2560x1080          | 1         | 1.32%   |
| 1680x1050 (WSXGA+) | 1         | 1.32%   |
| 1600x1200          | 1         | 1.32%   |
| 1400x1050          | 1         | 1.32%   |
| Unknown            | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 21.05%  |
| 14      | 9         | 11.84%  |
| 17      | 8         | 10.53%  |
| 13      | 8         | 10.53%  |
| 31      | 6         | 7.89%   |
| 21      | 6         | 7.89%   |
| 24      | 5         | 6.58%   |
| 27      | 4         | 5.26%   |
| 19      | 3         | 3.95%   |
| Unknown | 3         | 3.95%   |
| 11      | 2         | 2.63%   |
| 34      | 1         | 1.32%   |
| 23      | 1         | 1.32%   |
| 22      | 1         | 1.32%   |
| 20      | 1         | 1.32%   |
| 18      | 1         | 1.32%   |
| 16      | 1         | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 40.79%  |
| 351-400     | 11        | 14.47%  |
| 501-600     | 10        | 13.16%  |
| 401-500     | 8         | 10.53%  |
| 601-700     | 6         | 7.89%   |
| 201-300     | 6         | 7.89%   |
| Unknown     | 3         | 3.95%   |
| 701-800     | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 56        | 78.87%  |
| 5/4     | 4         | 5.63%   |
| 16/10   | 4         | 5.63%   |
| Unknown | 3         | 4.23%   |
| 4/3     | 2         | 2.82%   |
| 6/5     | 1         | 1.41%   |
| 21/9    | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 21.05%  |
| 81-90          | 13        | 17.11%  |
| 201-250        | 10        | 13.16%  |
| 351-500        | 7         | 9.21%   |
| 121-130        | 7         | 9.21%   |
| 151-200        | 6         | 7.89%   |
| 71-80          | 4         | 5.26%   |
| 301-350        | 4         | 5.26%   |
| Unknown        | 3         | 3.95%   |
| 51-60          | 2         | 2.63%   |
| 251-300        | 2         | 2.63%   |
| 141-150        | 1         | 1.32%   |
| 111-120        | 1         | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 36.99%  |
| 51-100        | 20        | 27.4%   |
| 101-120       | 16        | 21.92%  |
| More than 240 | 3         | 4.11%   |
| 161-240       | 3         | 4.11%   |
| Unknown       | 3         | 4.11%   |
| 1-50          | 1         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 58        | 65.91%  |
| 0     | 18        | 20.45%  |
| 2     | 12        | 13.64%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 39.53%  |
| Realtek Semiconductor           | 31        | 24.03%  |
| Qualcomm Atheros                | 13        | 10.08%  |
| Broadcom                        | 8         | 6.2%    |
| Broadcom Limited                | 5         | 3.88%   |
| TP-Link                         | 3         | 2.33%   |
| Mellanox Technologies           | 3         | 2.33%   |
| Standard Microsystems           | 2         | 1.55%   |
| Ralink Technology               | 2         | 1.55%   |
| Insyde Software                 | 2         | 1.55%   |
| American Megatrends             | 2         | 1.55%   |
| Sierra Wireless                 | 1         | 0.78%   |
| Samsung Electronics             | 1         | 0.78%   |
| Ralink                          | 1         | 0.78%   |
| Qualcomm Atheros Communications | 1         | 0.78%   |
| MediaTek                        | 1         | 0.78%   |
| Emulex                          | 1         | 0.78%   |
| ASIX Electronics                | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 21        | 12.96%  |
| Intel Wi-Fi 6 AX200                                                   | 5         | 3.09%   |
| Intel I350 Gigabit Network Connection                                 | 5         | 3.09%   |
| Intel I210 Gigabit Network Connection                                 | 4         | 2.47%   |
| Intel Ethernet Controller X550                                        | 4         | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 4         | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 3         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter            | 3         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter            | 3         | 1.85%   |
| Intel Wireless 8265 / 8275                                            | 3         | 1.85%   |
| Intel Wireless 7260                                                   | 3         | 1.85%   |
| Intel Wi-Fi 6 AX201                                                   | 3         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                     | 3         | 1.85%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 1.85%   |
| Standard Microsystems Ethernet controller                             | 2         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 2         | 1.23%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                   | 2         | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 1.23%   |
| Ralink MT7601U Wireless Adapter                                       | 2         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter            | 2         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                      | 2         | 1.23%   |
| Intel Wireless 8260                                                   | 2         | 1.23%   |
| Intel Wireless 3165                                                   | 2         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 2         | 1.23%   |
| Intel I211 Gigabit Network Connection                                 | 2         | 1.23%   |
| Intel Ethernet Controller I225-V                                      | 2         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                 | 2         | 1.23%   |
| Intel Ethernet Connection (14) I219-LM                                | 2         | 1.23%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 1.23%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 1.23%   |
| Intel 82574L Gigabit Network Connection                               | 2         | 1.23%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 1.23%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 2         | 1.23%   |
| American Megatrends Virtual Ethernet.                                 | 2         | 1.23%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 0.62%   |
| TP-Link Archer T4U ver.3                                              | 1         | 0.62%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                | 1         | 0.62%   |
| Sierra Wireless EM7345 4G LTE                                         | 1         | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 47.54%  |
| Qualcomm Atheros                | 11        | 18.03%  |
| Realtek Semiconductor           | 10        | 16.39%  |
| TP-Link                         | 2         | 3.28%   |
| Ralink Technology               | 2         | 3.28%   |
| Broadcom Limited                | 2         | 3.28%   |
| Broadcom                        | 2         | 3.28%   |
| Sierra Wireless                 | 1         | 1.64%   |
| Ralink                          | 1         | 1.64%   |
| Qualcomm Atheros Communications | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                         | 5         | 8.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 3         | 4.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 3         | 4.92%   |
| Intel Wireless 8265 / 8275                                  | 3         | 4.92%   |
| Intel Wireless 7260                                         | 3         | 4.92%   |
| Intel Wi-Fi 6 AX201                                         | 3         | 4.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 3         | 4.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 2         | 3.28%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter         | 2         | 3.28%   |
| Ralink MT7601U Wireless Adapter                             | 2         | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 2         | 3.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 2         | 3.28%   |
| Intel Wireless 8260                                         | 2         | 3.28%   |
| Intel Wireless 3165                                         | 2         | 3.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                      | 2         | 3.28%   |
| TP-Link Archer T4U ver.3                                    | 1         | 1.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                      | 1         | 1.64%   |
| Sierra Wireless EM7345 4G LTE                               | 1         | 1.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 1         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 1         | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter             | 1         | 1.64%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 1.64%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 1         | 1.64%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                   | 1         | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                             | 1         | 1.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter            | 1         | 1.64%   |
| Intel Wireless 7265                                         | 1         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                              | 1         | 1.64%   |
| Intel Centrino Wireless-N 2230                              | 1         | 1.64%   |
| Intel Centrino Ultimate-N 6300                              | 1         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                | 1         | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 1         | 1.64%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                     | 1         | 1.64%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter | 1         | 1.64%   |
| Broadcom BCM43225 802.11b/g/n                               | 1         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 1         | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 38.64%  |
| Realtek Semiconductor | 28        | 31.82%  |
| Broadcom              | 6         | 6.82%   |
| Qualcomm Atheros      | 3         | 3.41%   |
| Mellanox Technologies | 3         | 3.41%   |
| Broadcom Limited      | 3         | 3.41%   |
| Standard Microsystems | 2         | 2.27%   |
| Insyde Software       | 2         | 2.27%   |
| American Megatrends   | 2         | 2.27%   |
| TP-Link               | 1         | 1.14%   |
| Samsung Electronics   | 1         | 1.14%   |
| MediaTek              | 1         | 1.14%   |
| Emulex                | 1         | 1.14%   |
| ASIX Electronics      | 1         | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 21        | 20.79%  |
| Intel I350 Gigabit Network Connection                                 | 5         | 4.95%   |
| Intel I210 Gigabit Network Connection                                 | 4         | 3.96%   |
| Intel Ethernet Controller X550                                        | 4         | 3.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 4         | 3.96%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3         | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 3         | 2.97%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 2.97%   |
| Standard Microsystems Ethernet controller                             | 2         | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 1.98%   |
| Intel I211 Gigabit Network Connection                                 | 2         | 1.98%   |
| Intel Ethernet Controller I225-V                                      | 2         | 1.98%   |
| Intel Ethernet Connection (2) I219-LM                                 | 2         | 1.98%   |
| Intel Ethernet Connection (14) I219-LM                                | 2         | 1.98%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 1.98%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 1.98%   |
| Intel 82574L Gigabit Network Connection                               | 2         | 1.98%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 1.98%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 2         | 1.98%   |
| American Megatrends Virtual Ethernet.                                 | 2         | 1.98%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 0.99%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller             | 1         | 0.99%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                 | 1         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 0.99%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 0.99%   |
| Mellanox MT27800 Family [ConnectX-5]                                  | 1         | 0.99%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 0.99%   |
| MediaTek RMX3085                                                      | 1         | 0.99%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                         | 1         | 0.99%   |
| Intel Ethernet Connection I219-V                                      | 1         | 0.99%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 0.99%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 0.99%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 0.99%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 0.99%   |
| Intel Ethernet Connection (5) I219-V                                  | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 0.99%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 0.99%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 74        | 56.49%  |
| WiFi     | 57        | 43.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 52.94%  |
| WiFi     | 40        | 47.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 43        | 48.31%  |
| 1     | 28        | 31.46%  |
| 4     | 6         | 6.74%   |
| 3     | 4         | 4.49%   |
| 0     | 3         | 3.37%   |
| 6     | 2         | 2.25%   |
| 5     | 2         | 2.25%   |
| 8     | 1         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 66        | 73.33%  |
| Yes  | 24        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 52.94%  |
| Qualcomm Atheros Communications | 8         | 15.69%  |
| Realtek Semiconductor           | 7         | 13.73%  |
| Broadcom                        | 3         | 5.88%   |
| Foxconn / Hon Hai               | 2         | 3.92%   |
| Cambridge Silicon Radio         | 2         | 3.92%   |
| Lite-On Technology              | 1         | 1.96%   |
| ASUSTek Computer                | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 21.57%  |
| Intel AX201 Bluetooth                               | 7         | 13.73%  |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 11.76%  |
| Realtek Bluetooth Radio                             | 5         | 9.8%    |
| Intel AX200 Bluetooth                               | 5         | 9.8%    |
| Intel AX210 Bluetooth                               | 2         | 3.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.92%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.96%   |
| Lite-On Bluetooth Device                            | 1         | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.96%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.96%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.96%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 52        | 47.27%  |
| AMD                      | 26        | 23.64%  |
| Nvidia                   | 23        | 20.91%  |
| C-Media Electronics      | 2         | 1.82%   |
| Micro Star International | 1         | 0.91%   |
| JMTek                    | 1         | 0.91%   |
| Giga-Byte Technology     | 1         | 0.91%   |
| Conrad Electronic SE     | 1         | 0.91%   |
| Conexant Systems         | 1         | 0.91%   |
| ASUSTek Computer         | 1         | 0.91%   |
| Apple                    | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 7.58%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 5.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 3.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 3.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 3.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.27%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.27%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.52%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 1.52%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.52%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.52%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.52%   |
| AMD High Definition Audio Controller                                       | 2         | 1.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia Audio device                                                        | 1         | 0.76%   |
| Nvidia AD102 High Definition Audio Controller                              | 1         | 0.76%   |
| Micro Star International USB Audio                                         | 1         | 0.76%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.76%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 23.08%  |
| Kingston            | 11        | 16.92%  |
| SK hynix            | 9         | 13.85%  |
| Micron Technology   | 9         | 13.85%  |
| Crucial             | 6         | 9.23%   |
| G.Skill             | 4         | 6.15%   |
| Unknown             | 2         | 3.08%   |
| Elpida              | 2         | 3.08%   |
| Corsair             | 2         | 3.08%   |
| Unknown (0x0100)    | 1         | 1.54%   |
| Timetec             | 1         | 1.54%   |
| QEMU                | 1         | 1.54%   |
| Hewlett-Packard     | 1         | 1.54%   |
| Unknown             | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 2.74%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 2.74%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 1.37%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| Unknown (0x0100) RAM R744G2133S1S 4GB SODIMM DDR4 1866MT/s       | 1         | 1.37%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.37%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s            | 1         | 1.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 1.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 1.37%   |
| SK hynix RAM HMA82GR7AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 1.37%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.37%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.37%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.37%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.37%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.37%   |
| Samsung RAM M393A1K43DB1-CVF 8GB DIMM DDR4 2933MT/s              | 1         | 1.37%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s              | 1         | 1.37%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s             | 1         | 1.37%   |
| QEMU RAM Module 8GB DIMM RAM                                     | 1         | 1.37%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s              | 1         | 1.37%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.37%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Micron RAM 4ATF51264HZ-2G6E3 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.37%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s             | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 37        | 66.07%  |
| DDR3    | 13        | 23.21%  |
| LPDDR3  | 2         | 3.57%   |
| RAM     | 1         | 1.79%   |
| DDR5    | 1         | 1.79%   |
| DDR2    | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 28        | 50%     |
| SODIMM       | 25        | 44.64%  |
| Row Of Chips | 3         | 5.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 38.98%  |
| 4096  | 12        | 20.34%  |
| 16384 | 11        | 18.64%  |
| 32768 | 7         | 11.86%  |
| 2048  | 3         | 5.08%   |
| 65536 | 2         | 3.39%   |
| 49152 | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 20        | 31.25%  |
| 2667    | 11        | 17.19%  |
| 1600    | 10        | 15.63%  |
| 2400    | 4         | 6.25%   |
| 2133    | 4         | 6.25%   |
| 1866    | 3         | 4.69%   |
| 1333    | 3         | 4.69%   |
| 4800    | 1         | 1.56%   |
| 3733    | 1         | 1.56%   |
| 3466    | 1         | 1.56%   |
| 3066    | 1         | 1.56%   |
| 2933    | 1         | 1.56%   |
| 1867    | 1         | 1.56%   |
| 800     | 1         | 1.56%   |
| 667     | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 100%    |

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
| Chicony Electronics                    | 12        | 26.09%  |
| IMC Networks                           | 5         | 10.87%  |
| Realtek Semiconductor                  | 4         | 8.7%    |
| Microdia                               | 4         | 8.7%    |
| Bison Electronics                      | 4         | 8.7%    |
| Luxvisions Innotech Limited            | 3         | 6.52%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.52%   |
| Suyin                                  | 2         | 4.35%   |
| Microsoft                              | 2         | 4.35%   |
| Logitech                               | 2         | 4.35%   |
| Syntek                                 | 1         | 2.17%   |
| SunplusIT                              | 1         | 2.17%   |
| Sunplus Innovation Technology          | 1         | 2.17%   |
| Creative Technology                    | 1         | 2.17%   |
| Acer                                   | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 8.33%   |
| Chicony HP Truevision HD                                                 | 3         | 6.25%   |
| Realtek Integrated Webcam HD                                             | 2         | 4.17%   |
| Chicony Integrated HP HD Webcam                                          | 2         | 4.17%   |
| Syntek Integrated Camera                                                 | 1         | 2.08%   |
| Suyin HD WebCam                                                          | 1         | 2.08%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 1         | 2.08%   |
| SunplusIT HD Webcam                                                      | 1         | 2.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 2.08%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 2.08%   |
| Realtek EasyCamera                                                       | 1         | 2.08%   |
| Microsoft LifeCam VX-700                                                 | 1         | 2.08%   |
| Microsoft LifeCam HD-3000                                                | 1         | 2.08%   |
| Microdia USB 2.0 Camera                                                  | 1         | 2.08%   |
| Microdia Lenovo EasyCamera                                               | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                                            | 1         | 2.08%   |
| Microdia Integrated Webcam HD                                            | 1         | 2.08%   |
| Luxvisions Innotech Limited Integrated Camera                            | 1         | 2.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.08%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 1         | 2.08%   |
| Logitech Webcam C120                                                     | 1         | 2.08%   |
| Logitech Webcam B500                                                     | 1         | 2.08%   |
| Logitech QuickCam Vision Pro                                             | 1         | 2.08%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                     | 1         | 2.08%   |
| Creative Live! Cam Chat HD [VF0700]                                      | 1         | 2.08%   |
| Chicony USB2.0 Camera                                                    | 1         | 2.08%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 2.08%   |
| Chicony Lenovo EasyCamera                                                | 1         | 2.08%   |
| Chicony Integrated RGB Camera                                            | 1         | 2.08%   |
| Chicony HP TrueVision HD Camera                                          | 1         | 2.08%   |
| Chicony EasyCamera                                                       | 1         | 2.08%   |
| Chicony 8M Camera                                                        | 1         | 2.08%   |
| Chicony 720p HD Camera                                                   | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera          | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision FHD Camera         | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.08%   |
| Bison USB Camera                                                         | 1         | 2.08%   |
| Bison Lenovo EasyCamera                                                  | 1         | 2.08%   |
| Bison Integrated Camera                                                  | 1         | 2.08%   |
| Bison HD Webcam                                                          | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 70%     |
| Synaptics             | 2         | 20%     |
| Elan Microelectronics | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                           | 2         | 20%     |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 10%     |
| Validity Sensors Fingerprint scanner              | 1         | 10%     |
| Synaptics WBDI                                    | 1         | 10%     |
| Synaptics UWP WBDI Device                         | 1         | 10%     |
| Elan ELAN:ARM-M4                                  | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 2         | 40%     |
| SCM Microsystems | 1         | 20%     |
| OmniKey          | 1         | 20%     |
| Alcor Micro      | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 20%     |
| OmniKey CardMan 3021 / 3121                            | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 20%     |
| Broadcom 58200                                         | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                    | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 49        | 55.68%  |
| 1     | 30        | 34.09%  |
| 2     | 5         | 5.68%   |
| 3     | 2         | 2.27%   |
| 7     | 1         | 1.14%   |
| 5     | 1         | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 28.85%  |
| Fingerprint reader       | 10        | 19.23%  |
| Net/wireless             | 6         | 11.54%  |
| Multimedia controller    | 4         | 7.69%   |
| Net/ethernet             | 3         | 5.77%   |
| Unassigned class         | 2         | 3.85%   |
| Sound                    | 2         | 3.85%   |
| Communication controller | 2         | 3.85%   |
| Bluetooth                | 2         | 3.85%   |
| Storage/raid             | 1         | 1.92%   |
| Storage/ide              | 1         | 1.92%   |
| Storage                  | 1         | 1.92%   |
| Firewire controller      | 1         | 1.92%   |
| Chipcard                 | 1         | 1.92%   |
| Camera                   | 1         | 1.92%   |

