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

Total: 196

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| AlmaLinux 9.1 | 21        | 29.58%  |
| AlmaLinux 8.6 | 10        | 14.08%  |
| AlmaLinux 9.0 | 9         | 12.68%  |
| AlmaLinux 8.7 | 9         | 12.68%  |
| AlmaLinux 8.4 | 9         | 12.68%  |
| AlmaLinux 8.3 | 4         | 5.63%   |
| AlmaLinux 9.2 | 3         | 4.23%   |
| AlmaLinux 8.8 | 3         | 4.23%   |
| AlmaLinux 8.5 | 3         | 4.23%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 66        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64   | 8         | 11.11%  |
| 4.18.0-425.3.1.el8.x86_64     | 6         | 8.33%   |
| 5.14.0-162.12.1.el9_1.x86_64  | 5         | 6.94%   |
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 4.17%   |
| 5.14.0-284.11.1.el9_2.x86_64  | 3         | 4.17%   |
| 5.14.0-162.18.1.el9_1.x86_64  | 3         | 4.17%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 4.17%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 4.17%   |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 2.78%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 2.78%   |
| 5.14.0-162.22.2.el9_1.x86_64  | 2         | 2.78%   |
| 4.18.0-477.10.1.el8_8.x86_64  | 2         | 2.78%   |
| 4.18.0-425.13.1.el8_7.x86_64  | 2         | 2.78%   |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 2.78%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 2.78%   |
| 4.18.0-305.el8.x86_64         | 2         | 2.78%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 2.78%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 2.78%   |
| 6.3.0-2.el9.elrepo.x86_64     | 1         | 1.39%   |
| 6.1.24-1kx.el9.x86_64         | 1         | 1.39%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 1.39%   |
| 5.15.45-v8.1.el8              | 1         | 1.39%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 1         | 1.39%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 1.39%   |
| 5.14.0-162.23.1.el9_1.x86_64  | 1         | 1.39%   |
| 5.10.60-v8.1.el8              | 1         | 1.39%   |
| 4.18.0-477.13.1.el8_8.x86_64  | 1         | 1.39%   |
| 4.18.0-425.19.2.el8_7.x86_64  | 1         | 1.39%   |
| 4.18.0-425.10.1.el8_7.x86_64  | 1         | 1.39%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 1.39%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 1.39%   |
| 4.18.0-348.el8.x86_64         | 1         | 1.39%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 1         | 1.39%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 1         | 1.39%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 1         | 1.39%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 1         | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 31        | 46.27%  |
| 4.18.0  | 31        | 46.27%  |
| 6.3.0   | 1         | 1.49%   |
| 6.1.24  | 1         | 1.49%   |
| 5.4.175 | 1         | 1.49%   |
| 5.15.45 | 1         | 1.49%   |
| 5.10.60 | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 31        | 46.27%  |
| 4.18    | 31        | 46.27%  |
| 6.3     | 1         | 1.49%   |
| 6.1     | 1         | 1.49%   |
| 5.4     | 1         | 1.49%   |
| 5.15    | 1         | 1.49%   |
| 5.10    | 1         | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 63        | 95.45%  |
| aarch64 | 3         | 4.55%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 38        | 57.58%  |
| Unknown         | 18        | 27.27%  |
| MATE            | 3         | 4.55%   |
| KDE5            | 3         | 4.55%   |
| XFCE            | 2         | 3.03%   |
| GNOME Flashback | 1         | 1.52%   |
| GNOME Classic   | 1         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 32        | 47.76%  |
| X11     | 24        | 35.82%  |
| Unknown | 7         | 10.45%  |
| Tty     | 4         | 5.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 65.15%  |
| GDM     | 18        | 27.27%  |
| LightDM | 3         | 4.55%   |
| SDDM    | 2         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 33        | 48.53%  |
| en_GB   | 7         | 10.29%  |
| de_DE   | 7         | 10.29%  |
| fr_FR   | 4         | 5.88%   |
| en_CA   | 4         | 5.88%   |
| Unknown | 3         | 4.41%   |
| ru_RU   | 2         | 2.94%   |
| C       | 2         | 2.94%   |
| uk_UA   | 1         | 1.47%   |
| ru_UA   | 1         | 1.47%   |
| pl_PL   | 1         | 1.47%   |
| es_VE   | 1         | 1.47%   |
| es_ES   | 1         | 1.47%   |
| da_DK   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 42        | 62.69%  |
| BIOS | 25        | 37.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 51        | 77.27%  |
| Ext4 | 15        | 22.73%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 36        | 54.55%  |
| Unknown | 22        | 33.33%  |
| MBR     | 8         | 12.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 81.82%  |
| Yes       | 12        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 80.3%   |
| Yes       | 13        | 19.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 14        | 21.21%  |
| Hewlett-Packard         | 12        | 18.18%  |
| Dell                    | 7         | 10.61%  |
| ASUSTek Computer        | 5         | 7.58%   |
| Gigabyte Technology     | 4         | 6.06%   |
| Supermicro              | 3         | 4.55%   |
| MSI                     | 3         | 4.55%   |
| Intel                   | 3         | 4.55%   |
| Raspberry Pi Foundation | 2         | 3.03%   |
| Google                  | 2         | 3.03%   |
| ASRockRack              | 2         | 3.03%   |
| ASRock                  | 2         | 3.03%   |
| Acer                    | 2         | 3.03%   |
| TUXEDO                  | 1         | 1.52%   |
| Toshiba                 | 1         | 1.52%   |
| Optimized Hosting       | 1         | 1.52%   |
| Maibenben               | 1         | 1.52%   |
| AZW                     | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 3.03%   |
| TUXEDO Aura 15 Gen1                  | 1         | 1.52%   |
| Toshiba Satellite L50-C              | 1         | 1.52%   |
| Supermicro Super Server              | 1         | 1.52%   |
| Supermicro PIO-617R-TLN4F+-ST031     | 1         | 1.52%   |
| Supermicro motherboard-H12 Series    | 1         | 1.52%   |
| Optimized Hosting KVM                | 1         | 1.52%   |
| MSI MS-7900                          | 1         | 1.52%   |
| MSI MS-7816                          | 1         | 1.52%   |
| MSI GL75 9SE                         | 1         | 1.52%   |
| Maibenben MaiBook X series           | 1         | 1.52%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.52%   |
| Lenovo V14-ARE 82DQ                  | 1         | 1.52%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 1.52%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 1.52%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 1.52%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS | 1         | 1.52%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 1.52%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 1.52%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS    | 1         | 1.52%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 1.52%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 1.52%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.52%   |
| Lenovo H520S 10093                   | 1         | 1.52%   |
| Lenovo B50-30 20382                  | 1         | 1.52%   |
| Intel powered classmate PC           | 1         | 1.52%   |
| Intel NUC8i5BEH                      | 1         | 1.52%   |
| Intel NUC6i5SYB H81131-503           | 1         | 1.52%   |
| HP ZBook 17 G2                       | 1         | 1.52%   |
| HP Z620 Workstation                  | 1         | 1.52%   |
| HP Z600 Workstation                  | 1         | 1.52%   |
| HP Z2 Tower G4 Workstation           | 1         | 1.52%   |
| HP ProLiant DL360p Gen8              | 1         | 1.52%   |
| HP Laptop 17-cp0xxx                  | 1         | 1.52%   |
| HP Laptop 15-ef1xxx                  | 1         | 1.52%   |
| HP Falco                             | 1         | 1.52%   |
| HP ENVY dv6                          | 1         | 1.52%   |
| HP EliteBook 8570w                   | 1         | 1.52%   |
| HP EliteBook 850 G8 Notebook PC      | 1         | 1.52%   |
| HP EliteBook 8470p                   | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo ThinkPad                  | 3         | 4.55%   |
| Lenovo IdeaPad                   | 3         | 4.55%   |
| HP EliteBook                     | 3         | 4.55%   |
| RPi Raspberry                    | 2         | 3.03%   |
| Lenovo Legion                    | 2         | 3.03%   |
| HP Laptop                        | 2         | 3.03%   |
| Dell Inspiron                    | 2         | 3.03%   |
| TUXEDO Aura                      | 1         | 1.52%   |
| Toshiba Satellite                | 1         | 1.52%   |
| Supermicro Super                 | 1         | 1.52%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1         | 1.52%   |
| Supermicro motherboard-H12       | 1         | 1.52%   |
| Optimized Hosting KVM            | 1         | 1.52%   |
| MSI MS-7900                      | 1         | 1.52%   |
| MSI MS-7816                      | 1         | 1.52%   |
| MSI GL75                         | 1         | 1.52%   |
| Maibenben MaiBook                | 1         | 1.52%   |
| Lenovo Yoga                      | 1         | 1.52%   |
| Lenovo V14-ARE                   | 1         | 1.52%   |
| Lenovo ThinkStation              | 1         | 1.52%   |
| Lenovo IdeaPadFlex               | 1         | 1.52%   |
| Lenovo H520S                     | 1         | 1.52%   |
| Lenovo B50-30                    | 1         | 1.52%   |
| Intel powered                    | 1         | 1.52%   |
| Intel NUC8i5BEH                  | 1         | 1.52%   |
| Intel NUC6i5SYB                  | 1         | 1.52%   |
| HP ZBook                         | 1         | 1.52%   |
| HP Z620                          | 1         | 1.52%   |
| HP Z600                          | 1         | 1.52%   |
| HP Z2                            | 1         | 1.52%   |
| HP ProLiant                      | 1         | 1.52%   |
| HP Falco                         | 1         | 1.52%   |
| HP ENVY                          | 1         | 1.52%   |
| Google Kohaku                    | 1         | 1.52%   |
| Google Kefka                     | 1         | 1.52%   |
| Gigabyte Z690                    | 1         | 1.52%   |
| Gigabyte Z590                    | 1         | 1.52%   |
| Gigabyte MP32-AR1-00             | 1         | 1.52%   |
| Gigabyte H81M-D2V                | 1         | 1.52%   |
| Dell XPS                         | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 13        | 19.7%   |
| 2012    | 8         | 12.12%  |
| 2022    | 7         | 10.61%  |
| 2019    | 6         | 9.09%   |
| 2021    | 5         | 7.58%   |
| 2014    | 5         | 7.58%   |
| 2018    | 4         | 6.06%   |
| 2015    | 4         | 6.06%   |
| 2013    | 3         | 4.55%   |
| 2011    | 3         | 4.55%   |
| 2016    | 2         | 3.03%   |
| 2010    | 2         | 3.03%   |
| Unknown | 2         | 3.03%   |
| 2017    | 1         | 1.52%   |
| 2009    | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 32        | 48.48%  |
| Desktop        | 20        | 30.3%   |
| Server         | 7         | 10.61%  |
| Mini pc        | 3         | 4.55%   |
| System on chip | 2         | 3.03%   |
| Convertible    | 2         | 3.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 58        | 87.88%  |
| Enabled  | 8         | 12.12%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 63        | 95.45%  |
| Yes  | 3         | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 17        | 25.37%  |
| 8.01-16.0       | 16        | 23.88%  |
| 64.01-256.0     | 9         | 13.43%  |
| 16.01-24.0      | 6         | 8.96%   |
| More than 256.0 | 5         | 7.46%   |
| 3.01-4.0        | 5         | 7.46%   |
| 24.01-32.0      | 3         | 4.48%   |
| 32.01-64.0      | 2         | 2.99%   |
| 1.01-2.0        | 2         | 2.99%   |
| 0.51-1.0        | 2         | 2.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 17        | 24.64%  |
| 1.01-2.0        | 14        | 20.29%  |
| 3.01-4.0        | 12        | 17.39%  |
| 4.01-8.0        | 10        | 14.49%  |
| 8.01-16.0       | 3         | 4.35%   |
| 0.51-1.0        | 3         | 4.35%   |
| 32.01-64.0      | 2         | 2.9%    |
| 24.01-32.0      | 2         | 2.9%    |
| 16.01-24.0      | 2         | 2.9%    |
| 0.01-0.5        | 2         | 2.9%    |
| More than 256.0 | 1         | 1.45%   |
| 64.01-256.0     | 1         | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 43.28%  |
| 2      | 22        | 32.84%  |
| 3      | 6         | 8.96%   |
| 4      | 5         | 7.46%   |
| 12     | 1         | 1.49%   |
| 11     | 1         | 1.49%   |
| 6      | 1         | 1.49%   |
| 5      | 1         | 1.49%   |
| 0      | 1         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 75.76%  |
| Yes       | 16        | 24.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 80.3%   |
| No        | 13        | 19.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 65.15%  |
| No        | 23        | 34.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 59.09%  |
| No        | 27        | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 17        | 25.76%  |
| Germany      | 8         | 12.12%  |
| France       | 6         | 9.09%   |
| Canada       | 5         | 7.58%   |
| UK           | 4         | 6.06%   |
| Russia       | 4         | 6.06%   |
| Netherlands  | 3         | 4.55%   |
| Ukraine      | 2         | 3.03%   |
| Spain        | 2         | 3.03%   |
| Venezuela    | 1         | 1.52%   |
| Switzerland  | 1         | 1.52%   |
| Sweden       | 1         | 1.52%   |
| South Africa | 1         | 1.52%   |
| Puerto Rico  | 1         | 1.52%   |
| Poland       | 1         | 1.52%   |
| Pakistan     | 1         | 1.52%   |
| Mexico       | 1         | 1.52%   |
| Kazakhstan   | 1         | 1.52%   |
| India        | 1         | 1.52%   |
| Greenland    | 1         | 1.52%   |
| Finland      | 1         | 1.52%   |
| China        | 1         | 1.52%   |
| Bulgaria     | 1         | 1.52%   |
| Austria      | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Hamburg          | 3         | 4.48%   |
| Saint-Brieuc     | 2         | 2.99%   |
| Queens           | 2         | 2.99%   |
| Dallas           | 2         | 2.99%   |
| Zaporizhzhia     | 1         | 1.49%   |
| Zandvoort        | 1         | 1.49%   |
| Winterswijk      | 1         | 1.49%   |
| Wejherowo        | 1         | 1.49%   |
| Vienna           | 1         | 1.49%   |
| Uppsala          | 1         | 1.49%   |
| Tuusula          | 1         | 1.49%   |
| Tampa            | 1         | 1.49%   |
| Strasbourg       | 1         | 1.49%   |
| Stadtilm         | 1         | 1.49%   |
| St. Paul         | 1         | 1.49%   |
| Sofia            | 1         | 1.49%   |
| Shimanovsk       | 1         | 1.49%   |
| Shanghai         | 1         | 1.49%   |
| San Diego        | 1         | 1.49%   |
| Rothwell         | 1         | 1.49%   |
| Regina           | 1         | 1.49%   |
| Redlands         | 1         | 1.49%   |
| Parla            | 1         | 1.49%   |
| Paris            | 1         | 1.49%   |
| Nizhniy Novgorod | 1         | 1.49%   |
| Moscow           | 1         | 1.49%   |
| Mangalore        | 1         | 1.49%   |
| Los Angeles      | 1         | 1.49%   |
| London           | 1         | 1.49%   |
| Liverpool        | 1         | 1.49%   |
| Lille            | 1         | 1.49%   |
| Lawrence         | 1         | 1.49%   |
| Land O' Lakes    | 1         | 1.49%   |
| Lahore           | 1         | 1.49%   |
| Kyiv             | 1         | 1.49%   |
| Kitimat          | 1         | 1.49%   |
| Kennewick        | 1         | 1.49%   |
| Johannesburg     | 1         | 1.49%   |
| Irapuato         | 1         | 1.49%   |
| Ilulissat        | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 14        | 16     | 13.73%  |
| Samsung Electronics         | 14        | 19     | 13.73%  |
| Seagate                     | 13        | 25     | 12.75%  |
| Kingston                    | 6         | 8      | 5.88%   |
| Intel                       | 5         | 5      | 4.9%    |
| Unknown                     | 4         | 6      | 3.92%   |
| SK hynix                    | 4         | 4      | 3.92%   |
| Kingston Technology Company | 4         | 16     | 3.92%   |
| Crucial                     | 4         | 12     | 3.92%   |
| Toshiba                     | 3         | 4      | 2.94%   |
| Sandisk                     | 3         | 3      | 2.94%   |
| Netac                       | 3         | 3      | 2.94%   |
| Micron Technology           | 2         | 2      | 1.96%   |
| LITEONIT                    | 2         | 4      | 1.96%   |
| Hewlett-Packard             | 2         | 9      | 1.96%   |
| Dell                        | 2         | 3      | 1.96%   |
| Union Memory                | 1         | 1      | 0.98%   |
| Transcend                   | 1         | 1      | 0.98%   |
| Team                        | 1         | 1      | 0.98%   |
| SSSTC                       | 1         | 1      | 0.98%   |
| Silicon Motion              | 1         | 12     | 0.98%   |
| QEMU                        | 1         | 1      | 0.98%   |
| Plextor                     | 1         | 1      | 0.98%   |
| Phison                      | 1         | 1      | 0.98%   |
| LITEON                      | 1         | 1      | 0.98%   |
| KIOXIA                      | 1         | 1      | 0.98%   |
| Hitachi                     | 1         | 1      | 0.98%   |
| HGST                        | 1         | 1      | 0.98%   |
| EMTEC                       | 1         | 2      | 0.98%   |
| DELLBOSS                    | 1         | 1      | 0.98%   |
| China                       | 1         | 1      | 0.98%   |
| ASMT                        | 1         | 2      | 0.98%   |
| A-DATA Technology           | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                            | 2         | 1.77%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2         | 1.77%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                    | 2         | 1.77%   |
| Kingston Company KC2000 NVMe SSD 1TB              | 2         | 1.77%   |
| Kingston Company A2000 NVMe SSD 500GB             | 2         | 1.77%   |
| Kingston SA400S37480G 480GB SSD                   | 2         | 1.77%   |
| Crucial CT240BX500SSD1 240GB                      | 2         | 1.77%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 0.88%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 0.88%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.88%   |
| WDC WD20EARS-00J2GB0 2TB                          | 1         | 0.88%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 0.88%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.88%   |
| WDC WD10JPVX-00JC3T0 1TB                          | 1         | 0.88%   |
| WDC WD10EZEX-75M2NA0 1TB                          | 1         | 0.88%   |
| WDC WD10EZEX-00KUWA0 1TB                          | 1         | 0.88%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB              | 1         | 0.88%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 0.88%   |
| Unknown SD64G  64GB                               | 1         | 0.88%   |
| Unknown SD/MMC/MS PRO 64GB                        | 1         | 0.88%   |
| Unknown MMC Card  16GB                            | 1         | 0.88%   |
| Unknown EC2QT  64GB                               | 1         | 0.88%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB           | 1         | 0.88%   |
| Transcend TS256GMTE220S 256GB                     | 1         | 0.88%   |
| Toshiba MK6475GSX 640GB                           | 1         | 0.88%   |
| Toshiba MG06ACA800E 8TB                           | 1         | 0.88%   |
| Toshiba DT01ACA100 1TB                            | 1         | 0.88%   |
| Team T253X1480G 480GB SSD                         | 1         | 0.88%   |
| SSSTC CL1-3D256 256GB                             | 1         | 0.88%   |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1         | 0.88%   |
| SK hynix PC300 NVMe Solid State Drive 256GB       | 1         | 0.88%   |
| SK hynix NVMe SSD Drive 256GB                     | 1         | 0.88%   |
| SK hynix BC511 NVMe 256GB                         | 1         | 0.88%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1         | 0.88%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB       | 1         | 0.88%   |
| Seagate ST4000NC001-1FS168 4TB                    | 1         | 0.88%   |
| Seagate ST4000DM000-1F2168 4TB                    | 1         | 0.88%   |
| Seagate ST31000528AS 1TB                          | 1         | 0.88%   |
| Seagate ST3000DM001-1CH166 3TB                    | 1         | 0.88%   |
| Seagate ST250LM004 HN-M250MBB 250GB               | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 21     | 35.29%  |
| WDC                 | 11        | 11     | 32.35%  |
| Toshiba             | 3         | 4      | 8.82%   |
| Unknown             | 1         | 2      | 2.94%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| QEMU                | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |
| HGST                | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 8      | 2.94%   |
| DELLBOSS            | 1         | 1      | 2.94%   |
| ASMT                | 1         | 2      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 15.63%  |
| Kingston            | 5         | 5      | 15.63%  |
| Intel               | 4         | 4      | 12.5%   |
| Crucial             | 3         | 10     | 9.38%   |
| Netac               | 2         | 2      | 6.25%   |
| LITEONIT            | 2         | 4      | 6.25%   |
| WDC                 | 1         | 3      | 3.13%   |
| Team                | 1         | 1      | 3.13%   |
| SK hynix            | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Plextor             | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Dell                | 1         | 2      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 31        | 66     | 32.63%  |
| SSD     | 30        | 44     | 31.58%  |
| HDD     | 30        | 53     | 31.58%  |
| MMC     | 3         | 4      | 3.16%   |
| Unknown | 1         | 2      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 91     | 55.29%  |
| NVMe | 31        | 66     | 36.47%  |
| SAS  | 4         | 8      | 4.71%   |
| MMC  | 3         | 4      | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 35     | 44.44%  |
| 0.51-1.0   | 22        | 35     | 34.92%  |
| 1.01-2.0   | 6         | 12     | 9.52%   |
| 3.01-4.0   | 3         | 3      | 4.76%   |
| 4.01-10.0  | 3         | 11     | 4.76%   |
| 2.01-3.0   | 1         | 1      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 29.41%  |
| 251-500        | 10        | 14.71%  |
| 501-1000       | 10        | 14.71%  |
| More than 3000 | 6         | 8.82%   |
| 1001-2000      | 5         | 7.35%   |
| 51-100         | 5         | 7.35%   |
| Unknown        | 5         | 7.35%   |
| 1-20           | 3         | 4.41%   |
| 21-50          | 2         | 2.94%   |
| 2001-3000      | 2         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 31        | 43.66%  |
| 21-50          | 12        | 16.9%   |
| 101-250        | 8         | 11.27%  |
| 51-100         | 7         | 9.86%   |
| Unknown        | 5         | 7.04%   |
| 251-500        | 3         | 4.23%   |
| More than 3000 | 2         | 2.82%   |
| 2001-3000      | 1         | 1.41%   |
| 1001-2000      | 1         | 1.41%   |
| 501-1000       | 1         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J2GB0 2TB          | 1         | 1      | 20%     |
| SK hynix SH920 2.5 7MM 256GB SSD  | 1         | 1      | 20%     |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2      | 20%     |
| Samsung Electronics HD642JJ 640GB | 1         | 1      | 20%     |
| LITEONIT LSS-16L6G-HP 16GB SSD    | 1         | 3      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| SK hynix            | 1         | 1      | 20%     |
| Seagate             | 1         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| LITEONIT            | 1         | 3      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Seagate             | 1         | 2      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 60%     |
| SSD  | 2         | 4      | 40%     |

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
| Works    | 40        | 111    | 53.33%  |
| Detected | 30        | 50     | 40%     |
| Malfunc  | 5         | 8      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 39        | 41.05%  |
| AMD                            | 17        | 17.89%  |
| Samsung Electronics            | 10        | 10.53%  |
| Kingston Technology Company    | 6         | 6.32%   |
| SanDisk                        | 3         | 3.16%   |
| Union Memory (Shenzhen)        | 2         | 2.11%   |
| SK hynix                       | 2         | 2.11%   |
| Silicon Motion                 | 2         | 2.11%   |
| Marvell Technology Group       | 2         | 2.11%   |
| LSI Logic / Symbios Logic      | 2         | 2.11%   |
| Toshiba America Info Systems   | 1         | 1.05%   |
| Solid State Storage Technology | 1         | 1.05%   |
| Seagate Technology             | 1         | 1.05%   |
| Red Hat                        | 1         | 1.05%   |
| Phison Electronics             | 1         | 1.05%   |
| Netac Technology               | 1         | 1.05%   |
| Micron/Crucial Technology      | 1         | 1.05%   |
| Micron Technology              | 1         | 1.05%   |
| Hewlett-Packard                | 1         | 1.05%   |
| Broadcom / LSI                 | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 13.46%  |
| Samsung NVMe SSD Controller 980                                                | 4         | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.88%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 1.92%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 1.92%   |
| Kingston Company KC2000 NVMe SSD                                               | 2         | 1.92%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.92%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.92%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2         | 1.92%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 2         | 1.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.96%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.96%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.96%   |
| SK hynix BC511                                                                 | 1         | 0.96%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.96%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.96%   |
| SanDisk NVMe Controller                                                        | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.96%   |
| Red Hat Virtio 1.0 SCSI                                                        | 1         | 0.96%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.96%   |
| Netac Non-Volatile memory controller                                           | 1         | 0.96%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.96%   |
| Micron NVMe Controller                                                         | 1         | 0.96%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.96%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1         | 0.96%   |
| LSI Logic / Symbios Logic SAS3008 PCI-Express Fusion-MPT SAS-3                 | 1         | 0.96%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                        | 1         | 0.96%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46        | 48.42%  |
| NVMe | 31        | 32.63%  |
| RAID | 9         | 9.47%   |
| IDE  | 5         | 5.26%   |
| SAS  | 3         | 3.16%   |
| SCSI | 1         | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 42        | 63.64%  |
| AMD    | 21        | 31.82%  |
| ARM    | 3         | 4.55%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 4.48%   |
| ARM Processor                               | 3         | 4.48%   |
| AMD EPYC 7282 16-Core Processor             | 2         | 2.99%   |
| Intel Xeon W-1350 @ 3.30GHz                 | 1         | 1.49%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 1.49%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz         | 1         | 1.49%   |
| Intel Xeon E-2144G CPU @ 3.60GHz            | 1         | 1.49%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1         | 1.49%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1         | 1.49%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz          | 1         | 1.49%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 1.49%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.49%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.49%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.49%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.49%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.49%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.49%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 1.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.49%   |
| Intel Core i5-6260U CPU @ 1.80GHz           | 1         | 1.49%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.49%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.49%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.49%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.49%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 1.49%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.49%   |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1         | 1.49%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.49%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 1.49%   |
| Intel Celeron 2955U @ 1.40GHz               | 1         | 1.49%   |
| Intel Atom CPU N455 @ 1.66GHz               | 1         | 1.49%   |
| Intel 12th Gen Core i7-12700KF              | 1         | 1.49%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 19.7%   |
| Other                   | 8         | 12.12%  |
| Intel Xeon              | 7         | 10.61%  |
| Intel Core i7           | 7         | 10.61%  |
| Intel Core i3           | 5         | 7.58%   |
| AMD EPYC                | 5         | 7.58%   |
| AMD Ryzen 7             | 4         | 6.06%   |
| AMD Ryzen 5             | 4         | 6.06%   |
| Intel Celeron           | 2         | 3.03%   |
| AMD Ryzen 9             | 2         | 3.03%   |
| AMD A10                 | 2         | 3.03%   |
| Intel Xeon Gold         | 1         | 1.52%   |
| Intel Pentium Dual-Core | 1         | 1.52%   |
| Intel Pentium           | 1         | 1.52%   |
| Intel Atom              | 1         | 1.52%   |
| AMD Ryzen 3             | 1         | 1.52%   |
| AMD FX                  | 1         | 1.52%   |
| AMD A6                  | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 20        | 29.85%  |
| 2       | 19        | 28.36%  |
| 6       | 9         | 13.43%  |
| 16      | 4         | 5.97%   |
| 12      | 4         | 5.97%   |
| 8       | 4         | 5.97%   |
| Unknown | 2         | 2.99%   |
| 80      | 1         | 1.49%   |
| 48      | 1         | 1.49%   |
| 32      | 1         | 1.49%   |
| 24      | 1         | 1.49%   |
| 1       | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 59        | 89.39%  |
| 2       | 4         | 6.06%   |
| Unknown | 2         | 3.03%   |
| 4       | 1         | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 52        | 78.79%  |
| 1       | 12        | 18.18%  |
| Unknown | 2         | 3.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 95.45%  |
| Unknown        | 3         | 4.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 16.18%  |
| 0x806ec    | 4         | 5.88%   |
| 0x306a9    | 4         | 5.88%   |
| 0x40651    | 3         | 4.41%   |
| 0x306c3    | 3         | 4.41%   |
| 0xa0671    | 2         | 2.94%   |
| 0x906ea    | 2         | 2.94%   |
| 0x806c1    | 2         | 2.94%   |
| 0x406e3    | 2         | 2.94%   |
| 0x306e4    | 2         | 2.94%   |
| 0x08701021 | 2         | 2.94%   |
| 0x08600106 | 2         | 2.94%   |
| 0x08301055 | 2         | 2.94%   |
| 0xa0655    | 1         | 1.47%   |
| 0xa0652    | 1         | 1.47%   |
| 0x906ed    | 1         | 1.47%   |
| 0x906e9    | 1         | 1.47%   |
| 0x90672    | 1         | 1.47%   |
| 0x806e9    | 1         | 1.47%   |
| 0x806d1    | 1         | 1.47%   |
| 0x506e3    | 1         | 1.47%   |
| 0x50657    | 1         | 1.47%   |
| 0x406c4    | 1         | 1.47%   |
| 0x30678    | 1         | 1.47%   |
| 0x206a7    | 1         | 1.47%   |
| 0x20655    | 1         | 1.47%   |
| 0x106ca    | 1         | 1.47%   |
| 0x106a5    | 1         | 1.47%   |
| 0x1067a    | 1         | 1.47%   |
| 0x0a50000d | 1         | 1.47%   |
| 0x0a50000c | 1         | 1.47%   |
| 0x08608103 | 1         | 1.47%   |
| 0x08108109 | 1         | 1.47%   |
| 0x08108102 | 1         | 1.47%   |
| 0x0810100b | 1         | 1.47%   |
| 0x06006705 | 1         | 1.47%   |
| 0x06006704 | 1         | 1.47%   |
| 0x06006110 | 1         | 1.47%   |
| 0x06003106 | 1         | 1.47%   |
| 0x06000852 | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 10        | 15.15%  |
| KabyLake         | 10        | 15.15%  |
| IvyBridge        | 6         | 9.09%   |
| Haswell          | 6         | 9.09%   |
| Skylake          | 4         | 6.06%   |
| Unknown          | 4         | 6.06%   |
| Icelake          | 3         | 4.55%   |
| Excavator        | 3         | 4.55%   |
| Zen+             | 2         | 3.03%   |
| Zen 3            | 2         | 3.03%   |
| TigerLake        | 2         | 3.03%   |
| Silvermont       | 2         | 3.03%   |
| SandyBridge      | 2         | 3.03%   |
| CometLake        | 2         | 3.03%   |
| Zen              | 1         | 1.52%   |
| Westmere         | 1         | 1.52%   |
| Steamroller      | 1         | 1.52%   |
| Piledriver       | 1         | 1.52%   |
| Penryn           | 1         | 1.52%   |
| Nehalem          | 1         | 1.52%   |
| Bonnell          | 1         | 1.52%   |
| Alderlake Hybrid | 1         | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 31        | 43.06%  |
| Nvidia                     | 16        | 22.22%  |
| AMD                        | 16        | 22.22%  |
| ASPEED Technology          | 5         | 6.94%   |
| Matrox Electronics Systems | 3         | 4.17%   |
| Red Hat                    | 1         | 1.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                 | 5         | 6.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                         | 3         | 4.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                     | 3         | 4.17%   |
| Nvidia GA106 [Geforce RTX 3050]                                          | 2         | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                | 2         | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                | 2         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                         | 2         | 2.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                 | 2         | 2.78%   |
| AMD Renoir                                                               | 2         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]     | 2         | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]             | 2         | 2.78%   |
| Red Hat QXL paravirtual graphic card                                     | 1         | 1.39%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                               | 1         | 1.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                  | 1         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                  | 1         | 1.39%   |
| Nvidia GP107GL [Quadro P620]                                             | 1         | 1.39%   |
| Nvidia GP104 [GeForce GTX 1080]                                          | 1         | 1.39%   |
| Nvidia GM108M [GeForce 930M]                                             | 1         | 1.39%   |
| Nvidia GM107GL [Quadro K2200]                                            | 1         | 1.39%   |
| Nvidia GK107GLM [Quadro K1000M]                                          | 1         | 1.39%   |
| Nvidia GK104GLM [Quadro K3100M]                                          | 1         | 1.39%   |
| Nvidia GK104 [GeForce GTX 770]                                           | 1         | 1.39%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                        | 1         | 1.39%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                       | 1         | 1.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                          | 1         | 1.39%   |
| Nvidia GA102GL [RTX A6000]                                               | 1         | 1.39%   |
| Matrox Electronics Systems MGA G200eW WPCM450                            | 1         | 1.39%   |
| Matrox Electronics Systems MGA G200EH                                    | 1         | 1.39%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller | 1         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                               | 1         | 1.39%   |
| Intel Tiger Lake-H GT1 [UHD Graphics]                                    | 1         | 1.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                      | 1         | 1.39%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                               | 1         | 1.39%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                | 1         | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller             | 1         | 1.39%   |
| Intel Iris Graphics 540                                                  | 1         | 1.39%   |
| Intel HD Graphics 615                                                    | 1         | 1.39%   |
| Intel HD Graphics 530                                                    | 1         | 1.39%   |
| Intel DG2 [Arc A770]                                                     | 1         | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                      | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 36.36%  |
| 1 x AMD        | 15        | 22.73%  |
| 1 x Nvidia     | 9         | 13.64%  |
| Intel + Nvidia | 6         | 9.09%   |
| 1 x ASPEED     | 4         | 6.06%   |
| 1 x Matrox     | 3         | 4.55%   |
| Other          | 2         | 3.03%   |
| 1 x Red Hat    | 1         | 1.52%   |
| Intel + ASPEED | 1         | 1.52%   |
| AMD + Nvidia   | 1         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 50        | 75.76%  |
| Unknown     | 12        | 18.18%  |
| Proprietary | 4         | 6.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 60.61%  |
| 0.01-0.5   | 9         | 13.64%  |
| 1.01-2.0   | 6         | 9.09%   |
| 7.01-8.0   | 3         | 4.55%   |
| 5.01-6.0   | 3         | 4.55%   |
| 3.01-4.0   | 3         | 4.55%   |
| 32.01-64.0 | 1         | 1.52%   |
| 0.51-1.0   | 1         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 15.09%  |
| LG Display              | 7         | 13.21%  |
| Samsung Electronics     | 6         | 11.32%  |
| Chimei Innolux          | 4         | 7.55%   |
| BOE                     | 4         | 7.55%   |
| ViewSonic               | 2         | 3.77%   |
| Sharp                   | 2         | 3.77%   |
| PANDA                   | 2         | 3.77%   |
| InfoVision              | 2         | 3.77%   |
| Goldstar                | 2         | 3.77%   |
| Dell                    | 2         | 3.77%   |
| BenQ                    | 2         | 3.77%   |
| TopView                 | 1         | 1.89%   |
| STD                     | 1         | 1.89%   |
| Seiki                   | 1         | 1.89%   |
| Philips                 | 1         | 1.89%   |
| Medion                  | 1         | 1.89%   |
| Lenovo                  | 1         | 1.89%   |
| Eizo                    | 1         | 1.89%   |
| Chi Mei Optoelectronics | 1         | 1.89%   |
| AOC                     | 1         | 1.89%   |
| Acer                    | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 2         | 3.7%    |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch               | 1         | 1.85%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 470x300mm 22.0-inch            | 1         | 1.85%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                      | 1         | 1.85%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                        | 1         | 1.85%   |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch                  | 1         | 1.85%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 1.85%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 1.85%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch     | 1         | 1.85%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch        | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 1         | 1.85%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch       | 1         | 1.85%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                        | 1         | 1.85%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                  | 1         | 1.85%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 1.85%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                    | 1         | 1.85%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 1.85%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 1.85%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch             | 1         | 1.85%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 1.85%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1         | 1.85%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                    | 1         | 1.85%   |
| Eizo EV2336W ENC2390 1920x1080 510x287mm 23.0-inch                       | 1         | 1.85%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                         | 1         | 1.85%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1510 1920x1080 344x193mm 15.5-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.85%   |
| BOE LCD Monitor BOE09BA 2560x1600 345x215mm 16.0-inch                    | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 57.41%  |
| 1366x768 (WXGA)    | 10        | 18.52%  |
| 1280x1024 (SXGA)   | 3         | 5.56%   |
| 3840x2160 (4K)     | 2         | 3.7%    |
| 3200x1800 (QHD+)   | 1         | 1.85%   |
| 2560x1600          | 1         | 1.85%   |
| 2560x1440 (QHD)    | 1         | 1.85%   |
| 2560x1080          | 1         | 1.85%   |
| 1920x1200 (WUXGA)  | 1         | 1.85%   |
| 1680x1050 (WSXGA+) | 1         | 1.85%   |
| 1600x900 (HD+)     | 1         | 1.85%   |
| 1400x1050          | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 14        | 25.93%  |
| 14     | 7         | 12.96%  |
| 13     | 5         | 9.26%   |
| 31     | 4         | 7.41%   |
| 24     | 4         | 7.41%   |
| 21     | 4         | 7.41%   |
| 17     | 4         | 7.41%   |
| 27     | 2         | 3.7%    |
| 19     | 2         | 3.7%    |
| 11     | 2         | 3.7%    |
| 34     | 1         | 1.85%   |
| 23     | 1         | 1.85%   |
| 22     | 1         | 1.85%   |
| 20     | 1         | 1.85%   |
| 18     | 1         | 1.85%   |
| 16     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 44.44%  |
| 501-600     | 7         | 12.96%  |
| 351-400     | 7         | 12.96%  |
| 401-500     | 6         | 11.11%  |
| 201-300     | 5         | 9.26%   |
| 601-700     | 4         | 7.41%   |
| 701-800     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 84.31%  |
| 16/10 | 3         | 5.88%   |
| 5/4   | 2         | 3.92%   |
| 6/5   | 1         | 1.96%   |
| 4/3   | 1         | 1.96%   |
| 21/9  | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 25.93%  |
| 81-90          | 9         | 16.67%  |
| 151-200        | 7         | 12.96%  |
| 201-250        | 6         | 11.11%  |
| 351-500        | 5         | 9.26%   |
| 121-130        | 4         | 7.41%   |
| 71-80          | 3         | 5.56%   |
| 51-60          | 2         | 3.7%    |
| 301-350        | 2         | 3.7%    |
| 251-300        | 1         | 1.85%   |
| 111-120        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 38.46%  |
| 51-100        | 15        | 28.85%  |
| 101-120       | 11        | 21.15%  |
| More than 240 | 3         | 5.77%   |
| 161-240       | 2         | 3.85%   |
| 1-50          | 1         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 63.64%  |
| 0     | 16        | 24.24%  |
| 2     | 8         | 12.12%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 36.84%  |
| Realtek Semiconductor | 24        | 25.26%  |
| Qualcomm Atheros      | 10        | 10.53%  |
| Broadcom              | 7         | 7.37%   |
| Broadcom Limited      | 3         | 3.16%   |
| TP-Link               | 2         | 2.11%   |
| Standard Microsystems | 2         | 2.11%   |
| Ralink Technology     | 2         | 2.11%   |
| Mellanox Technologies | 2         | 2.11%   |
| Insyde Software       | 2         | 2.11%   |
| Sierra Wireless       | 1         | 1.05%   |
| Samsung Electronics   | 1         | 1.05%   |
| Ralink                | 1         | 1.05%   |
| MediaTek              | 1         | 1.05%   |
| Emulex                | 1         | 1.05%   |
| American Megatrends   | 1         | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 14.29%  |
| Intel I350 Gigabit Network Connection                             | 4         | 3.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.52%   |
| Intel Wireless 7260                                               | 3         | 2.52%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 2.52%   |
| Standard Microsystems Ethernet controller                         | 2         | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.68%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2         | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.68%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.68%   |
| Intel Wireless 8260                                               | 2         | 1.68%   |
| Intel Wireless 3165                                               | 2         | 1.68%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.68%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.68%   |
| Intel Ethernet Controller X550                                    | 2         | 1.68%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 2         | 1.68%   |
| Insyde Software RNDIS/Ethernet Gadget                             | 2         | 1.68%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.84%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.84%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.84%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.84%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.84%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.84%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.84%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                           | 1         | 0.84%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 47.83%  |
| Qualcomm Atheros      | 9         | 19.57%  |
| Realtek Semiconductor | 7         | 15.22%  |
| Ralink Technology     | 2         | 4.35%   |
| Broadcom              | 2         | 4.35%   |
| TP-Link               | 1         | 2.17%   |
| Sierra Wireless       | 1         | 2.17%   |
| Ralink                | 1         | 2.17%   |
| Broadcom Limited      | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 6.52%   |
| Intel Wireless 7260                                        | 3         | 6.52%   |
| Intel Wi-Fi 6 AX200                                        | 3         | 6.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 6.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 4.35%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 2         | 4.35%   |
| Ralink MT7601U Wireless Adapter                            | 2         | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 4.35%   |
| Intel Wireless 8260                                        | 2         | 4.35%   |
| Intel Wireless 3165                                        | 2         | 4.35%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 4.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1         | 2.17%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.17%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 2.17%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 2.17%   |
| Intel Wireless 8265 / 8275                                 | 1         | 2.17%   |
| Intel Wireless 7265                                        | 1         | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.17%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.17%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 2.17%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 2.17%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 35.48%  |
| Intel                 | 21        | 33.87%  |
| Broadcom              | 5         | 8.06%   |
| Standard Microsystems | 2         | 3.23%   |
| Qualcomm Atheros      | 2         | 3.23%   |
| Mellanox Technologies | 2         | 3.23%   |
| Insyde Software       | 2         | 3.23%   |
| Broadcom Limited      | 2         | 3.23%   |
| TP-Link               | 1         | 1.61%   |
| MediaTek              | 1         | 1.61%   |
| Emulex                | 1         | 1.61%   |
| American Megatrends   | 1         | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 17        | 23.61%  |
| Intel I350 Gigabit Network Connection                                 | 4         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 4.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 4.17%   |
| Standard Microsystems Ethernet controller                             | 2         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                     | 2         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 2         | 2.78%   |
| Intel I210 Gigabit Network Connection                                 | 2         | 2.78%   |
| Intel Ethernet Controller X550                                        | 2         | 2.78%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 2.78%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 2.78%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 2.78%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller             | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.39%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 1.39%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.39%   |
| MediaTek CPH2211                                                      | 1         | 1.39%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.39%   |
| Intel Ethernet Connection I219-V                                      | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.39%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 1.39%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection (5) I219-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.39%   |
| Intel 82574L Gigabit Network Connection                               | 1         | 1.39%   |
| Emulex OneConnect 10Gb NIC (be3)                                      | 1         | 1.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 1         | 1.39%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 1.39%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                | 1         | 1.39%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe               | 1         | 1.39%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.39%   |
| American Megatrends Virtual Ethernet                                  | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 54.64%  |
| WiFi     | 43        | 44.33%  |
| Modem    | 1         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 34        | 53.13%  |
| WiFi     | 30        | 46.88%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 51.52%  |
| 1     | 21        | 31.82%  |
| 4     | 3         | 4.55%   |
| 0     | 3         | 4.55%   |
| 5     | 2         | 3.03%   |
| 8     | 1         | 1.52%   |
| 6     | 1         | 1.52%   |
| 3     | 1         | 1.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 77.61%  |
| Yes  | 15        | 22.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 53.85%  |
| Qualcomm Atheros Communications | 7         | 17.95%  |
| Realtek Semiconductor           | 4         | 10.26%  |
| Broadcom                        | 3         | 7.69%   |
| Cambridge Silicon Radio         | 2         | 5.13%   |
| Foxconn / Hon Hai               | 1         | 2.56%   |
| ASUSTek Computer                | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 23.08%  |
| Intel AX201 Bluetooth                               | 6         | 15.38%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 12.82%  |
| Realtek Bluetooth Radio                             | 3         | 7.69%   |
| Intel AX200 Bluetooth                               | 3         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.56%   |
| Intel AX210 Bluetooth                               | 1         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.56%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 39        | 50.65%  |
| AMD                  | 18        | 23.38%  |
| Nvidia               | 15        | 19.48%  |
| C-Media Electronics  | 2         | 2.6%    |
| Giga-Byte Technology | 1         | 1.3%    |
| Conrad Electronic SE | 1         | 1.3%    |
| Apple                | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 8.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 4.26%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 3.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 3.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.19%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 3.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 3.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.13%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.13%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.13%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.13%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia Audio device                                                                               | 1         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.06%   |
| Intel Lewisburg MROM 0                                                                            | 1         | 1.06%   |
| Intel DG2 Audio Controller                                                                        | 1         | 1.06%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.06%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.06%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.06%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 23.53%  |
| Kingston            | 10        | 19.61%  |
| Micron Technology   | 8         | 15.69%  |
| SK hynix            | 6         | 11.76%  |
| Crucial             | 6         | 11.76%  |
| Unknown             | 2         | 3.92%   |
| G.Skill             | 2         | 3.92%   |
| Elpida              | 2         | 3.92%   |
| Timetec             | 1         | 1.96%   |
| QEMU                | 1         | 1.96%   |
| Hewlett-Packard     | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 3.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 3.51%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 3.51%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 1.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.75%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.75%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.75%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s            | 1         | 1.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 1.75%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.75%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.75%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.75%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.75%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.75%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 1.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.75%   |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Samsung RAM M378A5244CB0-CRC 4096MB DIMM DDR4 3066MT/s           | 1         | 1.75%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s             | 1         | 1.75%   |
| QEMU RAM Module 8GB DIMM RAM                                     | 1         | 1.75%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s              | 1         | 1.75%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.75%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s             | 1         | 1.75%   |
| Micron RAM 36ASF8G72PZ-3G2E1 64GB DIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 1         | 1.75%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s           | 1         | 1.75%   |
| Kingston RAM 9965742-029.B00G 32GB DIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Kingston RAM 9965694-026.B00G 32GB DIMM DDR4 3200MT/s            | 1         | 1.75%   |
| Kingston RAM 9965694-009.B00G 32GB DIMM DDR4 3200MT/s            | 1         | 1.75%   |
| Kingston RAM 9965640-033.C00G 32GB DIMM DDR4 2667MT/s            | 1         | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 27        | 62.79%  |
| DDR3    | 11        | 25.58%  |
| LPDDR3  | 2         | 4.65%   |
| RAM     | 1         | 2.33%   |
| DDR2    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 21        | 48.84%  |
| SODIMM       | 19        | 44.19%  |
| Row Of Chips | 3         | 6.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 17        | 36.96%  |
| 4096  | 10        | 21.74%  |
| 16384 | 8         | 17.39%  |
| 32768 | 7         | 15.22%  |
| 65536 | 2         | 4.35%   |
| 2048  | 2         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 16        | 32.65%  |
| 1600    | 9         | 18.37%  |
| 2667    | 8         | 16.33%  |
| 2133    | 3         | 6.12%   |
| 2400    | 2         | 4.08%   |
| 1866    | 2         | 4.08%   |
| 1333    | 2         | 4.08%   |
| 3600    | 1         | 2.04%   |
| 3466    | 1         | 2.04%   |
| 3066    | 1         | 2.04%   |
| 1867    | 1         | 2.04%   |
| 800     | 1         | 2.04%   |
| 667     | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

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
| Chicony Electronics                    | 9         | 25.71%  |
| IMC Networks                           | 5         | 14.29%  |
| Microdia                               | 3         | 8.57%   |
| Bison Electronics                      | 3         | 8.57%   |
| Suyin                                  | 2         | 5.71%   |
| Realtek Semiconductor                  | 2         | 5.71%   |
| Luxvisions Innotech Limited            | 2         | 5.71%   |
| Logitech                               | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Acer                                   | 2         | 5.71%   |
| Syntek                                 | 1         | 2.86%   |
| SunplusIT                              | 1         | 2.86%   |
| Creative Technology                    | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 10.81%  |
| Chicony Integrated HP HD Webcam                                          | 2         | 5.41%   |
| Chicony HP Truevision HD                                                 | 2         | 5.41%   |
| Bison Integrated Camera                                                  | 2         | 5.41%   |
| Syntek Integrated Camera                                                 | 1         | 2.7%    |
| Suyin HD WebCam                                                          | 1         | 2.7%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 1         | 2.7%    |
| SunplusIT HD Webcam                                                      | 1         | 2.7%    |
| Realtek Integrated Webcam HD                                             | 1         | 2.7%    |
| Realtek EasyCamera                                                       | 1         | 2.7%    |
| Microdia Integrated_Webcam_HD                                            | 1         | 2.7%    |
| Microdia Integrated Webcam HD                                            | 1         | 2.7%    |
| Microdia CameraA                                                         | 1         | 2.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.7%    |
| Luxvisions Innotech Limited HP HD Camera                                 | 1         | 2.7%    |
| Logitech Webcam C120                                                     | 1         | 2.7%    |
| Logitech Webcam B500                                                     | 1         | 2.7%    |
| Logitech QuickCam Vision Pro                                             | 1         | 2.7%    |
| IMC Networks USB2.0 HD IR UVC WebCam                                     | 1         | 2.7%    |
| Creative Live! Cam Chat HD [VF0700]                                      | 1         | 2.7%    |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 2.7%    |
| Chicony Lenovo EasyCamera                                                | 1         | 2.7%    |
| Chicony Integrated RGB Camera                                            | 1         | 2.7%    |
| Chicony EasyCamera                                                       | 1         | 2.7%    |
| Chicony 8M Camera                                                        | 1         | 2.7%    |
| Chicony 720p HD Camera                                                   | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera          | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.7%    |
| Bison Lenovo EasyCamera                                                  | 1         | 2.7%    |
| Acer USB Camera                                                          | 1         | 2.7%    |
| Acer HD Webcam                                                           | 1         | 2.7%    |

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
| 0     | 35        | 53.03%  |
| 1     | 23        | 34.85%  |
| 2     | 5         | 7.58%   |
| 7     | 1         | 1.52%   |
| 5     | 1         | 1.52%   |
| 3     | 1         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 12        | 27.27%  |
| Fingerprint reader       | 10        | 22.73%  |
| Net/wireless             | 5         | 11.36%  |
| Multimedia controller    | 4         | 9.09%   |
| Net/ethernet             | 3         | 6.82%   |
| Sound                    | 2         | 4.55%   |
| Unassigned class         | 1         | 2.27%   |
| Storage/raid             | 1         | 2.27%   |
| Storage/ide              | 1         | 2.27%   |
| Firewire controller      | 1         | 2.27%   |
| Communication controller | 1         | 2.27%   |
| Chipcard                 | 1         | 2.27%   |
| Camera                   | 1         | 2.27%   |
| Bluetooth                | 1         | 2.27%   |

