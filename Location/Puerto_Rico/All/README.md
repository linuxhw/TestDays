Linux in Puerto Rico - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Puerto Rico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Puerto_Rico/Desktop/README.md) and [notebooks](/Location/Puerto_Rico/Notebook/README.md).

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

Total: 221

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6420              | Notebook    | [251fb963fe](https://linux-hardware.org/?probe=251fb963fe) | Nov 28, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [fe69e51efe](https://linux-hardware.org/?probe=fe69e51efe) | Nov 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| Dell          | G5 5505                     | Notebook    | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [1c9628e804](https://linux-hardware.org/?probe=1c9628e804) | Aug 15, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [12a6ae992a](https://linux-hardware.org/?probe=12a6ae992a) | Aug 14, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [846e1d6c9f](https://linux-hardware.org/?probe=846e1d6c9f) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | Notebook    | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Dell          | Precision M4700             | Notebook    | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [96645b0a94](https://linux-hardware.org/?probe=96645b0a94) | Aug 04, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [3f1e6ca5cb](https://linux-hardware.org/?probe=3f1e6ca5cb) | Jul 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [012b0c7fa9](https://linux-hardware.org/?probe=012b0c7fa9) | Jul 23, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9122678102](https://linux-hardware.org/?probe=9122678102) | Jul 21, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [69d676f7be](https://linux-hardware.org/?probe=69d676f7be) | Jul 12, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9d8195a435](https://linux-hardware.org/?probe=9d8195a435) | Jul 12, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [a42903b516](https://linux-hardware.org/?probe=a42903b516) | Jul 10, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [404e81318c](https://linux-hardware.org/?probe=404e81318c) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d0cfec8d80](https://linux-hardware.org/?probe=d0cfec8d80) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9fd7dc8784](https://linux-hardware.org/?probe=9fd7dc8784) | Jul 02, 2022 |
| MSI           | MS-AE031                    | All in one  | [d6f4214361](https://linux-hardware.org/?probe=d6f4214361) | Jun 30, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [9eaa432fcd](https://linux-hardware.org/?probe=9eaa432fcd) | Jun 02, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [ae5664a81f](https://linux-hardware.org/?probe=ae5664a81f) | May 12, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [83ed9adfc1](https://linux-hardware.org/?probe=83ed9adfc1) | May 04, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [860d883e5b](https://linux-hardware.org/?probe=860d883e5b) | Apr 29, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [074f1f75dc](https://linux-hardware.org/?probe=074f1f75dc) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [656e8c50dd](https://linux-hardware.org/?probe=656e8c50dd) | Apr 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1911200c56](https://linux-hardware.org/?probe=1911200c56) | Mar 23, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [fd3185704d](https://linux-hardware.org/?probe=fd3185704d) | Mar 21, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Dell          | Inspiron 17-7778            | Notebook    | [bcc52b2596](https://linux-hardware.org/?probe=bcc52b2596) | Mar 17, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [f96e26bb9a](https://linux-hardware.org/?probe=f96e26bb9a) | Mar 08, 2022 |
| Dell          | OptiPlex 7020               | Desktop     | [ba82f9d852](https://linux-hardware.org/?probe=ba82f9d852) | Mar 01, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a1ecd8a3cb](https://linux-hardware.org/?probe=a1ecd8a3cb) | Feb 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [e7ce3f2f38](https://linux-hardware.org/?probe=e7ce3f2f38) | Feb 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [86dbaf1d07](https://linux-hardware.org/?probe=86dbaf1d07) | Jan 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [51e8a3a34d](https://linux-hardware.org/?probe=51e8a3a34d) | Dec 31, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [464d10c41d](https://linux-hardware.org/?probe=464d10c41d) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| HP            | 1998                        | Desktop     | [7bc6ddebf4](https://linux-hardware.org/?probe=7bc6ddebf4) | Nov 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9af646fd14](https://linux-hardware.org/?probe=9af646fd14) | Nov 10, 2021 |
| ASRock        | Q1900M                      | Desktop     | [8482ae3a2f](https://linux-hardware.org/?probe=8482ae3a2f) | Nov 09, 2021 |
| HP            | 339A                        | Desktop     | [e2ce00d1ec](https://linux-hardware.org/?probe=e2ce00d1ec) | Nov 08, 2021 |
| Alienware     | 07W25T A00                  | Desktop     | [c08c87521f](https://linux-hardware.org/?probe=c08c87521f) | Nov 08, 2021 |
| HP            | ENVY Laptop 17m-bw0xxx      | Notebook    | [9ec292c9d9](https://linux-hardware.org/?probe=9ec292c9d9) | Oct 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8649bba9b6](https://linux-hardware.org/?probe=8649bba9b6) | Oct 22, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fede248f75](https://linux-hardware.org/?probe=fede248f75) | Oct 19, 2021 |
| HP            | ProBook 6450b               | Notebook    | [518e694864](https://linux-hardware.org/?probe=518e694864) | Oct 19, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [29c7fa76a8](https://linux-hardware.org/?probe=29c7fa76a8) | Oct 10, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [6818ec3abc](https://linux-hardware.org/?probe=6818ec3abc) | Oct 10, 2021 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [732c00f018](https://linux-hardware.org/?probe=732c00f018) | Oct 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [7ecda0a147](https://linux-hardware.org/?probe=7ecda0a147) | Sep 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [9ed2b3cf12](https://linux-hardware.org/?probe=9ed2b3cf12) | Sep 21, 2021 |
| GPU Compan... | GWTN156-9                   | Notebook    | [a9ac79c22a](https://linux-hardware.org/?probe=a9ac79c22a) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a96d28c504](https://linux-hardware.org/?probe=a96d28c504) | Sep 16, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [686eb55129](https://linux-hardware.org/?probe=686eb55129) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d120a0016d](https://linux-hardware.org/?probe=d120a0016d) | Aug 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [9ad69ca6ad](https://linux-hardware.org/?probe=9ad69ca6ad) | Jul 27, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [75fd544183](https://linux-hardware.org/?probe=75fd544183) | Jul 26, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a3b055840b](https://linux-hardware.org/?probe=a3b055840b) | Jul 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [cbcf0ae65d](https://linux-hardware.org/?probe=cbcf0ae65d) | Jul 07, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [c3b8ac12be](https://linux-hardware.org/?probe=c3b8ac12be) | Jul 07, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3a88077121](https://linux-hardware.org/?probe=3a88077121) | Jul 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [17a65dfb0e](https://linux-hardware.org/?probe=17a65dfb0e) | Jul 06, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [5af810dc36](https://linux-hardware.org/?probe=5af810dc36) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675992d5f9](https://linux-hardware.org/?probe=675992d5f9) | Jul 04, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [4782df79ce](https://linux-hardware.org/?probe=4782df79ce) | Jul 02, 2021 |
| HP            | ProBook 6560b               | Notebook    | [806dfcb6f0](https://linux-hardware.org/?probe=806dfcb6f0) | Jul 01, 2021 |
| HP            | ProBook 6450b               | Notebook    | [a8689c5d60](https://linux-hardware.org/?probe=a8689c5d60) | Jun 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fed4ef6298](https://linux-hardware.org/?probe=fed4ef6298) | Jun 23, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [14e1d81078](https://linux-hardware.org/?probe=14e1d81078) | Jun 23, 2021 |
| HP            | ProBook 6450b               | Notebook    | [b4c7a0fd32](https://linux-hardware.org/?probe=b4c7a0fd32) | Jun 21, 2021 |
| Pegatron      | 2ACD                        | Desktop     | [fd757c14ce](https://linux-hardware.org/?probe=fd757c14ce) | Jun 13, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| HP            | 1998                        | Desktop     | [4c3248677a](https://linux-hardware.org/?probe=4c3248677a) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [9239b61815](https://linux-hardware.org/?probe=9239b61815) | May 25, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [6b2ff5fb12](https://linux-hardware.org/?probe=6b2ff5fb12) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [639725c8af](https://linux-hardware.org/?probe=639725c8af) | May 24, 2021 |
| HP            | ENVY dv7                    | Notebook    | [651a68adc6](https://linux-hardware.org/?probe=651a68adc6) | May 24, 2021 |
| HP            | 339A                        | Desktop     | [ac11f05a1a](https://linux-hardware.org/?probe=ac11f05a1a) | May 21, 2021 |
| Intel         | SKYBAY                      | Desktop     | [9bc7ab87d1](https://linux-hardware.org/?probe=9bc7ab87d1) | May 19, 2021 |
| ASRock        | Q1900M                      | Desktop     | [7c778b5654](https://linux-hardware.org/?probe=7c778b5654) | May 02, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [7442c54767](https://linux-hardware.org/?probe=7442c54767) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| HP            | 1998                        | Desktop     | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Lenovo        | ThinkPad T410 2516ADU       | Notebook    | [5feb962d24](https://linux-hardware.org/?probe=5feb962d24) | Apr 07, 2021 |
| Intel         | SKYBAY                      | Desktop     | [472818e347](https://linux-hardware.org/?probe=472818e347) | Apr 04, 2021 |
| HP            | 1998                        | Desktop     | [f515fbf660](https://linux-hardware.org/?probe=f515fbf660) | Apr 01, 2021 |
| HP            | 1998                        | Desktop     | [3bc0a0dcb6](https://linux-hardware.org/?probe=3bc0a0dcb6) | Mar 20, 2021 |
| HP            | 1998                        | Desktop     | [a10d91fc1b](https://linux-hardware.org/?probe=a10d91fc1b) | Mar 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [5ab0183bc4](https://linux-hardware.org/?probe=5ab0183bc4) | Mar 18, 2021 |
| Intel         | SKYBAY                      | Desktop     | [ecefc99ed5](https://linux-hardware.org/?probe=ecefc99ed5) | Mar 14, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [332f4238da](https://linux-hardware.org/?probe=332f4238da) | Mar 09, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [775057eb07](https://linux-hardware.org/?probe=775057eb07) | Feb 20, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [b11309575f](https://linux-hardware.org/?probe=b11309575f) | Feb 19, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [48d2054858](https://linux-hardware.org/?probe=48d2054858) | Feb 16, 2021 |
| Dell          | 0DFRFW A00                  | Desktop     | [093c47fb9c](https://linux-hardware.org/?probe=093c47fb9c) | Feb 13, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d4372897b8](https://linux-hardware.org/?probe=d4372897b8) | Feb 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [190f14bae7](https://linux-hardware.org/?probe=190f14bae7) | Feb 13, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [2140e64244](https://linux-hardware.org/?probe=2140e64244) | Feb 13, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81a3e9faea](https://linux-hardware.org/?probe=81a3e9faea) | Feb 11, 2021 |
| HP            | 18E4                        | Desktop     | [db6eb1d366](https://linux-hardware.org/?probe=db6eb1d366) | Feb 05, 2021 |
| HP            | 18E4                        | Desktop     | [bad5f5110c](https://linux-hardware.org/?probe=bad5f5110c) | Feb 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63a2a56eda](https://linux-hardware.org/?probe=63a2a56eda) | Jan 25, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [b2513f813d](https://linux-hardware.org/?probe=b2513f813d) | Jan 16, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0523ff890c](https://linux-hardware.org/?probe=0523ff890c) | Jan 15, 2021 |
| HP            | 18E4                        | Desktop     | [729391b32e](https://linux-hardware.org/?probe=729391b32e) | Jan 08, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [5780c56d1e](https://linux-hardware.org/?probe=5780c56d1e) | Jan 06, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [ecaae6f562](https://linux-hardware.org/?probe=ecaae6f562) | Jan 05, 2021 |
| AMI           | Intel                       | Notebook    | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [5e4b418568](https://linux-hardware.org/?probe=5e4b418568) | Dec 19, 2020 |
| AZW           | GT-R                        | Notebook    | [19b47cf9f6](https://linux-hardware.org/?probe=19b47cf9f6) | Dec 16, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [ba371f8d43](https://linux-hardware.org/?probe=ba371f8d43) | Dec 07, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [646f020b0d](https://linux-hardware.org/?probe=646f020b0d) | Nov 27, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [844bb428a9](https://linux-hardware.org/?probe=844bb428a9) | Nov 22, 2020 |
| MSI           | MS-B1711                    | Desktop     | [8d69ecec16](https://linux-hardware.org/?probe=8d69ecec16) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [958741b7b6](https://linux-hardware.org/?probe=958741b7b6) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [3c327ae485](https://linux-hardware.org/?probe=3c327ae485) | Nov 17, 2020 |
| CompuLab      | fit-PC3                     | Mini pc     | [2e92dc00d4](https://linux-hardware.org/?probe=2e92dc00d4) | Nov 12, 2020 |
| Dell          | Latitude E6410              | Notebook    | [d188c9653d](https://linux-hardware.org/?probe=d188c9653d) | Nov 07, 2020 |
| Dell          | Latitude E6410              | Notebook    | [caf34f9e21](https://linux-hardware.org/?probe=caf34f9e21) | Nov 02, 2020 |
| MSI           | MS-B1711                    | Desktop     | [26c2dcf112](https://linux-hardware.org/?probe=26c2dcf112) | Nov 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [62ebca752a](https://linux-hardware.org/?probe=62ebca752a) | Oct 31, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [362d74125d](https://linux-hardware.org/?probe=362d74125d) | Oct 31, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [f7ec0211fb](https://linux-hardware.org/?probe=f7ec0211fb) | Oct 27, 2020 |
| ASRock        | Q1900M                      | Desktop     | [72cddfd9ae](https://linux-hardware.org/?probe=72cddfd9ae) | Oct 24, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [9d734dee6e](https://linux-hardware.org/?probe=9d734dee6e) | Sep 30, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e5448099f1](https://linux-hardware.org/?probe=e5448099f1) | Sep 27, 2020 |
| HP            | 339A                        | Desktop     | [47db0521b7](https://linux-hardware.org/?probe=47db0521b7) | Sep 23, 2020 |
| HP            | 339A                        | Desktop     | [51cec5b6f8](https://linux-hardware.org/?probe=51cec5b6f8) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [a027a185e5](https://linux-hardware.org/?probe=a027a185e5) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [ff87d18b2b](https://linux-hardware.org/?probe=ff87d18b2b) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [37cfc48ef8](https://linux-hardware.org/?probe=37cfc48ef8) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [254f23a364](https://linux-hardware.org/?probe=254f23a364) | Sep 21, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| HP            | 18E4                        | Desktop     | [277593bde6](https://linux-hardware.org/?probe=277593bde6) | Aug 07, 2020 |
| Acer          | Swift SF314-51              | Notebook    | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [478381d890](https://linux-hardware.org/?probe=478381d890) | Jul 12, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [f9271f6dae](https://linux-hardware.org/?probe=f9271f6dae) | Jul 09, 2020 |
| MSI           | Z370-A PRO                  | Desktop     | [f8629928a6](https://linux-hardware.org/?probe=f8629928a6) | Jun 18, 2020 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9aaeabab3d](https://linux-hardware.org/?probe=9aaeabab3d) | Jun 18, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d161c397ca](https://linux-hardware.org/?probe=d161c397ca) | Jun 14, 2020 |
| HP            | ENVY dv7                    | Notebook    | [2ae56a2828](https://linux-hardware.org/?probe=2ae56a2828) | May 24, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | Notebook    | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [98ba3a8ad5](https://linux-hardware.org/?probe=98ba3a8ad5) | May 17, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [572157356f](https://linux-hardware.org/?probe=572157356f) | May 13, 2020 |
| HP            | 18E4                        | Desktop     | [1fe1707854](https://linux-hardware.org/?probe=1fe1707854) | May 07, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [8805cd4168](https://linux-hardware.org/?probe=8805cd4168) | Apr 16, 2020 |
| Dell          | 0M017G A00                  | Desktop     | [e8b9eefb82](https://linux-hardware.org/?probe=e8b9eefb82) | Apr 13, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e2de1ae596](https://linux-hardware.org/?probe=e2de1ae596) | Apr 04, 2020 |
| HP            | ENVY dv7                    | Notebook    | [97ae3dc919](https://linux-hardware.org/?probe=97ae3dc919) | Mar 14, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [44caca0bb1](https://linux-hardware.org/?probe=44caca0bb1) | Mar 12, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [3d3261ccc3](https://linux-hardware.org/?probe=3d3261ccc3) | Mar 09, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [c0f180f342](https://linux-hardware.org/?probe=c0f180f342) | Mar 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [4ac0a3b1fe](https://linux-hardware.org/?probe=4ac0a3b1fe) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a2582aaec1](https://linux-hardware.org/?probe=a2582aaec1) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a63cd159a1](https://linux-hardware.org/?probe=a63cd159a1) | Mar 06, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [aa32ea3cb7](https://linux-hardware.org/?probe=aa32ea3cb7) | Mar 05, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [efa77a90cb](https://linux-hardware.org/?probe=efa77a90cb) | Mar 01, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [aca2204df4](https://linux-hardware.org/?probe=aca2204df4) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [40a8750e54](https://linux-hardware.org/?probe=40a8750e54) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [399d92cf32](https://linux-hardware.org/?probe=399d92cf32) | Feb 28, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [7c094d733b](https://linux-hardware.org/?probe=7c094d733b) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [ddebe02bcd](https://linux-hardware.org/?probe=ddebe02bcd) | Feb 28, 2020 |
| HP            | Notebook                    | Notebook    | [80f2a12798](https://linux-hardware.org/?probe=80f2a12798) | Feb 28, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [132413f9bd](https://linux-hardware.org/?probe=132413f9bd) | Feb 21, 2020 |
| HP            | 18E4                        | Desktop     | [ee3dae8f72](https://linux-hardware.org/?probe=ee3dae8f72) | Feb 17, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa684e430c](https://linux-hardware.org/?probe=fa684e430c) | Feb 13, 2020 |
| MSI           | B150 PC MATE                | Desktop     | [ed98074061](https://linux-hardware.org/?probe=ed98074061) | Oct 08, 2019 |
| ASRock        | G31M-S                      | Desktop     | [d1f69377d4](https://linux-hardware.org/?probe=d1f69377d4) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [595867810d](https://linux-hardware.org/?probe=595867810d) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [556d0f2ca6](https://linux-hardware.org/?probe=556d0f2ca6) | Jun 06, 2019 |
| ASRock        | 945GCM-S                    | Desktop     | [d4ea4c5cb6](https://linux-hardware.org/?probe=d4ea4c5cb6) | May 04, 2019 |
| HP            | 18E4                        | Desktop     | [36f9656af0](https://linux-hardware.org/?probe=36f9656af0) | Feb 15, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [d24fc7f682](https://linux-hardware.org/?probe=d24fc7f682) | Jan 30, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [525707b787](https://linux-hardware.org/?probe=525707b787) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [a7616fb055](https://linux-hardware.org/?probe=a7616fb055) | Jan 21, 2019 |
| HP            | 18E4                        | Desktop     | [c6cf9c7817](https://linux-hardware.org/?probe=c6cf9c7817) | Jan 04, 2019 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [85398272dc](https://linux-hardware.org/?probe=85398272dc) | Dec 03, 2018 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [10a5b1559d](https://linux-hardware.org/?probe=10a5b1559d) | Dec 03, 2018 |
| Dell          | Inspiron MP061              | Notebook    | [113fc7a00d](https://linux-hardware.org/?probe=113fc7a00d) | Jul 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [82229858ec](https://linux-hardware.org/?probe=82229858ec) | Jun 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [90f397422e](https://linux-hardware.org/?probe=90f397422e) | Jun 15, 2018 |
| ASRock        | 945GCM-S                    | Desktop     | [c7cbed362d](https://linux-hardware.org/?probe=c7cbed362d) | May 27, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 22        | 15.94%  |
| Ubuntu 18.04        | 11        | 7.97%   |
| Ubuntu 22.04        | 6         | 4.35%   |
| OpenMandriva 4.2    | 6         | 4.35%   |
| OpenMandriva 4.3    | 5         | 3.62%   |
| Ubuntu 21.10        | 4         | 2.9%    |
| Ubuntu 20.10        | 4         | 2.9%    |
| Zorin 16            | 3         | 2.17%   |
| Manjaro             | 3         | 2.17%   |
| Linux Mint 20.1     | 3         | 2.17%   |
| Linux Mint 19.3     | 3         | 2.17%   |
| KDE neon 20.04      | 3         | 2.17%   |
| Fedora 36           | 3         | 2.17%   |
| BlackPanther 18.1   | 3         | 2.17%   |
| Zorin 15            | 2         | 1.45%   |
| Xubuntu 20.04       | 2         | 1.45%   |
| Ubuntu 19.10        | 2         | 1.45%   |
| ROSA R11            | 2         | 1.45%   |
| ROSA R10            | 2         | 1.45%   |
| Lubuntu 20.04       | 2         | 1.45%   |
| LMDE 4              | 2         | 1.45%   |
| Linux Mint 21       | 2         | 1.45%   |
| Linux Mint 20.3     | 2         | 1.45%   |
| Linux Mint 20.2     | 2         | 1.45%   |
| Linux Mint 20       | 2         | 1.45%   |
| Garuda Linux        | 2         | 1.45%   |
| ArcoLinux Rolling   | 2         | 1.45%   |
| Xubuntu 20.10       | 1         | 0.72%   |
| Ubuntu Unity 20.04  | 1         | 0.72%   |
| Ubuntu MATE 20.04   | 1         | 0.72%   |
| Ubuntu Budgie 21.04 | 1         | 0.72%   |
| ROSA R9             | 1         | 0.72%   |
| Pop!_OS 21.10       | 1         | 0.72%   |
| Pop!_OS 21.04       | 1         | 0.72%   |
| Pop!_OS 20.10       | 1         | 0.72%   |
| Pop!_OS 20.04       | 1         | 0.72%   |
| Pop!_OS 19.10       | 1         | 0.72%   |
| Peppermint 9        | 1         | 0.72%   |
| Parrot 5.0          | 1         | 0.72%   |
| Parrot 4.11         | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 47        | 35.88%  |
| OpenMandriva  | 13        | 9.92%   |
| Linux Mint    | 12        | 9.16%   |
| Zorin         | 5         | 3.82%   |
| Pop!_OS       | 5         | 3.82%   |
| Fedora        | 5         | 3.82%   |
| ROSA          | 4         | 3.05%   |
| Manjaro       | 4         | 3.05%   |
| Xubuntu       | 3         | 2.29%   |
| KDE neon      | 3         | 2.29%   |
| Debian        | 3         | 2.29%   |
| BlackPanther  | 3         | 2.29%   |
| Parrot        | 2         | 1.53%   |
| openSUSE      | 2         | 1.53%   |
| Lubuntu       | 2         | 1.53%   |
| LMDE          | 2         | 1.53%   |
| Garuda Linux  | 2         | 1.53%   |
| Endless       | 2         | 1.53%   |
| ArcoLinux     | 2         | 1.53%   |
| Arch          | 2         | 1.53%   |
| Ubuntu Unity  | 1         | 0.76%   |
| Ubuntu MATE   | 1         | 0.76%   |
| Ubuntu Budgie | 1         | 0.76%   |
| Peppermint    | 1         | 0.76%   |
| LinuxFX       | 1         | 0.76%   |
| EndeavourOS   | 1         | 0.76%   |
| Devuan        | 1         | 0.76%   |
| CentOS        | 1         | 0.76%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 6         | 3.75%   |
| 5.16.7-desktop-1omv4003        | 5         | 3.13%   |
| 5.4.0-58-generic               | 4         | 2.5%    |
| 5.8.0-59-generic               | 3         | 1.88%   |
| 5.11.0-38-generic              | 3         | 1.88%   |
| 4.15.0-43-generic              | 3         | 1.88%   |
| 5.8.18-1-MANJARO               | 2         | 1.25%   |
| 5.8.0-55-generic               | 2         | 1.25%   |
| 5.8.0-45-generic               | 2         | 1.25%   |
| 5.4.0-73-generic               | 2         | 1.25%   |
| 5.4.0-72-generic               | 2         | 1.25%   |
| 5.4.0-52-generic               | 2         | 1.25%   |
| 5.4.0-48-generic               | 2         | 1.25%   |
| 5.4.0-47-generic               | 2         | 1.25%   |
| 5.4.0-40-generic               | 2         | 1.25%   |
| 5.4.0-109-generic              | 2         | 1.25%   |
| 5.3.0-41-generic               | 2         | 1.25%   |
| 5.3.0-28-generic               | 2         | 1.25%   |
| 5.15.0-46-generic              | 2         | 1.25%   |
| 5.15.0-40-generic              | 2         | 1.25%   |
| 5.15.0-25-generic              | 2         | 1.25%   |
| 5.13.0-40-generic              | 2         | 1.25%   |
| 5.13.0-39-generic              | 2         | 1.25%   |
| 5.13.0-35-generic              | 2         | 1.25%   |
| 5.13.0-30-generic              | 2         | 1.25%   |
| 5.11.0-41-generic              | 2         | 1.25%   |
| 5.11.0-27-generic              | 2         | 1.25%   |
| 4.18.16-desktop-1bP            | 2         | 1.25%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2         | 1.25%   |
| 5.9.16-200.fc33.x86_64         | 1         | 0.63%   |
| 5.9.16-1-MANJARO               | 1         | 0.63%   |
| 5.9.1-1-MANJARO                | 1         | 0.63%   |
| 5.8.5-zen1-1-zen               | 1         | 0.63%   |
| 5.8.14-zen1-1-zen              | 1         | 0.63%   |
| 5.8.0-7630-generic             | 1         | 0.63%   |
| 5.8.0-63-generic               | 1         | 0.63%   |
| 5.8.0-54-generic               | 1         | 0.63%   |
| 5.8.0-53-generic               | 1         | 0.63%   |
| 5.8.0-49-generic               | 1         | 0.63%   |
| 5.8.0-44-generic               | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 21.58%  |
| 5.8.0   | 14        | 10.07%  |
| 5.13.0  | 11        | 7.91%   |
| 4.15.0  | 10        | 7.19%   |
| 5.11.0  | 9         | 6.47%   |
| 5.15.0  | 7         | 5.04%   |
| 5.3.0   | 6         | 4.32%   |
| 5.10.14 | 6         | 4.32%   |
| 5.16.7  | 5         | 3.6%    |
| 5.10.0  | 3         | 2.16%   |
| 4.19.0  | 3         | 2.16%   |
| 4.18.0  | 3         | 2.16%   |
| 5.9.16  | 2         | 1.44%   |
| 5.8.18  | 2         | 1.44%   |
| 4.9.60  | 2         | 1.44%   |
| 4.18.16 | 2         | 1.44%   |
| 5.9.1   | 1         | 0.72%   |
| 5.8.5   | 1         | 0.72%   |
| 5.8.14  | 1         | 0.72%   |
| 5.6.14  | 1         | 0.72%   |
| 5.3.6   | 1         | 0.72%   |
| 5.3.18  | 1         | 0.72%   |
| 5.19.7  | 1         | 0.72%   |
| 5.19.12 | 1         | 0.72%   |
| 5.18.9  | 1         | 0.72%   |
| 5.18.6  | 1         | 0.72%   |
| 5.18.5  | 1         | 0.72%   |
| 5.18.15 | 1         | 0.72%   |
| 5.18.12 | 1         | 0.72%   |
| 5.18.0  | 1         | 0.72%   |
| 5.17.1  | 1         | 0.72%   |
| 5.15.59 | 1         | 0.72%   |
| 5.15.5  | 1         | 0.72%   |
| 5.14.8  | 1         | 0.72%   |
| 5.13.19 | 1         | 0.72%   |
| 5.12.4  | 1         | 0.72%   |
| 5.11.16 | 1         | 0.72%   |
| 5.11.13 | 1         | 0.72%   |
| 4.9.20  | 1         | 0.72%   |
| 4.9.0   | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 22.22%  |
| 5.8     | 18        | 13.33%  |
| 5.13    | 12        | 8.89%   |
| 5.11    | 10        | 7.41%   |
| 4.15    | 10        | 7.41%   |
| 5.15    | 9         | 6.67%   |
| 5.10    | 9         | 6.67%   |
| 5.3     | 8         | 5.93%   |
| 5.16    | 5         | 3.7%    |
| 5.18    | 4         | 2.96%   |
| 4.9     | 4         | 2.96%   |
| 4.18    | 4         | 2.96%   |
| 5.9     | 3         | 2.22%   |
| 4.19    | 3         | 2.22%   |
| 5.19    | 2         | 1.48%   |
| 5.6     | 1         | 0.74%   |
| 5.17    | 1         | 0.74%   |
| 5.14    | 1         | 0.74%   |
| 5.12    | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 110       | 96.49%  |
| i686    | 2         | 1.75%   |
| aarch64 | 2         | 1.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 61        | 46.92%  |
| KDE5       | 25        | 19.23%  |
| X-Cinnamon | 10        | 7.69%   |
| XFCE       | 7         | 5.38%   |
| MATE       | 6         | 4.62%   |
| Unknown    | 6         | 4.62%   |
| LXQt       | 2         | 1.54%   |
| LXDE       | 2         | 1.54%   |
| KDE4       | 2         | 1.54%   |
| KDE        | 2         | 1.54%   |
| i3         | 2         | 1.54%   |
| Budgie     | 2         | 1.54%   |
| Unity      | 1         | 0.77%   |
| Deepin     | 1         | 0.77%   |
| Cinnamon   | 1         | 0.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 103       | 88.03%  |
| Wayland | 13        | 11.11%  |
| Unknown | 1         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 58.73%  |
| SDDM    | 18        | 14.29%  |
| GDM3    | 16        | 12.7%   |
| GDM     | 7         | 5.56%   |
| LightDM | 6         | 4.76%   |
| TDM     | 3         | 2.38%   |
| KDM     | 2         | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 96        | 82.76%  |
| Unknown | 12        | 10.34%  |
| es_PR   | 5         | 4.31%   |
| C       | 2         | 1.72%   |
| es_ES   | 1         | 0.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 66        | 55%     |
| EFI  | 54        | 45%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 88        | 73.33%  |
| Overlay | 17        | 14.17%  |
| Btrfs   | 8         | 6.67%   |
| Unknown | 5         | 4.17%   |
| Zfs     | 1         | 0.83%   |
| Xfs     | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 84        | 69.42%  |
| GPT     | 28        | 23.14%  |
| MBR     | 9         | 7.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 83.33%  |
| Yes       | 20        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 75.21%  |
| Yes       | 30        | 24.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 21        | 18.42%  |
| Dell                    | 21        | 18.42%  |
| Lenovo                  | 10        | 8.77%   |
| Gigabyte Technology     | 9         | 7.89%   |
| ASUSTek Computer        | 9         | 7.89%   |
| ASRock                  | 9         | 7.89%   |
| MSI                     | 8         | 7.02%   |
| Acer                    | 5         | 4.39%   |
| Apple                   | 4         | 3.51%   |
| Toshiba                 | 3         | 2.63%   |
| Intel                   | 3         | 2.63%   |
| Sony                    | 2         | 1.75%   |
| Raspberry Pi Foundation | 2         | 1.75%   |
| TUXEDO                  | 1         | 0.88%   |
| Pegatron                | 1         | 0.88%   |
| GPU Company             | 1         | 0.88%   |
| CompuLab                | 1         | 0.88%   |
| AZW                     | 1         | 0.88%   |
| AMI                     | 1         | 0.88%   |
| Alienware               | 1         | 0.88%   |
| Acidanthera             | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel SKYBAY                             | 3         | 2.63%   |
| Dell Vostro 3550                         | 3         | 2.63%   |
| RPi Raspberry Pi                         | 2         | 1.75%   |
| MSI Cubi N 8GL (MS-B171)                 | 2         | 1.75%   |
| ASRock Q1900M                            | 2         | 1.75%   |
| ASRock 945GCM-S                          | 2         | 1.75%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.88%   |
| Toshiba Satellite P755                   | 1         | 0.88%   |
| Toshiba Satellite L655                   | 1         | 0.88%   |
| Toshiba Satellite C55-C                  | 1         | 0.88%   |
| Sony VPCEA36FX                           | 1         | 0.88%   |
| Sony VGN-CS320J                          | 1         | 0.88%   |
| Pegatron QW716AA#ABA                     | 1         | 0.88%   |
| MSI US PIO PRO AP241                     | 1         | 0.88%   |
| MSI MS-7B48                              | 1         | 0.88%   |
| MSI MS-7971                              | 1         | 0.88%   |
| MSI MS-7817                              | 1         | 0.88%   |
| MSI GF65 Thin 10SDR                      | 1         | 0.88%   |
| MSI Cubi N JSL (MS-B0A1)                 | 1         | 0.88%   |
| Lenovo Yoga 910-13IKB 80VF               | 1         | 0.88%   |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 0.88%   |
| Lenovo ThinkPad T410 2516ADU             | 1         | 0.88%   |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 0.88%   |
| Lenovo ThinkCentre M91p 7033CG1          | 1         | 0.88%   |
| Lenovo ThinkCentre M58p 6136A66          | 1         | 0.88%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 0.88%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS  | 1         | 0.88%   |
| Lenovo G50-45 80E3                       | 1         | 0.88%   |
| HP Stream Laptop 14-CB1xxx               | 1         | 0.88%   |
| HP ProBook 6560b                         | 1         | 0.88%   |
| HP ProBook 6450b                         | 1         | 0.88%   |
| HP ProBook 450 G5                        | 1         | 0.88%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 0.88%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 0.88%   |
| HP Notebook                              | 1         | 0.88%   |
| HP Laptop 15-dy1xxx                      | 1         | 0.88%   |
| HP Laptop 15-dw0xxx                      | 1         | 0.88%   |
| HP Laptop 14-dk1xxx                      | 1         | 0.88%   |
| HP ENVY Laptop 17m-bw0xxx                | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 7         | 6.14%   |
| HP Compaq            | 5         | 4.39%   |
| Dell OptiPlex        | 4         | 3.51%   |
| Toshiba Satellite    | 3         | 2.63%   |
| MSI Cubi             | 3         | 2.63%   |
| Lenovo ThinkPad      | 3         | 2.63%   |
| Intel SKYBAY         | 3         | 2.63%   |
| HP ProBook           | 3         | 2.63%   |
| HP Laptop            | 3         | 2.63%   |
| HP ENVY              | 3         | 2.63%   |
| Dell Vostro          | 3         | 2.63%   |
| Dell Latitude        | 3         | 2.63%   |
| Acer Aspire          | 3         | 2.63%   |
| RPi Raspberry        | 2         | 1.75%   |
| Lenovo Yoga          | 2         | 1.75%   |
| Lenovo ThinkCentre   | 2         | 1.75%   |
| HP Pavilion          | 2         | 1.75%   |
| HP EliteDesk         | 2         | 1.75%   |
| Gigabyte X570        | 2         | 1.75%   |
| ASUS TUF             | 2         | 1.75%   |
| ASUS ROG             | 2         | 1.75%   |
| ASRock Q1900M        | 2         | 1.75%   |
| ASRock B450M-HDV     | 2         | 1.75%   |
| ASRock 945GCM-S      | 2         | 1.75%   |
| Acer Swift           | 2         | 1.75%   |
| TUXEDO Aura          | 1         | 0.88%   |
| Sony VPCEA36FX       | 1         | 0.88%   |
| Sony VGN-CS320J      | 1         | 0.88%   |
| Pegatron QW716AA#ABA | 1         | 0.88%   |
| MSI US               | 1         | 0.88%   |
| MSI MS-7B48          | 1         | 0.88%   |
| MSI MS-7971          | 1         | 0.88%   |
| MSI MS-7817          | 1         | 0.88%   |
| MSI GF65             | 1         | 0.88%   |
| Lenovo IdeaPad       | 1         | 0.88%   |
| Lenovo IdeaCentre    | 1         | 0.88%   |
| Lenovo G50-45        | 1         | 0.88%   |
| HP Stream            | 1         | 0.88%   |
| HP Notebook          | 1         | 0.88%   |
| HP EliteBook         | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 16        | 14.04%  |
| 2018    | 14        | 12.28%  |
| 2011    | 13        | 11.4%   |
| 2020    | 9         | 7.89%   |
| 2014    | 9         | 7.89%   |
| 2015    | 8         | 7.02%   |
| 2016    | 6         | 5.26%   |
| 2012    | 6         | 5.26%   |
| 2008    | 6         | 5.26%   |
| 2021    | 5         | 4.39%   |
| 2010    | 5         | 4.39%   |
| 2017    | 4         | 3.51%   |
| 2013    | 4         | 3.51%   |
| 2009    | 3         | 2.63%   |
| 2006    | 2         | 1.75%   |
| Unknown | 2         | 1.75%   |
| 2007    | 1         | 0.88%   |
| 2005    | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 54        | 47.37%  |
| Desktop        | 52        | 45.61%  |
| All in one     | 4         | 3.51%   |
| System on chip | 2         | 1.75%   |
| Convertible    | 1         | 0.88%   |
| Mini pc        | 1         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 107       | 93.04%  |
| Enabled  | 8         | 6.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 37        | 31.36%  |
| 3.01-4.0    | 24        | 20.34%  |
| 8.01-16.0   | 23        | 19.49%  |
| 16.01-24.0  | 17        | 14.41%  |
| 32.01-64.0  | 7         | 5.93%   |
| 1.01-2.0    | 5         | 4.24%   |
| 24.01-32.0  | 3         | 2.54%   |
| 64.01-256.0 | 2         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 66        | 47.48%  |
| 2.01-3.0  | 26        | 18.71%  |
| 3.01-4.0  | 20        | 14.39%  |
| 4.01-8.0  | 15        | 10.79%  |
| 0.51-1.0  | 9         | 6.47%   |
| 8.01-16.0 | 3         | 2.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 70        | 57.38%  |
| 2      | 28        | 22.95%  |
| 3      | 15        | 12.3%   |
| 4      | 5         | 4.1%    |
| 0      | 2         | 1.64%   |
| 6      | 1         | 0.82%   |
| 5      | 1         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 53.04%  |
| Yes       | 54        | 46.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 87.72%  |
| No        | 14        | 12.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 75.86%  |
| No        | 28        | 24.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 59.83%  |
| No        | 47        | 40.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Puerto Rico | 114       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San Juan      | 50        | 40%     |
| Bayamón      | 22        | 17.6%   |
| Carolina      | 9         | 7.2%    |
| Ponce         | 5         | 4%      |
| Cayey         | 4         | 3.2%    |
| Caguas        | 4         | 3.2%    |
| Aguadilla     | 3         | 2.4%    |
| Vega Alta     | 2         | 1.6%    |
| Sabana Grande | 2         | 1.6%    |
| Mayagüez     | 2         | 1.6%    |
| Lares         | 2         | 1.6%    |
| Guayama       | 2         | 1.6%    |
| Dorado        | 2         | 1.6%    |
| San Sebastian | 1         | 0.8%    |
| Rio Grande    | 1         | 0.8%    |
| Patillas      | 1         | 0.8%    |
| Morovis       | 1         | 0.8%    |
| Maunabo       | 1         | 0.8%    |
| Las Piedras   | 1         | 0.8%    |
| Humacao       | 1         | 0.8%    |
| Hatillo       | 1         | 0.8%    |
| Gurabo        | 1         | 0.8%    |
| Garrochales   | 1         | 0.8%    |
| Fajardo       | 1         | 0.8%    |
| Ensenada      | 1         | 0.8%    |
| Coamo         | 1         | 0.8%    |
| Catano        | 1         | 0.8%    |
| Barceloneta   | 1         | 0.8%    |
| Arecibo       | 1         | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 33        | 74     | 20%     |
| Seagate                     | 20        | 38     | 12.12%  |
| Toshiba                     | 15        | 18     | 9.09%   |
| Samsung Electronics         | 11        | 20     | 6.67%   |
| Hitachi                     | 9         | 24     | 5.45%   |
| Crucial                     | 9         | 13     | 5.45%   |
| Unknown                     | 8         | 12     | 4.85%   |
| SanDisk                     | 7         | 7      | 4.24%   |
| China                       | 5         | 8      | 3.03%   |
| A-DATA Technology           | 5         | 10     | 3.03%   |
| SK hynix                    | 3         | 4      | 1.82%   |
| Silicon Motion              | 3         | 3      | 1.82%   |
| Micron/Crucial Technology   | 3         | 4      | 1.82%   |
| External                    | 3         | 4      | 1.82%   |
| TDAS                        | 2         | 10     | 1.21%   |
| SABRENT                     | 2         | 3      | 1.21%   |
| PNY                         | 2         | 2      | 1.21%   |
| Phison                      | 2         | 2      | 1.21%   |
| LITEONIT                    | 2         | 2      | 1.21%   |
| Intel                       | 2         | 3      | 1.21%   |
| WD MediaMax                 | 1         | 3      | 0.61%   |
| W800SH                      | 1         | 1      | 0.61%   |
| USB3.0                      | 1         | 1      | 0.61%   |
| Team                        | 1         | 1      | 0.61%   |
| SPCC                        | 1         | 1      | 0.61%   |
| Patriot                     | 1         | 1      | 0.61%   |
| Micron Technology           | 1         | 1      | 0.61%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.61%   |
| MaxDigital                  | 1         | 1      | 0.61%   |
| Kingston                    | 1         | 1      | 0.61%   |
| KingSpec                    | 1         | 1      | 0.61%   |
| JMicron Technology          | 1         | 4      | 0.61%   |
| INTEL SS                    | 1         | 1      | 0.61%   |
| HGST                        | 1         | 1      | 0.61%   |
| Axiom                       | 1         | 3      | 0.61%   |
| Argon                       | 1         | 1      | 0.61%   |
| Apple                       | 1         | 1      | 0.61%   |
| addlink                     | 1         | 1      | 0.61%   |
| Unknown                     | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB        | 5         | 2.76%   |
| WDC WD5000LPVT-22G33T0 500GB        | 3         | 1.66%   |
| Toshiba DT01ACA100 1TB              | 3         | 1.66%   |
| External USB3.0 500GB               | 3         | 1.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 1.1%    |
| WDC WDBNCE2500PNC 250GB SSD         | 2         | 1.1%    |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2         | 1.1%    |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 1.1%    |
| Unknown MMC Card  2GB               | 2         | 1.1%    |
| Toshiba MQ01ABD100 1TB              | 2         | 1.1%    |
| Toshiba MK3261GSYN 320GB            | 2         | 1.1%    |
| Toshiba DT01ACA050 500GB            | 2         | 1.1%    |
| TDAS TerraMaster 1TB                | 2         | 1.1%    |
| Seagate ST320DM001 HD322GJ 320GB    | 2         | 1.1%    |
| Seagate ST2000VM003-1CT164 2TB      | 2         | 1.1%    |
| Seagate Expansion 1TB               | 2         | 1.1%    |
| Samsung SSD 850 EVO 500GB           | 2         | 1.1%    |
| Samsung NVMe SSD Drive 500GB        | 2         | 1.1%    |
| SABRENT Disk 500GB                  | 2         | 1.1%    |
| Micron/Crucial NVMe SSD Drive 500GB | 2         | 1.1%    |
| Hitachi HTS547550A9E384 500GB       | 2         | 1.1%    |
| Crucial CT240M500SSD1 240GB         | 2         | 1.1%    |
| China SATA SSD 512GB                | 2         | 1.1%    |
| WDC WDBNCE0010PNC 1TB SSD           | 1         | 0.55%   |
| WDC WD7500BPVX-60JC3T0 752GB        | 1         | 0.55%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 0.55%   |
| WDC WD5000BPVT-75HXZT1 500GB        | 1         | 0.55%   |
| WDC WD40EZRZ-22GXCB0 4TB            | 1         | 0.55%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1         | 0.55%   |
| WDC WD2500BPVT-22ZEST0 250GB        | 1         | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1         | 0.55%   |
| WDC WD1600AAJS-00PSA0 160GB         | 1         | 0.55%   |
| WDC WD1500HLFS-01G6U1 150GB         | 1         | 0.55%   |
| WDC WD1200BEVS-75UST0 120GB         | 1         | 0.55%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 0.55%   |
| WDC WD10SPZX-22Z10T1 1TB            | 1         | 0.55%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 0.55%   |
| WDC WD10SPCX-75KHST0 1TB            | 1         | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.55%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 63     | 35.62%  |
| Seagate             | 20        | 38     | 27.4%   |
| Toshiba             | 14        | 17     | 19.18%  |
| Hitachi             | 9         | 24     | 12.33%  |
| Samsung Electronics | 1         | 1      | 1.37%   |
| MaxDigital          | 1         | 1      | 1.37%   |
| HGST                | 1         | 1      | 1.37%   |
| Apple               | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 13     | 20%     |
| Samsung Electronics | 7         | 11     | 15.56%  |
| WDC                 | 5         | 8      | 11.11%  |
| China               | 5         | 8      | 11.11%  |
| A-DATA Technology   | 5         | 10     | 11.11%  |
| SanDisk             | 3         | 3      | 6.67%   |
| PNY                 | 2         | 2      | 4.44%   |
| LITEONIT            | 2         | 2      | 4.44%   |
| W800SH              | 1         | 1      | 2.22%   |
| USB3.0              | 1         | 1      | 2.22%   |
| Patriot             | 1         | 1      | 2.22%   |
| Micron Technology   | 1         | 1      | 2.22%   |
| KingSpec            | 1         | 1      | 2.22%   |
| INTEL SS            | 1         | 1      | 2.22%   |
| Argon               | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 66        | 146    | 43.71%  |
| SSD     | 41        | 64     | 27.15%  |
| NVMe    | 30        | 44     | 19.87%  |
| MMC     | 8         | 11     | 5.3%    |
| Unknown | 6         | 22     | 3.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 95        | 210    | 65.97%  |
| NVMe | 27        | 37     | 18.75%  |
| SAS  | 14        | 29     | 9.72%   |
| MMC  | 8         | 11     | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 108    | 55.36%  |
| 0.51-1.0   | 36        | 72     | 32.14%  |
| 1.01-2.0   | 9         | 20     | 8.04%   |
| 3.01-4.0   | 4         | 9      | 3.57%   |
| 2.01-3.0   | 1         | 1      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 29        | 21.01%  |
| 101-250        | 29        | 21.01%  |
| 501-1000       | 24        | 17.39%  |
| 1-20           | 16        | 11.59%  |
| 1001-2000      | 11        | 7.97%   |
| More than 3000 | 9         | 6.52%   |
| 2001-3000      | 9         | 6.52%   |
| 51-100         | 4         | 2.9%    |
| Unknown        | 4         | 2.9%    |
| 21-50          | 3         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 52        | 36.62%  |
| 21-50     | 26        | 18.31%  |
| 101-250   | 15        | 10.56%  |
| 51-100    | 14        | 9.86%   |
| 251-500   | 12        | 8.45%   |
| 501-1000  | 10        | 7.04%   |
| 1001-2000 | 7         | 4.93%   |
| Unknown   | 4         | 2.82%   |
| 2001-3000 | 2         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 7.14%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 7.14%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 7.14%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 7.14%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 7.14%   |
| Seagate ST320DM001 HD322GJ 320GB                 | 1         | 1      | 7.14%   |
| Seagate ST2000VM003-1CT164 2TB                   | 1         | 1      | 7.14%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 1      | 7.14%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 7.14%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 7.14%   |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 7.14%   |
| Hitachi HTS543232L9A300 320GB                    | 1         | 1      | 7.14%   |
| A-DATA Technology SU630 240GB SSD                | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 33.33%  |
| Hitachi             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 50%     |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Toshiba | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 66.67%  |
| SSD  | 3         | 3      | 25%     |
| NVMe | 1         | 1      | 8.33%   |

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
| Detected | 85        | 234    | 69.11%  |
| Works    | 26        | 39     | 21.14%  |
| Malfunc  | 12        | 14     | 9.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 80        | 59.7%   |
| AMD                          | 25        | 18.66%  |
| SanDisk                      | 5         | 3.73%   |
| Silicon Motion               | 4         | 2.99%   |
| Samsung Electronics          | 4         | 2.99%   |
| Phison Electronics           | 4         | 2.99%   |
| SK hynix                     | 3         | 2.24%   |
| Micron/Crucial Technology    | 3         | 2.24%   |
| Nvidia                       | 2         | 1.49%   |
| Toshiba America Info Systems | 1         | 0.75%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.75%   |
| Kingston Technology Company  | 1         | 0.75%   |
| ASMedia Technology           | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 13.21%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9         | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 4.4%    |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 3.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 2.52%   |
| Phison E12 NVMe Controller                                                              | 4         | 2.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 2.52%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 1.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.89%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.89%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 1.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.26%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.26%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.26%   |
| AMD FCH IDE Controller                                                                  | 2         | 1.26%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.63%   |
| SK hynix BC511                                                                          | 1         | 0.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.63%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.63%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1         | 0.63%   |
| Nvidia CK804 IDE                                                                        | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 83        | 58.04%  |
| NVMe | 27        | 18.88%  |
| IDE  | 18        | 12.59%  |
| RAID | 15        | 10.49%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 85        | 74.56%  |
| AMD    | 27        | 23.68%  |
| ARM    | 2         | 1.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 2.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 2.63%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 2.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 2.63%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 3         | 2.63%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.75%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 2         | 1.75%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.75%   |
| ARM Processor                               | 2         | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.75%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.75%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 2         | 1.75%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.88%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.88%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.88%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.88%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.88%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.88%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.88%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 0.88%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.88%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.88%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 0.88%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.88%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.88%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 20.18%  |
| Intel Celeron           | 15        | 13.16%  |
| Intel Core i7           | 14        | 12.28%  |
| Intel Core i3           | 11        | 9.65%   |
| Other                   | 7         | 6.14%   |
| Intel Core 2 Duo        | 7         | 6.14%   |
| AMD Ryzen 5             | 7         | 6.14%   |
| Intel Pentium Silver    | 4         | 3.51%   |
| AMD Ryzen 7             | 4         | 3.51%   |
| AMD Ryzen 3             | 4         | 3.51%   |
| AMD A8                  | 4         | 3.51%   |
| Intel Pentium Dual-Core | 2         | 1.75%   |
| Intel Pentium           | 2         | 1.75%   |
| AMD A6                  | 2         | 1.75%   |
| Intel Genuine           | 1         | 0.88%   |
| Intel Core 2            | 1         | 0.88%   |
| AMD Ryzen Threadripper  | 1         | 0.88%   |
| AMD G                   | 1         | 0.88%   |
| AMD FX                  | 1         | 0.88%   |
| AMD Athlon 64 X2        | 1         | 0.88%   |
| AMD Athlon              | 1         | 0.88%   |
| AMD A10                 | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 50.88%  |
| 4      | 36        | 31.58%  |
| 6      | 11        | 9.65%   |
| 8      | 5         | 4.39%   |
| 1      | 3         | 2.63%   |
| 16     | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 114       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 64        | 56.14%  |
| 1      | 50        | 43.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 111       | 96.52%  |
| Unknown        | 3         | 2.61%   |
| 32-bit         | 1         | 0.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 21.67%  |
| 0x206a7    | 10        | 8.33%   |
| 0x306c3    | 6         | 5%      |
| 0x806e9    | 5         | 4.17%   |
| 0x306a9    | 5         | 4.17%   |
| 0x706a1    | 4         | 3.33%   |
| 0x20655    | 4         | 3.33%   |
| 0x1067a    | 4         | 3.33%   |
| 0xa0671    | 3         | 2.5%    |
| 0x806ec    | 3         | 2.5%    |
| 0x806ea    | 3         | 2.5%    |
| 0x30678    | 3         | 2.5%    |
| 0x08108109 | 3         | 2.5%    |
| 0x06001119 | 3         | 2.5%    |
| 0x906ea    | 2         | 1.67%   |
| 0x6fd      | 2         | 1.67%   |
| 0x406e3    | 2         | 1.67%   |
| 0x306d4    | 2         | 1.67%   |
| 0x08701013 | 2         | 1.67%   |
| 0x06003106 | 2         | 1.67%   |
| 0xa0652    | 1         | 0.83%   |
| 0x906ed    | 1         | 0.83%   |
| 0x906e9    | 1         | 0.83%   |
| 0x906c0    | 1         | 0.83%   |
| 0x806c1    | 1         | 0.83%   |
| 0x706e5    | 1         | 0.83%   |
| 0x6fb      | 1         | 0.83%   |
| 0x6e8      | 1         | 0.83%   |
| 0x506e3    | 1         | 0.83%   |
| 0x506c9    | 1         | 0.83%   |
| 0x406c4    | 1         | 0.83%   |
| 0x406c3    | 1         | 0.83%   |
| 0x40651    | 1         | 0.83%   |
| 0x30679    | 1         | 0.83%   |
| 0x20652    | 1         | 0.83%   |
| 0x10676    | 1         | 0.83%   |
| 0x08600106 | 1         | 0.83%   |
| 0x08600104 | 1         | 0.83%   |
| 0x0810100b | 1         | 0.83%   |
| 0x08101007 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 14.04%  |
| SandyBridge   | 11        | 9.65%   |
| Penryn        | 8         | 7.02%   |
| Haswell       | 8         | 7.02%   |
| Zen+          | 6         | 5.26%   |
| Zen 2         | 6         | 5.26%   |
| Silvermont    | 6         | 5.26%   |
| Westmere      | 5         | 4.39%   |
| Skylake       | 5         | 4.39%   |
| IvyBridge     | 5         | 4.39%   |
| Goldmont plus | 5         | 4.39%   |
| Zen           | 4         | 3.51%   |
| Piledriver    | 4         | 3.51%   |
| Core          | 4         | 3.51%   |
| Icelake       | 3         | 2.63%   |
| Unknown       | 3         | 2.63%   |
| TigerLake     | 2         | 1.75%   |
| Steamroller   | 2         | 1.75%   |
| Broadwell     | 2         | 1.75%   |
| Zen 3         | 1         | 0.88%   |
| Tremont       | 1         | 0.88%   |
| Puma          | 1         | 0.88%   |
| P6            | 1         | 0.88%   |
| K8 Hammer     | 1         | 0.88%   |
| K10 Llano     | 1         | 0.88%   |
| Goldmont      | 1         | 0.88%   |
| CometLake     | 1         | 0.88%   |
| Bobcat        | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 77        | 61.11%  |
| AMD    | 26        | 20.63%  |
| Nvidia | 23        | 18.25%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 8.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 3.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.96%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.22%   |
| Intel HD Graphics 610                                                                    | 3         | 2.22%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.22%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 1.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.48%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 1.48%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 2         | 1.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.48%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.48%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.48%   |
| Intel HD Graphics 620                                                                    | 2         | 1.48%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.48%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 1.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.48%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 2         | 1.48%   |
| AMD Renoir                                                                               | 2         | 1.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.48%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 1.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.48%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.74%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.74%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 65        | 56.03%  |
| 1 x AMD            | 22        | 18.97%  |
| 1 x Nvidia         | 12        | 10.34%  |
| Intel + Nvidia     | 8         | 6.9%    |
| Intel + AMD        | 3         | 2.59%   |
| Other              | 2         | 1.72%   |
| Intel + 2 x Nvidia | 2         | 1.72%   |
| 2 x Nvidia         | 1         | 0.86%   |
| 2 x AMD            | 1         | 0.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 99        | 83.9%   |
| Proprietary | 13        | 11.02%  |
| Unknown     | 6         | 5.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 61.98%  |
| 0.01-0.5   | 12        | 9.92%   |
| 1.01-2.0   | 10        | 8.26%   |
| 0.51-1.0   | 10        | 8.26%   |
| 3.01-4.0   | 6         | 4.96%   |
| 5.01-6.0   | 4         | 3.31%   |
| 8.01-16.0  | 2         | 1.65%   |
| 7.01-8.0   | 1         | 0.83%   |
| 2.01-3.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 14        | 11.02%  |
| LG Display              | 10        | 7.87%   |
| Goldstar                | 10        | 7.87%   |
| Chimei Innolux          | 9         | 7.09%   |
| Dell                    | 8         | 6.3%    |
| AU Optronics            | 7         | 5.51%   |
| BOE                     | 6         | 4.72%   |
| Acer                    | 6         | 4.72%   |
| Hewlett-Packard         | 5         | 3.94%   |
| Vizio                   | 4         | 3.15%   |
| ViewSonic               | 4         | 3.15%   |
| Sony                    | 4         | 3.15%   |
| Apple                   | 4         | 3.15%   |
| AOC                     | 4         | 3.15%   |
| Sceptre Tech            | 3         | 2.36%   |
| PANDA                   | 3         | 2.36%   |
| Gateway                 | 3         | 2.36%   |
| Element                 | 3         | 2.36%   |
| VIZ                     | 2         | 1.57%   |
| Tech Concepts           | 2         | 1.57%   |
| RTK                     | 2         | 1.57%   |
| eMachines               | 2         | 1.57%   |
| Ancor Communications    | 2         | 1.57%   |
| Unknown                 | 1         | 0.79%   |
| UGD                     | 1         | 0.79%   |
| Seiki                   | 1         | 0.79%   |
| ONN                     | 1         | 0.79%   |
| MTK                     | 1         | 0.79%   |
| MStar                   | 1         | 0.79%   |
| Lenovo                  | 1         | 0.79%   |
| InnoLux Display         | 1         | 0.79%   |
| Chi Mei Optoelectronics | 1         | 0.79%   |
| ASUSTek Computer        | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 3.76%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch            | 3         | 2.26%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 3         | 2.26%   |
| Element ELEFW328 ELE1366 1366x768 700x400mm 31.7-inch                  | 3         | 2.26%   |
| VIZ LCD Monitor M551d-A2R                                              | 2         | 1.5%    |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch          | 2         | 1.5%    |
| Sony TV  *00 SNY4B04 3840x2160                                         | 2         | 1.5%    |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch      | 2         | 1.5%    |
| Gateway LCD Monitor FHX2300                                            | 2         | 1.5%    |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                  | 2         | 1.5%    |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 2         | 1.5%    |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch                | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.5%    |
| Acer LCD Monitor G236HL 5760x1080                                      | 2         | 1.5%    |
| Vizio M551d-A2R VIZ1006 1920x1080 1430x800mm 64.5-inch                 | 1         | 0.75%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                     | 1         | 0.75%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.75%   |
| Vizio D43f-F1 VIZ1027 1920x1080 940x529mm 42.5-inch                    | 1         | 0.75%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch               | 1         | 0.75%   |
| ViewSonic VA1930wm VSC171F 1440x900 410x260mm 19.1-inch                | 1         | 0.75%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                            | 1         | 0.75%   |
| UGD Artist 156 UGD1501 1920x1080 293x165mm 13.2-inch                   | 1         | 0.75%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                             | 1         | 0.75%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                             | 1         | 0.75%   |
| Sony TV SNYEA01 1920x1080                                              | 1         | 0.75%   |
| Sony TV SNY4502 1920x1080                                              | 1         | 0.75%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                    | 1         | 0.75%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch       | 1         | 0.75%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch         | 1         | 0.75%   |
| Sceptre Tech E27 SPT0ABF 1920x1080 521x293mm 23.5-inch                 | 1         | 0.75%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 800x330mm 34.1-inch      | 1         | 0.75%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1210x680mm 54.6-inch | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 52        | 44.44%  |
| 1366x768 (WXGA)    | 24        | 20.51%  |
| 3840x2160 (4K)     | 11        | 9.4%    |
| 1440x900 (WXGA+)   | 6         | 5.13%   |
| 1600x900 (HD+)     | 5         | 4.27%   |
| 1280x800 (WXGA)    | 4         | 3.42%   |
| 1280x1024 (SXGA)   | 3         | 2.56%   |
| 5760x1080          | 2         | 1.71%   |
| 2560x1080          | 2         | 1.71%   |
| Unknown            | 2         | 1.71%   |
| 3840x1080          | 1         | 0.85%   |
| 3440x1440          | 1         | 0.85%   |
| 3200x1800 (QHD+)   | 1         | 0.85%   |
| 2560x1440 (QHD)    | 1         | 0.85%   |
| 1680x1050 (WSXGA+) | 1         | 0.85%   |
| 1280x720 (HD)      | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 21.95%  |
| 21      | 14        | 11.38%  |
| 23      | 10        | 8.13%   |
| 17      | 8         | 6.5%    |
| 14      | 8         | 6.5%    |
| 72      | 7         | 5.69%   |
| 31      | 6         | 4.88%   |
| 19      | 6         | 4.88%   |
| 13      | 6         | 4.88%   |
| Unknown | 5         | 4.07%   |
| 27      | 4         | 3.25%   |
| 20      | 4         | 3.25%   |
| 34      | 3         | 2.44%   |
| 18      | 3         | 2.44%   |
| 24      | 2         | 1.63%   |
| 11      | 2         | 1.63%   |
| 84      | 1         | 0.81%   |
| 64      | 1         | 0.81%   |
| 52      | 1         | 0.81%   |
| 49      | 1         | 0.81%   |
| 32      | 1         | 0.81%   |
| 26      | 1         | 0.81%   |
| 25      | 1         | 0.81%   |
| 22      | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 30.83%  |
| 401-500     | 25        | 20.83%  |
| 501-600     | 17        | 14.17%  |
| 351-400     | 9         | 7.5%    |
| 1501-2000   | 8         | 6.67%   |
| 601-700     | 6         | 5%      |
| 201-300     | 6         | 5%      |
| Unknown     | 5         | 4.17%   |
| 701-800     | 4         | 3.33%   |
| 1001-1500   | 3         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 77.78%  |
| 16/10   | 12        | 11.11%  |
| Unknown | 5         | 4.63%   |
| 5/4     | 4         | 3.7%    |
| 21/9    | 3         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 22.31%  |
| 201-250        | 23        | 19.01%  |
| 151-200        | 14        | 11.57%  |
| 81-90          | 12        | 9.92%   |
| More than 1000 | 10        | 8.26%   |
| 351-500        | 10        | 8.26%   |
| 121-130        | 5         | 4.13%   |
| Unknown        | 5         | 4.13%   |
| 301-350        | 4         | 3.31%   |
| 141-150        | 4         | 3.31%   |
| 71-80          | 2         | 1.65%   |
| 51-60          | 2         | 1.65%   |
| 251-300        | 2         | 1.65%   |
| 131-140        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 43        | 36.44%  |
| 51-100        | 37        | 31.36%  |
| 121-160       | 19        | 16.1%   |
| 1-50          | 10        | 8.47%   |
| Unknown       | 5         | 4.24%   |
| More than 240 | 2         | 1.69%   |
| 161-240       | 2         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 91        | 77.12%  |
| 2     | 21        | 17.8%   |
| 0     | 4         | 3.39%   |
| 3     | 2         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 38.71%  |
| Intel                    | 62        | 33.33%  |
| Qualcomm Atheros         | 15        | 8.06%   |
| Broadcom                 | 8         | 4.3%    |
| Ralink Technology        | 5         | 2.69%   |
| NetGear                  | 5         | 2.69%   |
| Marvell Technology Group | 3         | 1.61%   |
| Broadcom Limited         | 3         | 1.61%   |
| TP-Link                  | 2         | 1.08%   |
| Samsung Electronics      | 2         | 1.08%   |
| Nvidia                   | 2         | 1.08%   |
| ASIX Electronics         | 2         | 1.08%   |
| Ralink                   | 1         | 0.54%   |
| Gemtek                   | 1         | 0.54%   |
| Dell                     | 1         | 0.54%   |
| Belkin Components        | 1         | 0.54%   |
| Aquantia                 | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 21.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.79%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 3.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.37%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3         | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.42%   |
| Intel Wireless 7265                                               | 3         | 1.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.95%   |
| Realtek 802.11n                                                   | 2         | 0.95%   |
| Realtek 802.11ac NIC                                              | 2         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.95%   |
| NetGear LB1120-100NAS                                             | 2         | 0.95%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.95%   |
| Intel Wireless 3160                                               | 2         | 0.95%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.95%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 2         | 0.95%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.95%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.95%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 2         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.47%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 40.59%  |
| Realtek Semiconductor | 25        | 24.75%  |
| Qualcomm Atheros      | 12        | 11.88%  |
| Broadcom              | 7         | 6.93%   |
| Ralink Technology     | 5         | 4.95%   |
| NetGear               | 3         | 2.97%   |
| TP-Link               | 2         | 1.98%   |
| Broadcom Limited      | 2         | 1.98%   |
| Ralink                | 1         | 0.99%   |
| Gemtek                | 1         | 0.99%   |
| Dell                  | 1         | 0.99%   |
| Belkin Components     | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 7         | 6.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 5         | 4.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 4         | 3.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4         | 3.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4         | 3.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 3         | 2.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 3         | 2.83%   |
| Intel Wireless 7265                                        | 3         | 2.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 1.89%   |
| Realtek 802.11n                                            | 2         | 1.89%   |
| Realtek 802.11ac NIC                                       | 2         | 1.89%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 2         | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 1.89%   |
| Intel Wireless 8265 / 8275                                 | 2         | 1.89%   |
| Intel Wireless 3160                                        | 2         | 1.89%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2         | 1.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 2         | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 1.89%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 2         | 1.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 2         | 1.89%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 2         | 1.89%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 2         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 1.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 0.94%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 0.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 0.94%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 0.94%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 0.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 0.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1         | 0.94%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 0.94%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                     | 1         | 0.94%   |
| Realtek RTL8187 Wireless Adapter                           | 1         | 0.94%   |
| Ralink RT2870 Wireless Adapter                             | 1         | 0.94%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 1         | 0.94%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 55.24%  |
| Intel                    | 28        | 26.67%  |
| Qualcomm Atheros         | 3         | 2.86%   |
| Marvell Technology Group | 3         | 2.86%   |
| Broadcom                 | 3         | 2.86%   |
| Samsung Electronics      | 2         | 1.9%    |
| Nvidia                   | 2         | 1.9%    |
| NetGear                  | 2         | 1.9%    |
| ASIX Electronics         | 2         | 1.9%    |
| Broadcom Limited         | 1         | 0.95%   |
| Aquantia                 | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 46        | 43.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 7.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 7.62%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 4.76%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 3.81%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 2.86%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.9%    |
| NetGear LB1120-100NAS                                                          | 2         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.95%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.95%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.95%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.95%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.95%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.95%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.95%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.95%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.95%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.95%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 0.95%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.95%   |
| ASIX AX88772B                                                                  | 1         | 0.95%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.95%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 53.19%  |
| WiFi     | 88        | 46.81%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 53.28%  |
| Ethernet | 57        | 46.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 50.86%  |
| 1     | 51        | 43.97%  |
| 3     | 3         | 2.59%   |
| 0     | 3         | 2.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 90.35%  |
| Yes  | 11        | 9.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 47.95%  |
| Realtek Semiconductor           | 8         | 10.96%  |
| Cambridge Silicon Radio         | 7         | 9.59%   |
| Qualcomm Atheros Communications | 5         | 6.85%   |
| Lite-On Technology              | 3         | 4.11%   |
| Apple                           | 3         | 4.11%   |
| Foxconn / Hon Hai               | 2         | 2.74%   |
| Dell                            | 2         | 2.74%   |
| Broadcom                        | 2         | 2.74%   |
| Toshiba                         | 1         | 1.37%   |
| IMC Networks                    | 1         | 1.37%   |
| Hewlett-Packard                 | 1         | 1.37%   |
| Dynex                           | 1         | 1.37%   |
| Belkin Components               | 1         | 1.37%   |
| Alps Electric                   | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 10        | 13.7%   |
| Intel AX200 Bluetooth                                                               | 7         | 9.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 9.59%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 6.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 6.85%   |
| Intel AX201 Bluetooth                                                               | 5         | 6.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 5.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 5.48%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.11%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.74%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.74%   |
| Broadcom Bluetooth Device                                                           | 2         | 2.74%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.74%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.37%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.37%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.37%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.37%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.37%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 1.37%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.37%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.37%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 1.37%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.37%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 84        | 58.74%  |
| AMD                                             | 28        | 19.58%  |
| Nvidia                                          | 19        | 13.29%  |
| Logitech                                        | 6         | 4.2%    |
| C-Media Electronics                             | 2         | 1.4%    |
| Nintendo                                        | 1         | 0.7%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.7%    |
| Kingston Technology                             | 1         | 0.7%    |
| Focusrite-Novation                              | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 6.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 6.29%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 5.71%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 2.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.29%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.29%   |
| Logitech EasyCall Speakerphone                                                                    | 3         | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.71%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.71%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.14%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 1.14%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.14%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.14%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.14%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 10        | 23.81%  |
| Samsung Electronics | 10        | 23.81%  |
| Unknown             | 7         | 16.67%  |
| Kingston            | 3         | 7.14%   |
| G.Skill             | 2         | 4.76%   |
| Crucial             | 2         | 4.76%   |
| Corsair             | 2         | 4.76%   |
| Silicon Power       | 1         | 2.38%   |
| Sesame              | 1         | 2.38%   |
| Ramaxel Technology  | 1         | 2.38%   |
| PNY                 | 1         | 2.38%   |
| Micron Technology   | 1         | 2.38%   |
| A-DATA Technology   | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 3         | 6.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 4.26%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s  | 2         | 4.26%   |
| Unknown RAM WPBS26D408SWC-8G 8192MB SODIMM DDR4 2667MT/s  | 1         | 2.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1         | 2.13%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1         | 2.13%   |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s  | 1         | 2.13%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 2.13%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 2.13%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 2.13%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 2.13%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1         | 2.13%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 2.13%   |
| SK hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s   | 1         | 2.13%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 2.13%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 2.13%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 2.13%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 1         | 2.13%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1         | 2.13%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s    | 1         | 2.13%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1         | 2.13%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 2.13%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 2.13%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 2.13%   |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 2.13%   |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 3200MT/s        | 1         | 2.13%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 2.13%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 1         | 2.13%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 2.13%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1         | 2.13%   |
| G.Skill RAM F3-10666CL9-8GBSQ 8GB DIMM DDR3 1333MT/s      | 1         | 2.13%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s     | 1         | 2.13%   |
| Crucial RAM BL16G26C16U4W.16FD 16GB DIMM DDR4 2667MT/s    | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 18        | 42.86%  |
| DDR3    | 16        | 38.1%   |
| SDRAM   | 3         | 7.14%   |
| LPDDR4  | 2         | 4.76%   |
| LPDDR3  | 1         | 2.38%   |
| DDR     | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 48.78%  |
| DIMM         | 20        | 48.78%  |
| Row Of Chips | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 47.62%  |
| 4096  | 15        | 35.71%  |
| 2048  | 5         | 11.9%   |
| 16384 | 2         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 27.91%  |
| 2667    | 9         | 20.93%  |
| 3200    | 5         | 11.63%  |
| 1333    | 3         | 6.98%   |
| Unknown | 3         | 6.98%   |
| 3600    | 2         | 4.65%   |
| 667     | 2         | 4.65%   |
| 3466    | 1         | 2.33%   |
| 3266    | 1         | 2.33%   |
| 2400    | 1         | 2.33%   |
| 2133    | 1         | 2.33%   |
| 1867    | 1         | 2.33%   |
| 1866    | 1         | 2.33%   |
| 800     | 1         | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| HP OfficeJet Pro 6960 | 1         | 50%     |
| Brother MFC-L2685DW   | 1         | 50%     |

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
| Chicony Electronics                    | 10        | 16.67%  |
| Microdia                               | 8         | 13.33%  |
| Ricoh                                  | 5         | 8.33%   |
| Logitech                               | 5         | 8.33%   |
| Realtek Semiconductor                  | 4         | 6.67%   |
| Acer                                   | 4         | 6.67%   |
| Sunplus Innovation Technology          | 3         | 5%      |
| Quanta                                 | 3         | 5%      |
| Apple                                  | 3         | 5%      |
| Suyin                                  | 2         | 3.33%   |
| Lite-On Technology                     | 2         | 3.33%   |
| IMC Networks                           | 2         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.33%   |
| Luxvisions Innotech Limited            | 1         | 1.67%   |
| Lenovo                                 | 1         | 1.67%   |
| Jieli Technology                       | 1         | 1.67%   |
| Goertek Electronics                    | 1         | 1.67%   |
| DJKANA19IDX53W                         | 1         | 1.67%   |
| Cubeternet                             | 1         | 1.67%   |
| Alpha Imaging Technology               | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Microdia Camera                                          | 4         | 6.67%   |
| Ricoh Integrated Webcam                                  | 3         | 5%      |
| Sunplus Integrated_Webcam_HD                             | 2         | 3.33%   |
| Realtek USB Camera                                       | 2         | 3.33%   |
| Chicony HD WebCam                                        | 2         | 3.33%   |
| Acer Lenovo EasyCamera                                   | 2         | 3.33%   |
| Suyin USB 2.0 Camera                                     | 1         | 1.67%   |
| Suyin Integrated_Webcam_HD                               | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                     | 1         | 1.67%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam | 1         | 1.67%   |
| Ricoh HD Webcam                                          | 1         | 1.67%   |
| Realtek Integrated Webcam HD                             | 1         | 1.67%   |
| Realtek Integrated Webcam                                | 1         | 1.67%   |
| Quanta HP Wide Vision HD Camera                          | 1         | 1.67%   |
| Quanta HP TrueVision HD Camera                           | 1         | 1.67%   |
| Quanta HD WebCam                                         | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_HD                     | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                            | 1         | 1.67%   |
| Microdia Hy-HD-Camera                                    | 1         | 1.67%   |
| Microdia Dell Integrated HD Webcam                       | 1         | 1.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera      | 1         | 1.67%   |
| Logitech Webcam Pro 9000                                 | 1         | 1.67%   |
| Logitech Webcam C310                                     | 1         | 1.67%   |
| Logitech Webcam C270                                     | 1         | 1.67%   |
| Logitech HD Pro Webcam C920                              | 1         | 1.67%   |
| Logitech CrystalCam                                      | 1         | 1.67%   |
| Lite-On HP Wide Vision HD Camera                         | 1         | 1.67%   |
| Lite-On HP HD Webcam                                     | 1         | 1.67%   |
| Lenovo Integrated Webcam [R5U877]                        | 1         | 1.67%   |
| Jieli USB PHY 2.0                                        | 1         | 1.67%   |
| IMC Networks UVC VGA Webcam                              | 1         | 1.67%   |
| IMC Networks Integrated Camera                           | 1         | 1.67%   |
| Goertek USB2.0 VGA UVC WebCam                            | 1         | 1.67%   |
| DJKANA19IDX53W HP Wide Vision HD Camera                  | 1         | 1.67%   |
| Cubeternet GL-UPC822 UVC WebCam                          | 1         | 1.67%   |
| Chicony TOSHIBA Web Camera - HD                          | 1         | 1.67%   |
| Chicony Toshiba Integrated Webcam                        | 1         | 1.67%   |
| Chicony Integrated HP HD Webcam                          | 1         | 1.67%   |
| Chicony HP Webcam                                        | 1         | 1.67%   |
| Chicony HP Truevision HD                                 | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 66.67%  |
| Synaptics             | 2         | 16.67%  |
| LighTuning Technology | 2         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 3         | 25%     |
| LighTuning EgisTec Touch Fingerprint Sensor       | 2         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                   | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner              | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 8.33%   |
| Unknown                                           | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 83        | 67.48%  |
| 1     | 35        | 28.46%  |
| 2     | 5         | 4.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 16        | 38.1%   |
| Fingerprint reader       | 12        | 28.57%  |
| Graphics card            | 6         | 14.29%  |
| Chipcard                 | 3         | 7.14%   |
| Communication controller | 2         | 4.76%   |
| Storage                  | 1         | 2.38%   |
| Net/ethernet             | 1         | 2.38%   |
| Multimedia controller    | 1         | 2.38%   |

