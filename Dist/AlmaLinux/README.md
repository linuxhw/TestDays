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

Total: 267

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.1 | 22        | 25.58%  |
| AlmaLinux 9.2 | 12        | 13.95%  |
| AlmaLinux 8.7 | 10        | 11.63%  |
| AlmaLinux 8.6 | 10        | 11.63%  |
| AlmaLinux 9.0 | 9         | 10.47%  |
| AlmaLinux 8.4 | 9         | 10.47%  |
| AlmaLinux 8.8 | 7         | 8.14%   |
| AlmaLinux 8.3 | 4         | 4.65%   |
| AlmaLinux 8.5 | 3         | 3.49%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 81        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64   | 9         | 9.38%   |
| 5.14.0-162.12.1.el9_1.x86_64  | 6         | 6.25%   |
| 4.18.0-425.3.1.el8.x86_64     | 6         | 6.25%   |
| 4.18.0-477.21.1.el8_8.x86_64  | 5         | 5.21%   |
| 4.18.0-477.13.1.el8_8.x86_64  | 4         | 4.17%   |
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 3.13%   |
| 5.14.0-284.30.1.el9_2.x86_64  | 3         | 3.13%   |
| 5.14.0-284.25.1.el9_2.x86_64  | 3         | 3.13%   |
| 5.14.0-284.11.1.el9_2.x86_64  | 3         | 3.13%   |
| 5.14.0-162.18.1.el9_1.x86_64  | 3         | 3.13%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 3.13%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 3.13%   |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 2.08%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 2.08%   |
| 5.14.0-284.18.1.el9_2.x86_64  | 2         | 2.08%   |
| 5.14.0-162.22.2.el9_1.x86_64  | 2         | 2.08%   |
| 4.18.0-477.27.1.el8_8.x86_64  | 2         | 2.08%   |
| 4.18.0-477.15.1.el8_8.x86_64  | 2         | 2.08%   |
| 4.18.0-477.10.1.el8_8.x86_64  | 2         | 2.08%   |
| 4.18.0-425.19.2.el8_7.x86_64  | 2         | 2.08%   |
| 4.18.0-425.13.1.el8_7.x86_64  | 2         | 2.08%   |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 2.08%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 2.08%   |
| 4.18.0-305.el8.x86_64         | 2         | 2.08%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 2.08%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 2.08%   |
| 6.4.0-1.el8.elrepo.x86_64     | 1         | 1.04%   |
| 6.3.0-2.el9.elrepo.x86_64     | 1         | 1.04%   |
| 6.1.24-1kx.el9.x86_64         | 1         | 1.04%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 1.04%   |
| 5.15.45-v8.1.el8              | 1         | 1.04%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 1         | 1.04%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 1.04%   |
| 5.14.0-162.23.1.el9_1.x86_64  | 1         | 1.04%   |
| 5.10.60-v8.1.el8              | 1         | 1.04%   |
| 4.18.0-425.10.1.el8_7.x86_64  | 1         | 1.04%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 1.04%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 1.04%   |
| 4.18.0-348.el8.x86_64         | 1         | 1.04%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 1         | 1.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 41        | 49.4%   |
| 4.18.0  | 36        | 43.37%  |
| 6.4.0   | 1         | 1.2%    |
| 6.3.0   | 1         | 1.2%    |
| 6.1.24  | 1         | 1.2%    |
| 5.4.175 | 1         | 1.2%    |
| 5.15.45 | 1         | 1.2%    |
| 5.10.60 | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 41        | 49.4%   |
| 4.18    | 36        | 43.37%  |
| 6.4     | 1         | 1.2%    |
| 6.3     | 1         | 1.2%    |
| 6.1     | 1         | 1.2%    |
| 5.4     | 1         | 1.2%    |
| 5.15    | 1         | 1.2%    |
| 5.10    | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 78        | 96.3%   |
| aarch64 | 3         | 3.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 47        | 58.02%  |
| Unknown         | 20        | 24.69%  |
| XFCE            | 5         | 6.17%   |
| KDE5            | 4         | 4.94%   |
| MATE            | 3         | 3.7%    |
| GNOME Flashback | 1         | 1.23%   |
| GNOME Classic   | 1         | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 38        | 46.34%  |
| X11     | 32        | 39.02%  |
| Unknown | 8         | 9.76%   |
| Tty     | 4         | 4.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 61.73%  |
| GDM     | 26        | 32.1%   |
| LightDM | 3         | 3.7%    |
| SDDM    | 2         | 2.47%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 42        | 50%     |
| en_GB   | 9         | 10.71%  |
| de_DE   | 7         | 8.33%   |
| fr_FR   | 4         | 4.76%   |
| en_CA   | 4         | 4.76%   |
| C       | 4         | 4.76%   |
| Unknown | 3         | 3.57%   |
| ru_RU   | 2         | 2.38%   |
| pl_PL   | 2         | 2.38%   |
| uk_UA   | 1         | 1.19%   |
| ru_UA   | 1         | 1.19%   |
| hu_HU   | 1         | 1.19%   |
| es_VE   | 1         | 1.19%   |
| es_ES   | 1         | 1.19%   |
| en_IN   | 1         | 1.19%   |
| da_DK   | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 55        | 66.27%  |
| BIOS | 28        | 33.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 62        | 76.54%  |
| Ext4    | 18        | 22.22%  |
| Overlay | 1         | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 44        | 54.32%  |
| Unknown | 29        | 35.8%   |
| MBR     | 8         | 9.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 85.19%  |
| Yes       | 12        | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 81.48%  |
| Yes       | 15        | 18.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 16        | 19.75%  |
| Hewlett-Packard         | 16        | 19.75%  |
| Dell                    | 11        | 13.58%  |
| ASUSTek Computer        | 7         | 8.64%   |
| Gigabyte Technology     | 5         | 6.17%   |
| Supermicro              | 3         | 3.7%    |
| MSI                     | 3         | 3.7%    |
| Intel                   | 3         | 3.7%    |
| ASRockRack              | 3         | 3.7%    |
| Raspberry Pi Foundation | 2         | 2.47%   |
| Google                  | 2         | 2.47%   |
| ASRock                  | 2         | 2.47%   |
| Acer                    | 2         | 2.47%   |
| TUXEDO                  | 1         | 1.23%   |
| Toshiba                 | 1         | 1.23%   |
| Timi                    | 1         | 1.23%   |
| Optimized Hosting       | 1         | 1.23%   |
| Maibenben               | 1         | 1.23%   |
| AZW                     | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 2.47%   |
| TUXEDO Aura 15 Gen1                  | 1         | 1.23%   |
| Toshiba Satellite L50-C              | 1         | 1.23%   |
| Timi RedmiBook 14-APCS               | 1         | 1.23%   |
| Supermicro Super Server              | 1         | 1.23%   |
| Supermicro PIO-617R-TLN4F+-ST031     | 1         | 1.23%   |
| Supermicro motherboard-H12 Series    | 1         | 1.23%   |
| Optimized Hosting KVM                | 1         | 1.23%   |
| MSI MS-7900                          | 1         | 1.23%   |
| MSI MS-7816                          | 1         | 1.23%   |
| MSI GL75 9SE                         | 1         | 1.23%   |
| Maibenben MaiBook X series           | 1         | 1.23%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.23%   |
| Lenovo V14-ARE 82DQ                  | 1         | 1.23%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 1.23%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 1.23%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 1.23%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS | 1         | 1.23%   |
| Lenovo ThinkPad E14 Gen 2 20TBS0CK00 | 1         | 1.23%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 1.23%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 1.23%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS    | 1         | 1.23%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 1.23%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 1.23%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.23%   |
| Lenovo H520S 10093                   | 1         | 1.23%   |
| Lenovo G580 20157                    | 1         | 1.23%   |
| Lenovo B50-30 20382                  | 1         | 1.23%   |
| Intel powered classmate PC           | 1         | 1.23%   |
| Intel NUC8i5BEH                      | 1         | 1.23%   |
| Intel NUC6i5SYB H81131-503           | 1         | 1.23%   |
| HP ZBook 17 G2                       | 1         | 1.23%   |
| HP Z820 Workstation                  | 1         | 1.23%   |
| HP Z620 Workstation                  | 1         | 1.23%   |
| HP Z600 Workstation                  | 1         | 1.23%   |
| HP Z2 Tower G4 Workstation           | 1         | 1.23%   |
| HP ProLiant DL360p Gen8              | 1         | 1.23%   |
| HP Notebook                          | 1         | 1.23%   |
| HP Laptop 17-cp0xxx                  | 1         | 1.23%   |
| HP Laptop 15-ef1xxx                  | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo ThinkPad                  | 4         | 4.94%   |
| Lenovo IdeaPad                   | 3         | 3.7%    |
| HP Laptop                        | 3         | 3.7%    |
| HP EliteBook                     | 3         | 3.7%    |
| Dell Latitude                    | 3         | 3.7%    |
| Dell Inspiron                    | 3         | 3.7%    |
| RPi Raspberry                    | 2         | 2.47%   |
| Lenovo Legion                    | 2         | 2.47%   |
| Dell PowerEdge                   | 2         | 2.47%   |
| TUXEDO Aura                      | 1         | 1.23%   |
| Toshiba Satellite                | 1         | 1.23%   |
| Timi RedmiBook                   | 1         | 1.23%   |
| Supermicro Super                 | 1         | 1.23%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1         | 1.23%   |
| Supermicro motherboard-H12       | 1         | 1.23%   |
| Optimized Hosting KVM            | 1         | 1.23%   |
| MSI MS-7900                      | 1         | 1.23%   |
| MSI MS-7816                      | 1         | 1.23%   |
| MSI GL75                         | 1         | 1.23%   |
| Maibenben MaiBook                | 1         | 1.23%   |
| Lenovo Yoga                      | 1         | 1.23%   |
| Lenovo V14-ARE                   | 1         | 1.23%   |
| Lenovo ThinkStation              | 1         | 1.23%   |
| Lenovo IdeaPadFlex               | 1         | 1.23%   |
| Lenovo H520S                     | 1         | 1.23%   |
| Lenovo G580                      | 1         | 1.23%   |
| Lenovo B50-30                    | 1         | 1.23%   |
| Intel powered                    | 1         | 1.23%   |
| Intel NUC8i5BEH                  | 1         | 1.23%   |
| Intel NUC6i5SYB                  | 1         | 1.23%   |
| HP ZBook                         | 1         | 1.23%   |
| HP Z820                          | 1         | 1.23%   |
| HP Z620                          | 1         | 1.23%   |
| HP Z600                          | 1         | 1.23%   |
| HP Z2                            | 1         | 1.23%   |
| HP ProLiant                      | 1         | 1.23%   |
| HP Notebook                      | 1         | 1.23%   |
| HP Falco                         | 1         | 1.23%   |
| HP ENVY                          | 1         | 1.23%   |
| HP 17-ak041ur                    | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 17        | 20.99%  |
| 2012    | 10        | 12.35%  |
| 2019    | 8         | 9.88%   |
| 2022    | 7         | 8.64%   |
| 2021    | 6         | 7.41%   |
| 2018    | 5         | 6.17%   |
| 2014    | 5         | 6.17%   |
| 2015    | 4         | 4.94%   |
| 2011    | 4         | 4.94%   |
| 2023    | 3         | 3.7%    |
| 2013    | 3         | 3.7%    |
| 2017    | 2         | 2.47%   |
| 2016    | 2         | 2.47%   |
| 2010    | 2         | 2.47%   |
| Unknown | 2         | 2.47%   |
| 2009    | 1         | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 41        | 50.62%  |
| Desktop        | 24        | 29.63%  |
| Server         | 9         | 11.11%  |
| Mini pc        | 3         | 3.7%    |
| System on chip | 2         | 2.47%   |
| Convertible    | 2         | 2.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 73        | 89.02%  |
| Enabled  | 9         | 10.98%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 96.3%   |
| Yes  | 3         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 21        | 25.61%  |
| 4.01-8.0        | 18        | 21.95%  |
| 64.01-256.0     | 12        | 14.63%  |
| 3.01-4.0        | 8         | 9.76%   |
| More than 256.0 | 6         | 7.32%   |
| 16.01-24.0      | 6         | 7.32%   |
| 32.01-64.0      | 4         | 4.88%   |
| 24.01-32.0      | 3         | 3.66%   |
| 1.01-2.0        | 2         | 2.44%   |
| 0.51-1.0        | 2         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 23        | 27.06%  |
| 1.01-2.0        | 16        | 18.82%  |
| 3.01-4.0        | 15        | 17.65%  |
| 4.01-8.0        | 11        | 12.94%  |
| 8.01-16.0       | 4         | 4.71%   |
| 32.01-64.0      | 3         | 3.53%   |
| 16.01-24.0      | 3         | 3.53%   |
| 0.51-1.0        | 3         | 3.53%   |
| 24.01-32.0      | 2         | 2.35%   |
| 64.01-256.0     | 2         | 2.35%   |
| 0.01-0.5        | 2         | 2.35%   |
| More than 256.0 | 1         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 46.34%  |
| 2      | 23        | 28.05%  |
| 3      | 7         | 8.54%   |
| 4      | 5         | 6.1%    |
| 6      | 3         | 3.66%   |
| 0      | 2         | 2.44%   |
| 12     | 1         | 1.22%   |
| 11     | 1         | 1.22%   |
| 10     | 1         | 1.22%   |
| 5      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 75.61%  |
| Yes       | 20        | 24.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 82.72%  |
| No        | 14        | 17.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 66.67%  |
| No        | 27        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 59.26%  |
| No        | 33        | 40.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 24.69%  |
| Germany      | 8         | 9.88%   |
| France       | 6         | 7.41%   |
| Russia       | 5         | 6.17%   |
| Canada       | 5         | 6.17%   |
| UK           | 4         | 4.94%   |
| Netherlands  | 3         | 3.7%    |
| Hungary      | 3         | 3.7%    |
| Ukraine      | 2         | 2.47%   |
| Spain        | 2         | 2.47%   |
| South Africa | 2         | 2.47%   |
| Romania      | 2         | 2.47%   |
| Poland       | 2         | 2.47%   |
| Indonesia    | 2         | 2.47%   |
| India        | 2         | 2.47%   |
| China        | 2         | 2.47%   |
| Venezuela    | 1         | 1.23%   |
| Switzerland  | 1         | 1.23%   |
| Sweden       | 1         | 1.23%   |
| Puerto Rico  | 1         | 1.23%   |
| Pakistan     | 1         | 1.23%   |
| Mexico       | 1         | 1.23%   |
| Kazakhstan   | 1         | 1.23%   |
| Greenland    | 1         | 1.23%   |
| Finland      | 1         | 1.23%   |
| Bulgaria     | 1         | 1.23%   |
| Austria      | 1         | 1.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Hamburg          | 3         | 3.61%   |
| Tunari           | 2         | 2.41%   |
| Saint-Brieuc     | 2         | 2.41%   |
| Queens           | 2         | 2.41%   |
| Johannesburg     | 2         | 2.41%   |
| Dallas           | 2         | 2.41%   |
| Zaporizhzhia     | 1         | 1.2%    |
| Zandvoort        | 1         | 1.2%    |
| Winterswijk      | 1         | 1.2%    |
| Wilmington       | 1         | 1.2%    |
| Wejherowo        | 1         | 1.2%    |
| Warsaw           | 1         | 1.2%    |
| Vienna           | 1         | 1.2%    |
| Varosfoeld       | 1         | 1.2%    |
| Uppsala          | 1         | 1.2%    |
| Tuusula          | 1         | 1.2%    |
| Tampa            | 1         | 1.2%    |
| Suzhou           | 1         | 1.2%    |
| Strasbourg       | 1         | 1.2%    |
| Stadtilm         | 1         | 1.2%    |
| St. Paul         | 1         | 1.2%    |
| South Tangerang  | 1         | 1.2%    |
| Sofia            | 1         | 1.2%    |
| Shimanovsk       | 1         | 1.2%    |
| Shanghai         | 1         | 1.2%    |
| San Diego        | 1         | 1.2%    |
| Rothwell         | 1         | 1.2%    |
| Regina           | 1         | 1.2%    |
| Redlands         | 1         | 1.2%    |
| Penza            | 1         | 1.2%    |
| Parla            | 1         | 1.2%    |
| Paris            | 1         | 1.2%    |
| Nizhniy Novgorod | 1         | 1.2%    |
| Moscow           | 1         | 1.2%    |
| Miami            | 1         | 1.2%    |
| Mangalore        | 1         | 1.2%    |
| Los Angeles      | 1         | 1.2%    |
| London           | 1         | 1.2%    |
| Liverpool        | 1         | 1.2%    |
| Lille            | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 19        | 25     | 15.7%   |
| Seagate                     | 17        | 29     | 14.05%  |
| WDC                         | 16        | 33     | 13.22%  |
| SK hynix                    | 6         | 6      | 4.96%   |
| Kingston                    | 6         | 8      | 4.96%   |
| Kingston Technology Company | 5         | 25     | 4.13%   |
| Intel                       | 5         | 6      | 4.13%   |
| Unknown                     | 4         | 6      | 3.31%   |
| Micron Technology           | 4         | 5      | 3.31%   |
| Crucial                     | 4         | 12     | 3.31%   |
| Toshiba                     | 3         | 4      | 2.48%   |
| SanDisk                     | 3         | 3      | 2.48%   |
| Netac                       | 3         | 3      | 2.48%   |
| LITEONIT                    | 2         | 4      | 1.65%   |
| Hitachi                     | 2         | 2      | 1.65%   |
| Hewlett-Packard             | 2         | 9      | 1.65%   |
| Dell                        | 2         | 3      | 1.65%   |
| Union Memory                | 1         | 1      | 0.83%   |
| Transcend                   | 1         | 1      | 0.83%   |
| Team                        | 1         | 1      | 0.83%   |
| SSSTC                       | 1         | 1      | 0.83%   |
| Silicon Motion              | 1         | 14     | 0.83%   |
| QEMU                        | 1         | 1      | 0.83%   |
| Plextor                     | 1         | 1      | 0.83%   |
| Phison                      | 1         | 1      | 0.83%   |
| LITEON                      | 1         | 1      | 0.83%   |
| KIOXIA                      | 1         | 1      | 0.83%   |
| HGST                        | 1         | 1      | 0.83%   |
| Emtec                       | 1         | 2      | 0.83%   |
| DELLBOSS                    | 1         | 1      | 0.83%   |
| China                       | 1         | 1      | 0.83%   |
| ASMT                        | 1         | 2      | 0.83%   |
| AMD                         | 1         | 5      | 0.83%   |
| A-DATA Technology           | 1         | 1      | 0.83%   |
| Unknown                     | 1         | 8      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                              | 2         | 1.37%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 1.37%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 1.37%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                      | 2         | 1.37%   |
| Kingston Company KC2000 NVMe SSD 1TB                | 2         | 1.37%   |
| Kingston Company A2000 NVMe SSD 1TB                 | 2         | 1.37%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 1.37%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 1.37%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.68%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 0.68%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 0.68%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1         | 0.68%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1         | 0.68%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1         | 0.68%   |
| WDC WD4000FYYZ-01UL1B2 4TB                          | 1         | 0.68%   |
| WDC WD4000FYYZ-01UL1B1 4TB                          | 1         | 0.68%   |
| WDC WD4000FDYZ-27YA5B0 4TB                          | 1         | 0.68%   |
| WDC WD4000F9YZ-09N20L1 4TB                          | 1         | 0.68%   |
| WDC WD3600FYYZ-01UL1B3 4TB                          | 1         | 0.68%   |
| WDC WD3600FYYZ-01UL1B1 4TB                          | 1         | 0.68%   |
| WDC WD35EFRX-68WT0N0 4TB                            | 1         | 0.68%   |
| WDC WD20EARS-00J2GB0 2TB                            | 1         | 0.68%   |
| WDC WD10SPZX-60Z10T1 1TB                            | 1         | 0.68%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.68%   |
| WDC WD10JPVX-00JC3T0 1TB                            | 1         | 0.68%   |
| WDC WD10EZEX-75M2NA0 1TB                            | 1         | 0.68%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1         | 0.68%   |
| WDC RAT035VWHG-GTK4D7 4TB                           | 1         | 0.68%   |
| WDC RAT035VQHR-GTK4D7 4TB                           | 1         | 0.68%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB                | 1         | 0.68%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.68%   |
| Unknown SD64G  64GB                                 | 1         | 0.68%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 0.68%   |
| Unknown MMC Card  16GB                              | 1         | 0.68%   |
| Unknown EC2QT  64GB                                 | 1         | 0.68%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB             | 1         | 0.68%   |
| Transcend TS256GMTE220S 256GB                       | 1         | 0.68%   |
| Toshiba MK6475GSX 640GB                             | 1         | 0.68%   |
| Toshiba MG06ACA800E 8TB                             | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 25     | 40%     |
| WDC                 | 13        | 28     | 32.5%   |
| Toshiba             | 3         | 4      | 7.5%    |
| Hitachi             | 2         | 2      | 5%      |
| Unknown             | 1         | 2      | 2.5%    |
| Samsung Electronics | 1         | 1      | 2.5%    |
| QEMU                | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| Hewlett-Packard     | 1         | 8      | 2.5%    |
| DELLBOSS            | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 15.79%  |
| Kingston            | 5         | 5      | 13.16%  |
| Intel               | 4         | 5      | 10.53%  |
| SK hynix            | 3         | 3      | 7.89%   |
| Micron Technology   | 3         | 4      | 7.89%   |
| Crucial             | 3         | 10     | 7.89%   |
| Netac               | 2         | 2      | 5.26%   |
| LITEONIT            | 2         | 4      | 5.26%   |
| WDC                 | 1         | 3      | 2.63%   |
| Team                | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| LITEON              | 1         | 1      | 2.63%   |
| Hewlett-Packard     | 1         | 1      | 2.63%   |
| Dell                | 1         | 2      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| ASMT                | 1         | 2      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 38        | 95     | 33.63%  |
| HDD     | 36        | 73     | 31.86%  |
| SSD     | 35        | 53     | 30.97%  |
| MMC     | 3         | 4      | 2.65%   |
| Unknown | 1         | 2      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 119    | 54.9%   |
| NVMe | 38        | 95     | 37.25%  |
| SAS  | 5         | 9      | 4.9%    |
| MMC  | 3         | 4      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 43     | 45.33%  |
| 0.51-1.0   | 24        | 39     | 32%     |
| 3.01-4.0   | 7         | 21     | 9.33%   |
| 1.01-2.0   | 6         | 11     | 8%      |
| 4.01-10.0  | 3         | 11     | 4%      |
| 2.01-3.0   | 1         | 1      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 30.12%  |
| 251-500        | 14        | 16.87%  |
| 501-1000       | 11        | 13.25%  |
| More than 3000 | 7         | 8.43%   |
| Unknown        | 7         | 8.43%   |
| 51-100         | 6         | 7.23%   |
| 1001-2000      | 5         | 6.02%   |
| 2001-3000      | 3         | 3.61%   |
| 1-20           | 3         | 3.61%   |
| 21-50          | 2         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 42.05%  |
| 21-50          | 15        | 17.05%  |
| 101-250        | 10        | 11.36%  |
| 51-100         | 9         | 10.23%  |
| Unknown        | 7         | 7.95%   |
| 251-500        | 4         | 4.55%   |
| More than 3000 | 2         | 2.27%   |
| 501-1000       | 2         | 2.27%   |
| 2001-3000      | 1         | 1.14%   |
| 1001-2000      | 1         | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD4000FDYZ-27YA5B0 4TB        | 1         | 1      | 16.67%  |
| WDC WD20EARS-00J2GB0 2TB          | 1         | 1      | 16.67%  |
| SK hynix SH920 2.5 7MM 256GB SSD  | 1         | 1      | 16.67%  |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2      | 16.67%  |
| Samsung Electronics HD642JJ 640GB | 1         | 1      | 16.67%  |
| LITEONIT LSS-16L6G-HP 16GB SSD    | 1         | 3      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 33.33%  |
| SK hynix            | 1         | 1      | 16.67%  |
| Seagate             | 1         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| LITEONIT            | 1         | 3      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 50%     |
| Seagate             | 1         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 66.67%  |
| SSD  | 2         | 4      | 33.33%  |

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
| Works    | 46        | 140    | 50.55%  |
| Detected | 39        | 78     | 42.86%  |
| Malfunc  | 6         | 9      | 6.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 46        | 39.32%  |
| AMD                            | 22        | 18.8%   |
| Samsung Electronics            | 13        | 11.11%  |
| Kingston Technology Company    | 7         | 5.98%   |
| LSI Logic / Symbios Logic      | 4         | 3.42%   |
| SanDisk                        | 3         | 2.56%   |
| Union Memory (Shenzhen)        | 2         | 1.71%   |
| SK hynix                       | 2         | 1.71%   |
| Silicon Motion                 | 2         | 1.71%   |
| Marvell Technology Group       | 2         | 1.71%   |
| Broadcom / LSI                 | 2         | 1.71%   |
| ASMedia Technology             | 2         | 1.71%   |
| Toshiba America Info Systems   | 1         | 0.85%   |
| Solid State Storage Technology | 1         | 0.85%   |
| Seagate Technology             | 1         | 0.85%   |
| Red Hat                        | 1         | 0.85%   |
| Phison Electronics             | 1         | 0.85%   |
| Nextorage                      | 1         | 0.85%   |
| Netac Technology               | 1         | 0.85%   |
| Micron/Crucial Technology      | 1         | 0.85%   |
| Micron Technology              | 1         | 0.85%   |
| Hewlett-Packard                | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 13.64%  |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 3.03%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 2.27%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 3         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.52%   |
| Kingston Company KC2000/KC2500 NVMe SSD                                        | 2         | 1.52%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.52%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.52%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 1.52%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.52%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 1         | 0.76%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.76%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.76%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.76%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.76%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.76%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.76%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.76%   |
| Red Hat Virtio 1.0 SCSI                                                        | 1         | 0.76%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.76%   |
| Nextorage NE1N NVMe SSD                                                        | 1         | 0.76%   |
| Netac Non-Volatile memory controller                                           | 1         | 0.76%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.76%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1         | 0.76%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 56        | 47.86%  |
| NVMe | 37        | 31.62%  |
| RAID | 11        | 9.4%    |
| IDE  | 7         | 5.98%   |
| SAS  | 5         | 4.27%   |
| SCSI | 1         | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 62.96%  |
| AMD    | 27        | 33.33%  |
| ARM    | 3         | 3.7%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 3.66%   |
| ARM Processor                               | 3         | 3.66%   |
| AMD EPYC 7282 16-Core Processor             | 2         | 2.44%   |
| Intel Xeon W-1350 @ 3.30GHz                 | 1         | 1.22%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 1.22%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz        | 1         | 1.22%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz         | 1         | 1.22%   |
| Intel Xeon E-2144G CPU @ 3.60GHz            | 1         | 1.22%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1         | 1.22%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 1.22%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1         | 1.22%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz          | 1         | 1.22%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 1.22%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.22%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.22%   |
| Intel Pentium CPU 3825U @ 1.90GHz           | 1         | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.22%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.22%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.22%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.22%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.22%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.22%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.22%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 1.22%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.22%   |
| Intel Core i5-6260U CPU @ 1.80GHz           | 1         | 1.22%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 1.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.22%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.22%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.22%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.22%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.22%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 1.22%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.22%   |
| Intel Core i3-2370M CPU @ 2.40GHz           | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 19.75%  |
| Other                   | 10        | 12.35%  |
| Intel Xeon              | 8         | 9.88%   |
| Intel Core i7           | 7         | 8.64%   |
| Intel Core i3           | 6         | 7.41%   |
| AMD Ryzen 7             | 6         | 7.41%   |
| AMD Ryzen 5             | 5         | 6.17%   |
| AMD EPYC                | 5         | 6.17%   |
| AMD Ryzen 9             | 3         | 3.7%    |
| Intel Pentium           | 2         | 2.47%   |
| Intel Celeron           | 2         | 2.47%   |
| AMD A10                 | 2         | 2.47%   |
| Intel Xeon Silver       | 1         | 1.23%   |
| Intel Xeon Gold         | 1         | 1.23%   |
| Intel Pentium Dual-Core | 1         | 1.23%   |
| Intel Atom              | 1         | 1.23%   |
| AMD Ryzen Threadripper  | 1         | 1.23%   |
| AMD Ryzen 3             | 1         | 1.23%   |
| AMD FX                  | 1         | 1.23%   |
| AMD A6                  | 1         | 1.23%   |
| AMD A12                 | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 24        | 29.27%  |
| 2       | 23        | 28.05%  |
| 6       | 10        | 12.2%   |
| 16      | 6         | 7.32%   |
| 8       | 5         | 6.1%    |
| 12      | 4         | 4.88%   |
| 32      | 2         | 2.44%   |
| 24      | 2         | 2.44%   |
| Unknown | 2         | 2.44%   |
| 80      | 1         | 1.22%   |
| 48      | 1         | 1.22%   |
| 10      | 1         | 1.22%   |
| 1       | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 72        | 88.89%  |
| 2       | 6         | 7.41%   |
| Unknown | 2         | 2.47%   |
| 4       | 1         | 1.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 66        | 81.48%  |
| 1       | 13        | 16.05%  |
| Unknown | 2         | 2.47%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 96.3%   |
| Unknown        | 3         | 3.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 14.12%  |
| 0x806ec    | 4         | 4.71%   |
| 0x306a9    | 4         | 4.71%   |
| 0x806c1    | 3         | 3.53%   |
| 0x40651    | 3         | 3.53%   |
| 0x306c3    | 3         | 3.53%   |
| 0x206a7    | 3         | 3.53%   |
| 0x08701021 | 3         | 3.53%   |
| 0xa0671    | 2         | 2.35%   |
| 0x906ea    | 2         | 2.35%   |
| 0x806ea    | 2         | 2.35%   |
| 0x406e3    | 2         | 2.35%   |
| 0x306e4    | 2         | 2.35%   |
| 0x08600106 | 2         | 2.35%   |
| 0x0830107a | 2         | 2.35%   |
| 0x08301055 | 2         | 2.35%   |
| 0x08108109 | 2         | 2.35%   |
| 0xb06a3    | 1         | 1.18%   |
| 0xa0655    | 1         | 1.18%   |
| 0xa0652    | 1         | 1.18%   |
| 0x906ed    | 1         | 1.18%   |
| 0x906e9    | 1         | 1.18%   |
| 0x90672    | 1         | 1.18%   |
| 0x806e9    | 1         | 1.18%   |
| 0x806d1    | 1         | 1.18%   |
| 0x506e3    | 1         | 1.18%   |
| 0x50657    | 1         | 1.18%   |
| 0x50654    | 1         | 1.18%   |
| 0x406c4    | 1         | 1.18%   |
| 0x306d4    | 1         | 1.18%   |
| 0x30678    | 1         | 1.18%   |
| 0x206d7    | 1         | 1.18%   |
| 0x20655    | 1         | 1.18%   |
| 0x106ca    | 1         | 1.18%   |
| 0x106a5    | 1         | 1.18%   |
| 0x1067a    | 1         | 1.18%   |
| 0x0a601203 | 1         | 1.18%   |
| 0x0a50000d | 1         | 1.18%   |
| 0x0a50000c | 1         | 1.18%   |
| 0x0a20120a | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 12        | 14.81%  |
| KabyLake         | 12        | 14.81%  |
| IvyBridge        | 6         | 7.41%   |
| Haswell          | 6         | 7.41%   |
| Skylake          | 5         | 6.17%   |
| SandyBridge      | 5         | 6.17%   |
| Unknown          | 5         | 6.17%   |
| Excavator        | 4         | 4.94%   |
| Zen+             | 3         | 3.7%    |
| Zen 3            | 3         | 3.7%    |
| TigerLake        | 3         | 3.7%    |
| Icelake          | 3         | 3.7%    |
| Silvermont       | 2         | 2.47%   |
| CometLake        | 2         | 2.47%   |
| Alderlake Hybrid | 2         | 2.47%   |
| Zen              | 1         | 1.23%   |
| Westmere         | 1         | 1.23%   |
| Steamroller      | 1         | 1.23%   |
| Piledriver       | 1         | 1.23%   |
| Penryn           | 1         | 1.23%   |
| Nehalem          | 1         | 1.23%   |
| Broadwell        | 1         | 1.23%   |
| Bonnell          | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 38        | 42.22%  |
| Nvidia                     | 21        | 23.33%  |
| AMD                        | 20        | 22.22%  |
| ASPEED Technology          | 6         | 6.67%   |
| Matrox Electronics Systems | 4         | 4.44%   |
| Red Hat                    | 1         | 1.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                  | 6         | 6.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 3.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 3.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 3.3%    |
| Nvidia GA106 [Geforce RTX 3050]                                           | 2         | 2.2%    |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 2         | 2.2%    |
| Intel UHD Graphics 620                                                    | 2         | 2.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.2%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 2.2%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 2.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 2.2%    |
| AMD Renoir                                                                | 2         | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.2%    |
| Red Hat QXL paravirtual graphic card                                      | 1         | 1.1%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 1.1%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.1%    |
| Nvidia GP107GL [Quadro P620]                                              | 1         | 1.1%    |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1         | 1.1%    |
| Nvidia GM204GL [Quadro M4000]                                             | 1         | 1.1%    |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 1.1%    |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 1.1%    |
| Nvidia GM107GL [Quadro K2200]                                             | 1         | 1.1%    |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 1.1%    |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.1%    |
| Nvidia GK104 [GeForce GTX 770]                                            | 1         | 1.1%    |
| Nvidia GF119 [GeForce GT 610]                                             | 1         | 1.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.1%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 1.1%    |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.1%    |
| Nvidia GA102GL [RTX A6000]                                                | 1         | 1.1%    |
| Nvidia AD102 [GeForce RTX 4090]                                           | 1         | 1.1%    |
| Matrox Electronics Systems MGA G200eW WPCM450                             | 1         | 1.1%    |
| Matrox Electronics Systems MGA G200EH                                     | 1         | 1.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.1%    |
| Intel Tiger Lake-H GT1 [UHD Graphics]                                     | 1         | 1.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 35.8%   |
| 1 x AMD        | 16        | 19.75%  |
| 1 x Nvidia     | 13        | 16.05%  |
| Intel + Nvidia | 7         | 8.64%   |
| 1 x Matrox     | 4         | 4.94%   |
| 1 x ASPEED     | 4         | 4.94%   |
| Other          | 2         | 2.47%   |
| 2 x AMD        | 1         | 1.23%   |
| 1 x Red Hat    | 1         | 1.23%   |
| Intel + ASPEED | 1         | 1.23%   |
| Intel + AMD    | 1         | 1.23%   |
| AMD + Nvidia   | 1         | 1.23%   |
| AMD + ASPEED   | 1         | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 62        | 76.54%  |
| Unknown     | 12        | 14.81%  |
| Proprietary | 7         | 8.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 58.02%  |
| 0.01-0.5   | 11        | 13.58%  |
| 1.01-2.0   | 7         | 8.64%   |
| 7.01-8.0   | 4         | 4.94%   |
| 3.01-4.0   | 4         | 4.94%   |
| 5.01-6.0   | 3         | 3.7%    |
| 0.51-1.0   | 3         | 3.7%    |
| 32.01-64.0 | 1         | 1.23%   |
| 16.01-24.0 | 1         | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 16.18%  |
| Samsung Electronics     | 10        | 14.71%  |
| LG Display              | 7         | 10.29%  |
| BOE                     | 6         | 8.82%   |
| Chimei Innolux          | 5         | 7.35%   |
| PANDA                   | 3         | 4.41%   |
| Eizo                    | 3         | 4.41%   |
| Dell                    | 3         | 4.41%   |
| BenQ                    | 3         | 4.41%   |
| ViewSonic               | 2         | 2.94%   |
| Sharp                   | 2         | 2.94%   |
| InfoVision              | 2         | 2.94%   |
| Goldstar                | 2         | 2.94%   |
| TopView                 | 1         | 1.47%   |
| STD                     | 1         | 1.47%   |
| Seiki                   | 1         | 1.47%   |
| Philips                 | 1         | 1.47%   |
| Medion                  | 1         | 1.47%   |
| Lenovo                  | 1         | 1.47%   |
| Chi Mei Optoelectronics | 1         | 1.47%   |
| AOC                     | 1         | 1.47%   |
| Acer                    | 1         | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 2.9%    |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch            | 1         | 1.45%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch         | 1         | 1.45%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                   | 1         | 1.45%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                     | 1         | 1.45%   |
| Sharp LCD Monitor SHP146B 3200x1800 290x170mm 13.2-inch               | 1         | 1.45%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch               | 1         | 1.45%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                   | 1         | 1.45%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch  | 1         | 1.45%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1         | 1.45%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 1.45%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                     | 1         | 1.45%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 1.45%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                     | 1         | 1.45%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch               | 1         | 1.45%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 1.45%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.45%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                 | 1         | 1.45%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.45%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 1.45%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch          | 1         | 1.45%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 1.45%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch           | 1         | 1.45%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.45%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch           | 1         | 1.45%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1         | 1.45%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch          | 1         | 1.45%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.45%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                 | 1         | 1.45%   |
| Eizo LCD Monitor CG247 5760x2160                                      | 1         | 1.45%   |
| Eizo LCD Monitor CG247 1920x1200                                      | 1         | 1.45%   |
| Eizo EV2336W ENC2390 1920x1080 510x287mm 23.0-inch                    | 1         | 1.45%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                      | 1         | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 53.73%  |
| 1366x768 (WXGA)    | 12        | 17.91%  |
| 1280x1024 (SXGA)   | 5         | 7.46%   |
| 3840x2160 (4K)     | 2         | 2.99%   |
| 2560x1440 (QHD)    | 2         | 2.99%   |
| 1920x1200 (WUXGA)  | 2         | 2.99%   |
| 1600x900 (HD+)     | 2         | 2.99%   |
| 5760x2160          | 1         | 1.49%   |
| 3200x1800 (QHD+)   | 1         | 1.49%   |
| 2560x1600          | 1         | 1.49%   |
| 2560x1080          | 1         | 1.49%   |
| 1680x1050 (WSXGA+) | 1         | 1.49%   |
| 1400x1050          | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 23.53%  |
| 14      | 9         | 13.24%  |
| 13      | 8         | 11.76%  |
| 17      | 6         | 8.82%   |
| 21      | 5         | 7.35%   |
| 31      | 4         | 5.88%   |
| 24      | 4         | 5.88%   |
| 19      | 3         | 4.41%   |
| Unknown | 3         | 4.41%   |
| 27      | 2         | 2.94%   |
| 11      | 2         | 2.94%   |
| 34      | 1         | 1.47%   |
| 23      | 1         | 1.47%   |
| 22      | 1         | 1.47%   |
| 20      | 1         | 1.47%   |
| 18      | 1         | 1.47%   |
| 16      | 1         | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 45.59%  |
| 351-400     | 9         | 13.24%  |
| 501-600     | 7         | 10.29%  |
| 401-500     | 7         | 10.29%  |
| 201-300     | 6         | 8.82%   |
| 601-700     | 4         | 5.88%   |
| Unknown     | 3         | 4.41%   |
| 701-800     | 1         | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 51        | 79.69%  |
| 5/4     | 4         | 6.25%   |
| 16/10   | 3         | 4.69%   |
| Unknown | 3         | 4.69%   |
| 6/5     | 1         | 1.56%   |
| 4/3     | 1         | 1.56%   |
| 21/9    | 1         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 23.53%  |
| 81-90          | 13        | 19.12%  |
| 201-250        | 8         | 11.76%  |
| 151-200        | 7         | 10.29%  |
| 351-500        | 5         | 7.35%   |
| 121-130        | 5         | 7.35%   |
| 71-80          | 4         | 5.88%   |
| Unknown        | 3         | 4.41%   |
| 51-60          | 2         | 2.94%   |
| 301-350        | 2         | 2.94%   |
| 251-300        | 1         | 1.47%   |
| 141-150        | 1         | 1.47%   |
| 111-120        | 1         | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 36.36%  |
| 51-100        | 17        | 25.76%  |
| 101-120       | 15        | 22.73%  |
| More than 240 | 3         | 4.55%   |
| 161-240       | 3         | 4.55%   |
| Unknown       | 3         | 4.55%   |
| 1-50          | 1         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 53        | 65.43%  |
| 0     | 18        | 22.22%  |
| 2     | 10        | 12.35%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 36.67%  |
| Realtek Semiconductor           | 29        | 24.17%  |
| Qualcomm Atheros                | 13        | 10.83%  |
| Broadcom                        | 8         | 6.67%   |
| Broadcom Limited                | 5         | 4.17%   |
| TP-Link                         | 3         | 2.5%    |
| Mellanox Technologies           | 3         | 2.5%    |
| Standard Microsystems           | 2         | 1.67%   |
| Ralink Technology               | 2         | 1.67%   |
| Insyde Software                 | 2         | 1.67%   |
| American Megatrends             | 2         | 1.67%   |
| Sierra Wireless                 | 1         | 0.83%   |
| Samsung Electronics             | 1         | 0.83%   |
| Ralink                          | 1         | 0.83%   |
| Qualcomm Atheros Communications | 1         | 0.83%   |
| MediaTek                        | 1         | 0.83%   |
| Emulex                          | 1         | 0.83%   |
| ASIX Electronics                | 1         | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 19        | 12.67%  |
| Intel I350 Gigabit Network Connection                                 | 5         | 3.33%   |
| Intel Wi-Fi 6 AX200                                                   | 4         | 2.67%   |
| Intel Ethernet Controller X550                                        | 4         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 4         | 2.67%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3         | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 3         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter            | 3         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter            | 3         | 2%      |
| Intel Wireless 7260                                                   | 3         | 2%      |
| Intel Wi-Fi 6 AX201                                                   | 3         | 2%      |
| Intel I210 Gigabit Network Connection                                 | 3         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                     | 3         | 2%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 2%      |
| Standard Microsystems Ethernet controller                             | 2         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 2         | 1.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                   | 2         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 1.33%   |
| Ralink MT7601U Wireless Adapter                                       | 2         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter            | 2         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                      | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                            | 2         | 1.33%   |
| Intel Wireless 8260                                                   | 2         | 1.33%   |
| Intel Wireless 3165                                                   | 2         | 1.33%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 1.33%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 1.33%   |
| Intel 82574L Gigabit Network Connection                               | 2         | 1.33%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 1.33%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 2         | 1.33%   |
| American Megatrends Virtual Ethernet.                                 | 2         | 1.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 0.67%   |
| TP-Link Archer T4U ver.3                                              | 1         | 0.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                | 1         | 0.67%   |
| Sierra Wireless EM7345 4G LTE                                         | 1         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 0.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller           | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter              | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                       | 1         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                            | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                       | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 44.83%  |
| Qualcomm Atheros                | 11        | 18.97%  |
| Realtek Semiconductor           | 10        | 17.24%  |
| TP-Link                         | 2         | 3.45%   |
| Ralink Technology               | 2         | 3.45%   |
| Broadcom Limited                | 2         | 3.45%   |
| Broadcom                        | 2         | 3.45%   |
| Sierra Wireless                 | 1         | 1.72%   |
| Ralink                          | 1         | 1.72%   |
| Qualcomm Atheros Communications | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                         | 4         | 6.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 3         | 5.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 3         | 5.17%   |
| Intel Wireless 7260                                         | 3         | 5.17%   |
| Intel Wi-Fi 6 AX201                                         | 3         | 5.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 3         | 5.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 2         | 3.45%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter         | 2         | 3.45%   |
| Ralink MT7601U Wireless Adapter                             | 2         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 2         | 3.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 2         | 3.45%   |
| Intel Wireless 8265 / 8275                                  | 2         | 3.45%   |
| Intel Wireless 8260                                         | 2         | 3.45%   |
| Intel Wireless 3165                                         | 2         | 3.45%   |
| TP-Link Archer T4U ver.3                                    | 1         | 1.72%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                      | 1         | 1.72%   |
| Sierra Wireless EM7345 4G LTE                               | 1         | 1.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 1         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 1         | 1.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter             | 1         | 1.72%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 1.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 1         | 1.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                   | 1         | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                             | 1         | 1.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter            | 1         | 1.72%   |
| Intel Wireless 7265                                         | 1         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                      | 1         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                              | 1         | 1.72%   |
| Intel Centrino Wireless-N 2230                              | 1         | 1.72%   |
| Intel Centrino Ultimate-N 6300                              | 1         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                | 1         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 1         | 1.72%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                     | 1         | 1.72%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter | 1         | 1.72%   |
| Broadcom BCM43225 802.11b/g/n                               | 1         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 35%     |
| Realtek Semiconductor | 26        | 32.5%   |
| Broadcom              | 6         | 7.5%    |
| Qualcomm Atheros      | 3         | 3.75%   |
| Mellanox Technologies | 3         | 3.75%   |
| Broadcom Limited      | 3         | 3.75%   |
| Standard Microsystems | 2         | 2.5%    |
| Insyde Software       | 2         | 2.5%    |
| American Megatrends   | 2         | 2.5%    |
| TP-Link               | 1         | 1.25%   |
| Samsung Electronics   | 1         | 1.25%   |
| MediaTek              | 1         | 1.25%   |
| Emulex                | 1         | 1.25%   |
| ASIX Electronics      | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 19        | 20.65%  |
| Intel I350 Gigabit Network Connection                                 | 5         | 5.43%   |
| Intel Ethernet Controller X550                                        | 4         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 4         | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3         | 3.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 3         | 3.26%   |
| Intel I210 Gigabit Network Connection                                 | 3         | 3.26%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 3.26%   |
| Standard Microsystems Ethernet controller                             | 2         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 2.17%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 2.17%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 2.17%   |
| Intel 82574L Gigabit Network Connection                               | 2         | 2.17%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 2.17%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 2         | 2.17%   |
| American Megatrends Virtual Ethernet.                                 | 2         | 2.17%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 1.09%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller             | 1         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                 | 1         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.09%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 1.09%   |
| Mellanox MT27800 Family [ConnectX-5]                                  | 1         | 1.09%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.09%   |
| MediaTek Infinix HOT 11S NFC                                          | 1         | 1.09%   |
| Intel I211 Gigabit Network Connection                                 | 1         | 1.09%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.09%   |
| Intel Ethernet Connection I219-V                                      | 1         | 1.09%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.09%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.09%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 1.09%   |
| Intel Ethernet Connection (5) I219-V                                  | 1         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 67        | 55.37%  |
| WiFi     | 54        | 44.63%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 51.9%   |
| WiFi     | 38        | 48.1%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 40        | 49.38%  |
| 1     | 25        | 30.86%  |
| 4     | 5         | 6.17%   |
| 3     | 3         | 3.7%    |
| 0     | 3         | 3.7%    |
| 6     | 2         | 2.47%   |
| 5     | 2         | 2.47%   |
| 8     | 1         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 63        | 75.9%   |
| Yes  | 20        | 24.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 50%     |
| Qualcomm Atheros Communications | 8         | 16.67%  |
| Realtek Semiconductor           | 7         | 14.58%  |
| Broadcom                        | 3         | 6.25%   |
| Foxconn / Hon Hai               | 2         | 4.17%   |
| Cambridge Silicon Radio         | 2         | 4.17%   |
| Lite-On Technology              | 1         | 2.08%   |
| ASUSTek Computer                | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 20.83%  |
| Intel AX201 Bluetooth                               | 7         | 14.58%  |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 12.5%   |
| Realtek Bluetooth Radio                             | 5         | 10.42%  |
| Intel AX200 Bluetooth                               | 4         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.17%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.08%   |
| Lite-On Bluetooth Device                            | 1         | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.08%   |
| Intel AX210 Bluetooth                               | 1         | 2.08%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.08%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.08%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 47        | 48.45%  |
| AMD                  | 24        | 24.74%  |
| Nvidia               | 19        | 19.59%  |
| C-Media Electronics  | 2         | 2.06%   |
| Giga-Byte Technology | 1         | 1.03%   |
| Conrad Electronic SE | 1         | 1.03%   |
| Conexant Systems     | 1         | 1.03%   |
| ASUSTek Computer     | 1         | 1.03%   |
| Apple                | 1         | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 8.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 5.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 4.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 3.39%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.54%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.69%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 1.69%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.69%   |
| AMD High Definition Audio Controller                                       | 2         | 1.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.85%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia Audio device                                                        | 1         | 0.85%   |
| Nvidia AD102 High Definition Audio Controller                              | 1         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.85%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.85%   |
| Intel Lewisburg MROM 0                                                     | 1         | 0.85%   |
| Intel DG2 Audio Controller                                                 | 1         | 0.85%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 21.67%  |
| Kingston            | 10        | 16.67%  |
| SK hynix            | 9         | 15%     |
| Micron Technology   | 9         | 15%     |
| Crucial             | 6         | 10%     |
| G.Skill             | 3         | 5%      |
| Unknown             | 2         | 3.33%   |
| Elpida              | 2         | 3.33%   |
| Corsair             | 2         | 3.33%   |
| Unknown (0x0100)    | 1         | 1.67%   |
| Timetec             | 1         | 1.67%   |
| QEMU                | 1         | 1.67%   |
| Hewlett-Packard     | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.94%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 2.94%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 2.94%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 1.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.47%   |
| Unknown (0x0100) RAM R744G2133S1S 4GB SODIMM DDR4 1866MT/s       | 1         | 1.47%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.47%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s            | 1         | 1.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 1.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 1.47%   |
| SK hynix RAM HMA82GR7AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 1.47%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.47%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.47%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.47%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.47%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.47%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.47%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s              | 1         | 1.47%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s             | 1         | 1.47%   |
| QEMU RAM Module 8GB DIMM RAM                                     | 1         | 1.47%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s              | 1         | 1.47%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.47%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.47%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s             | 1         | 1.47%   |
| Micron RAM 36ASF8G72PZ-3G2E1 64GB DIMM DDR4 3200MT/s             | 1         | 1.47%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 33        | 64.71%  |
| DDR3    | 12        | 23.53%  |
| LPDDR3  | 2         | 3.92%   |
| RAM     | 1         | 1.96%   |
| DDR5    | 1         | 1.96%   |
| DDR2    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 25        | 49.02%  |
| SODIMM       | 23        | 45.1%   |
| Row Of Chips | 3         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 37.04%  |
| 4096  | 11        | 20.37%  |
| 16384 | 10        | 18.52%  |
| 32768 | 7         | 12.96%  |
| 2048  | 3         | 5.56%   |
| 65536 | 2         | 3.7%    |
| 49152 | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 18        | 30.51%  |
| 2667    | 10        | 16.95%  |
| 1600    | 9         | 15.25%  |
| 2400    | 4         | 6.78%   |
| 2133    | 4         | 6.78%   |
| 1866    | 3         | 5.08%   |
| 1333    | 3         | 5.08%   |
| 4800    | 1         | 1.69%   |
| 3600    | 1         | 1.69%   |
| 3466    | 1         | 1.69%   |
| 3066    | 1         | 1.69%   |
| 1867    | 1         | 1.69%   |
| 800     | 1         | 1.69%   |
| 667     | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 25.58%  |
| IMC Networks                           | 5         | 11.63%  |
| Microdia                               | 4         | 9.3%    |
| Bison Electronics                      | 4         | 9.3%    |
| Realtek Semiconductor                  | 3         | 6.98%   |
| Luxvisions Innotech Limited            | 3         | 6.98%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.98%   |
| Suyin                                  | 2         | 4.65%   |
| Logitech                               | 2         | 4.65%   |
| Syntek                                 | 1         | 2.33%   |
| SunplusIT                              | 1         | 2.33%   |
| Sunplus Innovation Technology          | 1         | 2.33%   |
| Microsoft                              | 1         | 2.33%   |
| Creative Technology                    | 1         | 2.33%   |
| Acer                                   | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 8.89%   |
| Chicony HP Truevision HD                                                 | 3         | 6.67%   |
| Realtek Integrated Webcam HD                                             | 2         | 4.44%   |
| Chicony Integrated HP HD Webcam                                          | 2         | 4.44%   |
| Bison Integrated Camera                                                  | 2         | 4.44%   |
| Syntek Integrated Camera                                                 | 1         | 2.22%   |
| Suyin HD WebCam                                                          | 1         | 2.22%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 1         | 2.22%   |
| SunplusIT HD Webcam                                                      | 1         | 2.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 2.22%   |
| Realtek EasyCamera                                                       | 1         | 2.22%   |
| Microsoft LifeCam HD-3000                                                | 1         | 2.22%   |
| Microdia USB 2.0 Camera                                                  | 1         | 2.22%   |
| Microdia Lenovo EasyCamera                                               | 1         | 2.22%   |
| Microdia Integrated_Webcam_HD                                            | 1         | 2.22%   |
| Microdia Integrated Webcam HD                                            | 1         | 2.22%   |
| Luxvisions Innotech Limited Integrated Camera                            | 1         | 2.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.22%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 1         | 2.22%   |
| Logitech Webcam C120                                                     | 1         | 2.22%   |
| Logitech Webcam B500                                                     | 1         | 2.22%   |
| Logitech QuickCam Vision Pro                                             | 1         | 2.22%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                     | 1         | 2.22%   |
| Creative Live! Cam Chat HD [VF0700]                                      | 1         | 2.22%   |
| Chicony Web Camera - HD                                                  | 1         | 2.22%   |
| Chicony Lenovo EasyCamera                                                | 1         | 2.22%   |
| Chicony Integrated RGB Camera                                            | 1         | 2.22%   |
| Chicony HP TrueVision HD Camera                                          | 1         | 2.22%   |
| Chicony EasyCamera                                                       | 1         | 2.22%   |
| Chicony 8M Camera                                                        | 1         | 2.22%   |
| Chicony 720p HD Camera                                                   | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera          | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision FHD Camera         | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.22%   |
| Bison Lenovo EasyCamera                                                  | 1         | 2.22%   |
| Bison HD Webcam                                                          | 1         | 2.22%   |
| Acer USB Camera                                                          | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 70%     |
| Synaptics             | 2         | 20%     |
| Elan Microelectronics | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| OmniKey     | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| OmniKey CardMan 3021 / 3121                    | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 44        | 54.32%  |
| 1     | 28        | 34.57%  |
| 2     | 5         | 6.17%   |
| 3     | 2         | 2.47%   |
| 7     | 1         | 1.23%   |
| 5     | 1         | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 28%     |
| Fingerprint reader       | 10        | 20%     |
| Net/wireless             | 6         | 12%     |
| Multimedia controller    | 4         | 8%      |
| Net/ethernet             | 3         | 6%      |
| Unassigned class         | 2         | 4%      |
| Sound                    | 2         | 4%      |
| Communication controller | 2         | 4%      |
| Storage/raid             | 1         | 2%      |
| Storage/ide              | 1         | 2%      |
| Storage                  | 1         | 2%      |
| Firewire controller      | 1         | 2%      |
| Chipcard                 | 1         | 2%      |
| Camera                   | 1         | 2%      |
| Bluetooth                | 1         | 2%      |

