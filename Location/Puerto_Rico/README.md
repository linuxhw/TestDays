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

Total: 219

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 22        | 16.18%  |
| Ubuntu 18.04                 | 11        | 8.09%   |
| OpenMandriva 4.2             | 6         | 4.41%   |
| Ubuntu 22.04                 | 5         | 3.68%   |
| OpenMandriva 4.3             | 5         | 3.68%   |
| Ubuntu 21.10                 | 4         | 2.94%   |
| Ubuntu 20.10                 | 4         | 2.94%   |
| Zorin 16                     | 3         | 2.21%   |
| Manjaro                      | 3         | 2.21%   |
| Linux Mint 20.1              | 3         | 2.21%   |
| Linux Mint 19.3              | 3         | 2.21%   |
| KDE neon 20.04               | 3         | 2.21%   |
| Fedora 36                    | 3         | 2.21%   |
| BlackPanther 18.1            | 3         | 2.21%   |
| Zorin 15                     | 2         | 1.47%   |
| Xubuntu 20.04                | 2         | 1.47%   |
| Ubuntu 19.10                 | 2         | 1.47%   |
| ROSA R11                     | 2         | 1.47%   |
| ROSA R10                     | 2         | 1.47%   |
| Lubuntu 20.04                | 2         | 1.47%   |
| LMDE 4                       | 2         | 1.47%   |
| Linux Mint 20.3              | 2         | 1.47%   |
| Linux Mint 20.2              | 2         | 1.47%   |
| Linux Mint 20                | 2         | 1.47%   |
| Garuda Linux                 | 2         | 1.47%   |
| ArcoLinux Rolling            | 2         | 1.47%   |
| Xubuntu 20.10                | 1         | 0.74%   |
| Ubuntu Unity 20.04           | 1         | 0.74%   |
| Ubuntu MATE 20.04            | 1         | 0.74%   |
| Ubuntu Budgie 21.04          | 1         | 0.74%   |
| ROSA R9                      | 1         | 0.74%   |
| Pop!_OS 21.10                | 1         | 0.74%   |
| Pop!_OS 21.04                | 1         | 0.74%   |
| Pop!_OS 20.10                | 1         | 0.74%   |
| Pop!_OS 20.04                | 1         | 0.74%   |
| Pop!_OS 19.10                | 1         | 0.74%   |
| Peppermint 9                 | 1         | 0.74%   |
| Parrot 5.0                   | 1         | 0.74%   |
| Parrot 4.11                  | 1         | 0.74%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 46        | 35.66%  |
| OpenMandriva  | 13        | 10.08%  |
| Linux Mint    | 11        | 8.53%   |
| Zorin         | 5         | 3.88%   |
| Pop!_OS       | 5         | 3.88%   |
| Fedora        | 5         | 3.88%   |
| ROSA          | 4         | 3.1%    |
| Manjaro       | 4         | 3.1%    |
| Xubuntu       | 3         | 2.33%   |
| KDE neon      | 3         | 2.33%   |
| Debian        | 3         | 2.33%   |
| BlackPanther  | 3         | 2.33%   |
| Parrot        | 2         | 1.55%   |
| openSUSE      | 2         | 1.55%   |
| Lubuntu       | 2         | 1.55%   |
| LMDE          | 2         | 1.55%   |
| Garuda Linux  | 2         | 1.55%   |
| Endless       | 2         | 1.55%   |
| ArcoLinux     | 2         | 1.55%   |
| Arch          | 2         | 1.55%   |
| Ubuntu Unity  | 1         | 0.78%   |
| Ubuntu MATE   | 1         | 0.78%   |
| Ubuntu Budgie | 1         | 0.78%   |
| Peppermint    | 1         | 0.78%   |
| LinuxFX       | 1         | 0.78%   |
| EndeavourOS   | 1         | 0.78%   |
| Devuan        | 1         | 0.78%   |
| CentOS        | 1         | 0.78%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 6         | 3.8%    |
| 5.16.7-desktop-1omv4003        | 5         | 3.16%   |
| 5.4.0-58-generic               | 4         | 2.53%   |
| 5.8.0-59-generic               | 3         | 1.9%    |
| 5.11.0-38-generic              | 3         | 1.9%    |
| 4.15.0-43-generic              | 3         | 1.9%    |
| 5.8.18-1-MANJARO               | 2         | 1.27%   |
| 5.8.0-55-generic               | 2         | 1.27%   |
| 5.8.0-45-generic               | 2         | 1.27%   |
| 5.4.0-73-generic               | 2         | 1.27%   |
| 5.4.0-72-generic               | 2         | 1.27%   |
| 5.4.0-52-generic               | 2         | 1.27%   |
| 5.4.0-48-generic               | 2         | 1.27%   |
| 5.4.0-47-generic               | 2         | 1.27%   |
| 5.4.0-40-generic               | 2         | 1.27%   |
| 5.4.0-109-generic              | 2         | 1.27%   |
| 5.3.0-41-generic               | 2         | 1.27%   |
| 5.3.0-28-generic               | 2         | 1.27%   |
| 5.15.0-46-generic              | 2         | 1.27%   |
| 5.15.0-40-generic              | 2         | 1.27%   |
| 5.13.0-40-generic              | 2         | 1.27%   |
| 5.13.0-39-generic              | 2         | 1.27%   |
| 5.13.0-35-generic              | 2         | 1.27%   |
| 5.13.0-30-generic              | 2         | 1.27%   |
| 5.11.0-41-generic              | 2         | 1.27%   |
| 5.11.0-27-generic              | 2         | 1.27%   |
| 4.18.16-desktop-1bP            | 2         | 1.27%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2         | 1.27%   |
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
| 5.8.0-29-generic               | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 21.9%   |
| 5.8.0   | 14        | 10.22%  |
| 5.13.0  | 11        | 8.03%   |
| 4.15.0  | 10        | 7.3%    |
| 5.11.0  | 9         | 6.57%   |
| 5.3.0   | 6         | 4.38%   |
| 5.10.14 | 6         | 4.38%   |
| 5.16.7  | 5         | 3.65%   |
| 5.15.0  | 5         | 3.65%   |
| 5.10.0  | 3         | 2.19%   |
| 4.19.0  | 3         | 2.19%   |
| 4.18.0  | 3         | 2.19%   |
| 5.9.16  | 2         | 1.46%   |
| 5.8.18  | 2         | 1.46%   |
| 4.9.60  | 2         | 1.46%   |
| 4.18.16 | 2         | 1.46%   |
| 5.9.1   | 1         | 0.73%   |
| 5.8.5   | 1         | 0.73%   |
| 5.8.14  | 1         | 0.73%   |
| 5.6.14  | 1         | 0.73%   |
| 5.3.6   | 1         | 0.73%   |
| 5.3.18  | 1         | 0.73%   |
| 5.19.7  | 1         | 0.73%   |
| 5.19.12 | 1         | 0.73%   |
| 5.18.9  | 1         | 0.73%   |
| 5.18.6  | 1         | 0.73%   |
| 5.18.5  | 1         | 0.73%   |
| 5.18.15 | 1         | 0.73%   |
| 5.18.12 | 1         | 0.73%   |
| 5.18.0  | 1         | 0.73%   |
| 5.17.1  | 1         | 0.73%   |
| 5.15.59 | 1         | 0.73%   |
| 5.15.5  | 1         | 0.73%   |
| 5.14.8  | 1         | 0.73%   |
| 5.13.19 | 1         | 0.73%   |
| 5.12.4  | 1         | 0.73%   |
| 5.11.16 | 1         | 0.73%   |
| 5.11.13 | 1         | 0.73%   |
| 4.9.20  | 1         | 0.73%   |
| 4.9.0   | 1         | 0.73%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 22.56%  |
| 5.8     | 18        | 13.53%  |
| 5.13    | 12        | 9.02%   |
| 5.11    | 10        | 7.52%   |
| 4.15    | 10        | 7.52%   |
| 5.10    | 9         | 6.77%   |
| 5.3     | 8         | 6.02%   |
| 5.15    | 7         | 5.26%   |
| 5.16    | 5         | 3.76%   |
| 5.18    | 4         | 3.01%   |
| 4.9     | 4         | 3.01%   |
| 4.18    | 4         | 3.01%   |
| 5.9     | 3         | 2.26%   |
| 4.19    | 3         | 2.26%   |
| 5.19    | 2         | 1.5%    |
| 5.6     | 1         | 0.75%   |
| 5.17    | 1         | 0.75%   |
| 5.14    | 1         | 0.75%   |
| 5.12    | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 108       | 96.43%  |
| i686    | 2         | 1.79%   |
| aarch64 | 2         | 1.79%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 60        | 46.88%  |
| KDE5       | 25        | 19.53%  |
| X-Cinnamon | 9         | 7.03%   |
| XFCE       | 7         | 5.47%   |
| MATE       | 6         | 4.69%   |
| Unknown    | 6         | 4.69%   |
| LXQt       | 2         | 1.56%   |
| LXDE       | 2         | 1.56%   |
| KDE4       | 2         | 1.56%   |
| KDE        | 2         | 1.56%   |
| i3         | 2         | 1.56%   |
| Budgie     | 2         | 1.56%   |
| Unity      | 1         | 0.78%   |
| Deepin     | 1         | 0.78%   |
| Cinnamon   | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 101       | 87.83%  |
| Wayland | 13        | 11.3%   |
| Unknown | 1         | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 73        | 58.87%  |
| SDDM    | 18        | 14.52%  |
| GDM3    | 15        | 12.1%   |
| GDM     | 7         | 5.65%   |
| LightDM | 6         | 4.84%   |
| TDM     | 3         | 2.42%   |
| KDM     | 2         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 94        | 82.46%  |
| Unknown | 12        | 10.53%  |
| es_PR   | 5         | 4.39%   |
| C       | 2         | 1.75%   |
| es_ES   | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 64        | 54.24%  |
| EFI  | 54        | 45.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 86        | 72.88%  |
| Overlay | 17        | 14.41%  |
| Btrfs   | 8         | 6.78%   |
| Unknown | 5         | 4.24%   |
| Zfs     | 1         | 0.85%   |
| Xfs     | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 83        | 69.75%  |
| GPT     | 27        | 22.69%  |
| MBR     | 9         | 7.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 83.05%  |
| Yes       | 20        | 16.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 74.79%  |
| Yes       | 30        | 25.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 21        | 18.75%  |
| Dell                    | 20        | 17.86%  |
| Lenovo                  | 9         | 8.04%   |
| Gigabyte Technology     | 9         | 8.04%   |
| ASUSTek Computer        | 9         | 8.04%   |
| ASRock                  | 9         | 8.04%   |
| MSI                     | 8         | 7.14%   |
| Acer                    | 5         | 4.46%   |
| Apple                   | 4         | 3.57%   |
| Toshiba                 | 3         | 2.68%   |
| Intel                   | 3         | 2.68%   |
| Sony                    | 2         | 1.79%   |
| Raspberry Pi Foundation | 2         | 1.79%   |
| TUXEDO                  | 1         | 0.89%   |
| Pegatron                | 1         | 0.89%   |
| GPU Company             | 1         | 0.89%   |
| CompuLab                | 1         | 0.89%   |
| AZW                     | 1         | 0.89%   |
| AMI                     | 1         | 0.89%   |
| Alienware               | 1         | 0.89%   |
| Acidanthera             | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel SKYBAY                             | 3         | 2.68%   |
| Dell Vostro 3550                         | 3         | 2.68%   |
| RPi Raspberry Pi                         | 2         | 1.79%   |
| MSI Cubi N 8GL (MS-B171)                 | 2         | 1.79%   |
| ASRock Q1900M                            | 2         | 1.79%   |
| ASRock 945GCM-S                          | 2         | 1.79%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.89%   |
| Toshiba Satellite P755                   | 1         | 0.89%   |
| Toshiba Satellite L655                   | 1         | 0.89%   |
| Toshiba Satellite C55-C                  | 1         | 0.89%   |
| Sony VPCEA36FX                           | 1         | 0.89%   |
| Sony VGN-CS320J                          | 1         | 0.89%   |
| Pegatron QW716AA#ABA                     | 1         | 0.89%   |
| MSI US PIO PRO AP241                     | 1         | 0.89%   |
| MSI MS-7B48                              | 1         | 0.89%   |
| MSI MS-7971                              | 1         | 0.89%   |
| MSI MS-7817                              | 1         | 0.89%   |
| MSI GF65 Thin 10SDR                      | 1         | 0.89%   |
| MSI Cubi N JSL (MS-B0A1)                 | 1         | 0.89%   |
| Lenovo Yoga 910-13IKB 80VF               | 1         | 0.89%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 0.89%   |
| Lenovo ThinkPad T410 2516ADU             | 1         | 0.89%   |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 0.89%   |
| Lenovo ThinkCentre M91p 7033CG1          | 1         | 0.89%   |
| Lenovo ThinkCentre M58p 6136A66          | 1         | 0.89%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 0.89%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS  | 1         | 0.89%   |
| Lenovo G50-45 80E3                       | 1         | 0.89%   |
| HP Stream Laptop 14-CB1xxx               | 1         | 0.89%   |
| HP ProBook 6560b                         | 1         | 0.89%   |
| HP ProBook 6450b                         | 1         | 0.89%   |
| HP ProBook 450 G5                        | 1         | 0.89%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 0.89%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 0.89%   |
| HP Notebook                              | 1         | 0.89%   |
| HP Laptop 15-dy1xxx                      | 1         | 0.89%   |
| HP Laptop 15-dw0xxx                      | 1         | 0.89%   |
| HP Laptop 14-dk1xxx                      | 1         | 0.89%   |
| HP ENVY Laptop 17m-bw0xxx                | 1         | 0.89%   |
| HP ENVY Laptop 17-ce1xxx                 | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 7         | 6.25%   |
| HP Compaq            | 5         | 4.46%   |
| Dell OptiPlex        | 4         | 3.57%   |
| Toshiba Satellite    | 3         | 2.68%   |
| MSI Cubi             | 3         | 2.68%   |
| Lenovo ThinkPad      | 3         | 2.68%   |
| Intel SKYBAY         | 3         | 2.68%   |
| HP ProBook           | 3         | 2.68%   |
| HP Laptop            | 3         | 2.68%   |
| HP ENVY              | 3         | 2.68%   |
| Dell Vostro          | 3         | 2.68%   |
| Acer Aspire          | 3         | 2.68%   |
| RPi Raspberry        | 2         | 1.79%   |
| Lenovo ThinkCentre   | 2         | 1.79%   |
| HP Pavilion          | 2         | 1.79%   |
| HP EliteDesk         | 2         | 1.79%   |
| Gigabyte X570        | 2         | 1.79%   |
| Dell Latitude        | 2         | 1.79%   |
| ASUS TUF             | 2         | 1.79%   |
| ASUS ROG             | 2         | 1.79%   |
| ASRock Q1900M        | 2         | 1.79%   |
| ASRock B450M-HDV     | 2         | 1.79%   |
| ASRock 945GCM-S      | 2         | 1.79%   |
| Acer Swift           | 2         | 1.79%   |
| TUXEDO Aura          | 1         | 0.89%   |
| Sony VPCEA36FX       | 1         | 0.89%   |
| Sony VGN-CS320J      | 1         | 0.89%   |
| Pegatron QW716AA#ABA | 1         | 0.89%   |
| MSI US               | 1         | 0.89%   |
| MSI MS-7B48          | 1         | 0.89%   |
| MSI MS-7971          | 1         | 0.89%   |
| MSI MS-7817          | 1         | 0.89%   |
| MSI GF65             | 1         | 0.89%   |
| Lenovo Yoga          | 1         | 0.89%   |
| Lenovo IdeaPad       | 1         | 0.89%   |
| Lenovo IdeaCentre    | 1         | 0.89%   |
| Lenovo G50-45        | 1         | 0.89%   |
| HP Stream            | 1         | 0.89%   |
| HP Notebook          | 1         | 0.89%   |
| HP EliteBook         | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 16        | 14.29%  |
| 2018    | 14        | 12.5%   |
| 2011    | 12        | 10.71%  |
| 2020    | 9         | 8.04%   |
| 2014    | 9         | 8.04%   |
| 2015    | 7         | 6.25%   |
| 2016    | 6         | 5.36%   |
| 2012    | 6         | 5.36%   |
| 2008    | 6         | 5.36%   |
| 2021    | 5         | 4.46%   |
| 2010    | 5         | 4.46%   |
| 2017    | 4         | 3.57%   |
| 2013    | 4         | 3.57%   |
| 2009    | 3         | 2.68%   |
| 2006    | 2         | 1.79%   |
| Unknown | 2         | 1.79%   |
| 2007    | 1         | 0.89%   |
| 2005    | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 52        | 46.43%  |
| Notebook       | 52        | 46.43%  |
| All in one     | 4         | 3.57%   |
| System on chip | 2         | 1.79%   |
| Convertible    | 1         | 0.89%   |
| Mini pc        | 1         | 0.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 105       | 92.92%  |
| Enabled  | 8         | 7.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 36        | 31.03%  |
| 3.01-4.0    | 24        | 20.69%  |
| 8.01-16.0   | 23        | 19.83%  |
| 16.01-24.0  | 16        | 13.79%  |
| 32.01-64.0  | 7         | 6.03%   |
| 1.01-2.0    | 5         | 4.31%   |
| 24.01-32.0  | 3         | 2.59%   |
| 64.01-256.0 | 2         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 65        | 47.45%  |
| 2.01-3.0  | 26        | 18.98%  |
| 3.01-4.0  | 19        | 13.87%  |
| 4.01-8.0  | 15        | 10.95%  |
| 0.51-1.0  | 9         | 6.57%   |
| 8.01-16.0 | 3         | 2.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 70        | 58.33%  |
| 2      | 27        | 22.5%   |
| 3      | 15        | 12.5%   |
| 4      | 5         | 4.17%   |
| 6      | 1         | 0.83%   |
| 5      | 1         | 0.83%   |
| 0      | 1         | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 53.57%  |
| Yes       | 52        | 46.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 87.5%   |
| No        | 14        | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 75.44%  |
| No        | 28        | 24.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 59.13%  |
| No        | 47        | 40.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Puerto Rico | 112       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San Juan      | 49        | 39.84%  |
| Bayamón      | 21        | 17.07%  |
| Carolina      | 9         | 7.32%   |
| Ponce         | 5         | 4.07%   |
| Cayey         | 4         | 3.25%   |
| Caguas        | 4         | 3.25%   |
| Aguadilla     | 3         | 2.44%   |
| Vega Alta     | 2         | 1.63%   |
| Sabana Grande | 2         | 1.63%   |
| Mayagüez     | 2         | 1.63%   |
| Lares         | 2         | 1.63%   |
| Guayama       | 2         | 1.63%   |
| Dorado        | 2         | 1.63%   |
| San Sebastian | 1         | 0.81%   |
| Rio Grande    | 1         | 0.81%   |
| Patillas      | 1         | 0.81%   |
| Morovis       | 1         | 0.81%   |
| Maunabo       | 1         | 0.81%   |
| Las Piedras   | 1         | 0.81%   |
| Humacao       | 1         | 0.81%   |
| Hatillo       | 1         | 0.81%   |
| Gurabo        | 1         | 0.81%   |
| Garrochales   | 1         | 0.81%   |
| Fajardo       | 1         | 0.81%   |
| Ensenada      | 1         | 0.81%   |
| Coamo         | 1         | 0.81%   |
| Catano        | 1         | 0.81%   |
| Barceloneta   | 1         | 0.81%   |
| Arecibo       | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 33        | 74     | 20.25%  |
| Seagate                     | 20        | 38     | 12.27%  |
| Toshiba                     | 15        | 18     | 9.2%    |
| Samsung Electronics         | 11        | 20     | 6.75%   |
| Hitachi                     | 9         | 24     | 5.52%   |
| Crucial                     | 9         | 13     | 5.52%   |
| Unknown                     | 7         | 11     | 4.29%   |
| SanDisk                     | 7         | 7      | 4.29%   |
| China                       | 5         | 8      | 3.07%   |
| A-DATA Technology           | 5         | 10     | 3.07%   |
| SK hynix                    | 3         | 4      | 1.84%   |
| Silicon Motion              | 3         | 3      | 1.84%   |
| Micron/Crucial Technology   | 3         | 4      | 1.84%   |
| External                    | 3         | 4      | 1.84%   |
| TDAS                        | 2         | 10     | 1.23%   |
| SABRENT                     | 2         | 3      | 1.23%   |
| PNY                         | 2         | 2      | 1.23%   |
| Phison                      | 2         | 2      | 1.23%   |
| LITEONIT                    | 2         | 2      | 1.23%   |
| Intel                       | 2         | 3      | 1.23%   |
| WD MediaMax                 | 1         | 3      | 0.61%   |
| W800SH                      | 1         | 1      | 0.61%   |
| USB3.0                      | 1         | 1      | 0.61%   |
| Team                        | 1         | 1      | 0.61%   |
| SPCC                        | 1         | 1      | 0.61%   |
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

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB        | 5         | 2.79%   |
| WDC WD5000LPVT-22G33T0 500GB        | 3         | 1.68%   |
| Toshiba DT01ACA100 1TB              | 3         | 1.68%   |
| External USB3.0 480GB               | 3         | 1.68%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 1.12%   |
| WDC WDBNCE2500PNC 250GB SSD         | 2         | 1.12%   |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2         | 1.12%   |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 1.12%   |
| Unknown MMC Card  2GB               | 2         | 1.12%   |
| Toshiba MQ01ABD100 1TB              | 2         | 1.12%   |
| Toshiba MK3261GSYN 320GB            | 2         | 1.12%   |
| Toshiba DT01ACA050 500GB            | 2         | 1.12%   |
| TDAS TerraMaster 1TB                | 2         | 1.12%   |
| Seagate ST320DM001 HD322GJ 320GB    | 2         | 1.12%   |
| Seagate ST2000VM003-1CT164 2TB      | 2         | 1.12%   |
| Seagate Expansion 2TB               | 2         | 1.12%   |
| Samsung SSD 850 EVO 500GB           | 2         | 1.12%   |
| Samsung NVMe SSD Drive 500GB        | 2         | 1.12%   |
| SABRENT Disk 500GB                  | 2         | 1.12%   |
| Micron/Crucial NVMe SSD Drive 500GB | 2         | 1.12%   |
| Hitachi HTS547550A9E384 500GB       | 2         | 1.12%   |
| Crucial CT240M500SSD1 240GB         | 2         | 1.12%   |
| China SATA SSD 512GB                | 2         | 1.12%   |
| WDC WDBNCE0010PNC 1TB SSD           | 1         | 0.56%   |
| WDC WD7500BPVX-60JC3T0 752GB        | 1         | 0.56%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 0.56%   |
| WDC WD5000BPVT-75HXZT1 500GB        | 1         | 0.56%   |
| WDC WD40EZRZ-22GXCB0 4TB            | 1         | 0.56%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1         | 0.56%   |
| WDC WD2500BPVT-22ZEST0 250GB        | 1         | 0.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1         | 0.56%   |
| WDC WD1600AAJS-00PSA0 160GB         | 1         | 0.56%   |
| WDC WD1500HLFS-01G6U1 150GB         | 1         | 0.56%   |
| WDC WD1200BEVS-75UST0 120GB         | 1         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 0.56%   |
| WDC WD10SPZX-22Z10T1 1TB            | 1         | 0.56%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 0.56%   |
| WDC WD10SPCX-75KHST0 1TB            | 1         | 0.56%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.56%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 63     | 34.21%  |
| Seagate             | 20        | 38     | 26.32%  |
| Toshiba             | 14        | 17     | 18.42%  |
| Hitachi             | 9         | 24     | 11.84%  |
| SABRENT             | 2         | 3      | 2.63%   |
| USB3.0              | 1         | 1      | 1.32%   |
| Samsung Electronics | 1         | 1      | 1.32%   |
| MaxDigital          | 1         | 1      | 1.32%   |
| HGST                | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 13     | 20.93%  |
| Samsung Electronics | 7         | 11     | 16.28%  |
| WDC                 | 5         | 8      | 11.63%  |
| China               | 5         | 8      | 11.63%  |
| A-DATA Technology   | 5         | 10     | 11.63%  |
| SanDisk             | 3         | 3      | 6.98%   |
| PNY                 | 2         | 2      | 4.65%   |
| LITEONIT            | 2         | 2      | 4.65%   |
| W800SH              | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| INTEL SS            | 1         | 1      | 2.33%   |
| Argon               | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 68        | 150    | 45.03%  |
| SSD     | 40        | 62     | 26.49%  |
| NVMe    | 30        | 41     | 19.87%  |
| MMC     | 7         | 10     | 4.64%   |
| Unknown | 6         | 22     | 3.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 209    | 66.2%   |
| NVMe | 27        | 37     | 19.01%  |
| SAS  | 14        | 29     | 9.86%   |
| MMC  | 7         | 10     | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 109    | 54.39%  |
| 0.51-1.0   | 36        | 71     | 31.58%  |
| 1.01-2.0   | 11        | 22     | 9.65%   |
| 3.01-4.0   | 4         | 9      | 3.51%   |
| 2.01-3.0   | 1         | 1      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 29        | 21.32%  |
| 101-250        | 29        | 21.32%  |
| 501-1000       | 23        | 16.91%  |
| 1-20           | 15        | 11.03%  |
| 1001-2000      | 11        | 8.09%   |
| More than 3000 | 9         | 6.62%   |
| 2001-3000      | 9         | 6.62%   |
| 51-100         | 4         | 2.94%   |
| Unknown        | 4         | 2.94%   |
| 21-50          | 3         | 2.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 51        | 36.43%  |
| 21-50     | 26        | 18.57%  |
| 101-250   | 14        | 10%     |
| 51-100    | 14        | 10%     |
| 251-500   | 12        | 8.57%   |
| 501-1000  | 10        | 7.14%   |
| 1001-2000 | 7         | 5%      |
| Unknown   | 4         | 2.86%   |
| 2001-3000 | 2         | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 50%     |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Toshiba | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 84        | 232    | 68.85%  |
| Works    | 26        | 39     | 21.31%  |
| Malfunc  | 12        | 14     | 9.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 78        | 59.09%  |
| AMD                          | 25        | 18.94%  |
| SanDisk                      | 5         | 3.79%   |
| Silicon Motion               | 4         | 3.03%   |
| Samsung Electronics          | 4         | 3.03%   |
| Phison Electronics           | 4         | 3.03%   |
| SK hynix                     | 3         | 2.27%   |
| Micron/Crucial Technology    | 3         | 2.27%   |
| Nvidia                       | 2         | 1.52%   |
| Toshiba America Info Systems | 1         | 0.76%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.76%   |
| Kingston Technology Company  | 1         | 0.76%   |
| ASMedia Technology           | 1         | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 13.38%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 5.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 3.82%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.18%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 3.18%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 2.55%   |
| Phison E12 NVMe Controller                                                              | 4         | 2.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 2.55%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 1.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 1.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.91%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.91%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.27%   |
| AMD FCH IDE Controller                                                                  | 2         | 1.27%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.64%   |
| SK hynix BC511                                                                          | 1         | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.64%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.64%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.64%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1         | 0.64%   |
| Nvidia CK804 IDE                                                                        | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 82        | 58.16%  |
| NVMe | 27        | 19.15%  |
| IDE  | 18        | 12.77%  |
| RAID | 14        | 9.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 83        | 74.11%  |
| AMD    | 27        | 24.11%  |
| ARM    | 2         | 1.79%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 2.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 2.68%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 2.68%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 3         | 2.68%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.79%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 2         | 1.79%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.79%   |
| ARM Processor                               | 2         | 1.79%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.79%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.79%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.79%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 2         | 1.79%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.89%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.89%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.89%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.89%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.89%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.89%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 0.89%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.89%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.89%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 0.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.89%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.89%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.89%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 19.64%  |
| Intel Celeron           | 15        | 13.39%  |
| Intel Core i7           | 13        | 11.61%  |
| Intel Core i3           | 11        | 9.82%   |
| Other                   | 7         | 6.25%   |
| Intel Core 2 Duo        | 7         | 6.25%   |
| AMD Ryzen 5             | 7         | 6.25%   |
| Intel Pentium Silver    | 4         | 3.57%   |
| AMD Ryzen 7             | 4         | 3.57%   |
| AMD Ryzen 3             | 4         | 3.57%   |
| AMD A8                  | 4         | 3.57%   |
| Intel Pentium Dual-Core | 2         | 1.79%   |
| Intel Pentium           | 2         | 1.79%   |
| AMD A6                  | 2         | 1.79%   |
| Intel Genuine           | 1         | 0.89%   |
| Intel Core 2            | 1         | 0.89%   |
| AMD Ryzen Threadripper  | 1         | 0.89%   |
| AMD G                   | 1         | 0.89%   |
| AMD FX                  | 1         | 0.89%   |
| AMD Athlon 64 X2        | 1         | 0.89%   |
| AMD Athlon              | 1         | 0.89%   |
| AMD A10                 | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 56        | 50%     |
| 4      | 36        | 32.14%  |
| 6      | 11        | 9.82%   |
| 8      | 5         | 4.46%   |
| 1      | 3         | 2.68%   |
| 16     | 1         | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 112       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 62        | 55.36%  |
| 1      | 50        | 44.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 96.46%  |
| Unknown        | 3         | 2.65%   |
| 32-bit         | 1         | 0.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 21.19%  |
| 0x206a7    | 9         | 7.63%   |
| 0x306c3    | 6         | 5.08%   |
| 0x806e9    | 5         | 4.24%   |
| 0x306a9    | 5         | 4.24%   |
| 0x706a1    | 4         | 3.39%   |
| 0x20655    | 4         | 3.39%   |
| 0x1067a    | 4         | 3.39%   |
| 0xa0671    | 3         | 2.54%   |
| 0x806ec    | 3         | 2.54%   |
| 0x806ea    | 3         | 2.54%   |
| 0x30678    | 3         | 2.54%   |
| 0x08108109 | 3         | 2.54%   |
| 0x06001119 | 3         | 2.54%   |
| 0x906ea    | 2         | 1.69%   |
| 0x6fd      | 2         | 1.69%   |
| 0x406e3    | 2         | 1.69%   |
| 0x306d4    | 2         | 1.69%   |
| 0x08701013 | 2         | 1.69%   |
| 0x06003106 | 2         | 1.69%   |
| 0xa0652    | 1         | 0.85%   |
| 0x906ed    | 1         | 0.85%   |
| 0x906e9    | 1         | 0.85%   |
| 0x906c0    | 1         | 0.85%   |
| 0x806c1    | 1         | 0.85%   |
| 0x706e5    | 1         | 0.85%   |
| 0x6fb      | 1         | 0.85%   |
| 0x6e8      | 1         | 0.85%   |
| 0x506e3    | 1         | 0.85%   |
| 0x506c9    | 1         | 0.85%   |
| 0x406c4    | 1         | 0.85%   |
| 0x406c3    | 1         | 0.85%   |
| 0x40651    | 1         | 0.85%   |
| 0x30679    | 1         | 0.85%   |
| 0x20652    | 1         | 0.85%   |
| 0x10676    | 1         | 0.85%   |
| 0x08600106 | 1         | 0.85%   |
| 0x08600104 | 1         | 0.85%   |
| 0x0810100b | 1         | 0.85%   |
| 0x08101007 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 14.29%  |
| SandyBridge   | 10        | 8.93%   |
| Penryn        | 8         | 7.14%   |
| Haswell       | 8         | 7.14%   |
| Zen+          | 6         | 5.36%   |
| Zen 2         | 6         | 5.36%   |
| Silvermont    | 6         | 5.36%   |
| Westmere      | 5         | 4.46%   |
| IvyBridge     | 5         | 4.46%   |
| Goldmont plus | 5         | 4.46%   |
| Zen           | 4         | 3.57%   |
| Skylake       | 4         | 3.57%   |
| Piledriver    | 4         | 3.57%   |
| Core          | 4         | 3.57%   |
| Icelake       | 3         | 2.68%   |
| Unknown       | 3         | 2.68%   |
| TigerLake     | 2         | 1.79%   |
| Steamroller   | 2         | 1.79%   |
| Broadwell     | 2         | 1.79%   |
| Zen 3         | 1         | 0.89%   |
| Tremont       | 1         | 0.89%   |
| Puma          | 1         | 0.89%   |
| P6            | 1         | 0.89%   |
| K8 Hammer     | 1         | 0.89%   |
| K10 Llano     | 1         | 0.89%   |
| Goldmont      | 1         | 0.89%   |
| CometLake     | 1         | 0.89%   |
| Bobcat        | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 75        | 60.48%  |
| AMD    | 26        | 20.97%  |
| Nvidia | 23        | 18.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 7.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 3.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.01%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.26%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 2.26%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.26%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.26%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 1.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.5%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 1.5%    |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 2         | 1.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.5%    |
| Intel HD Graphics 620                                                                    | 2         | 1.5%    |
| Intel HD Graphics 5500                                                                   | 2         | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.5%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 1.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.5%    |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 2         | 1.5%    |
| AMD Renoir                                                                               | 2         | 1.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.5%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.5%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.75%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 63        | 55.26%  |
| 1 x AMD            | 22        | 19.3%   |
| 1 x Nvidia         | 12        | 10.53%  |
| Intel + Nvidia     | 8         | 7.02%   |
| Intel + AMD        | 3         | 2.63%   |
| Other              | 2         | 1.75%   |
| Intel + 2 x Nvidia | 2         | 1.75%   |
| 2 x Nvidia         | 1         | 0.88%   |
| 2 x AMD            | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 97        | 83.62%  |
| Proprietary | 13        | 11.21%  |
| Unknown     | 6         | 5.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 61.34%  |
| 0.01-0.5   | 12        | 10.08%  |
| 1.01-2.0   | 10        | 8.4%    |
| 0.51-1.0   | 10        | 8.4%    |
| 3.01-4.0   | 6         | 5.04%   |
| 5.01-6.0   | 4         | 3.36%   |
| 8.01-16.0  | 2         | 1.68%   |
| 7.01-8.0   | 1         | 0.84%   |
| 2.01-3.0   | 1         | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 12        | 9.68%   |
| LG Display              | 10        | 8.06%   |
| Goldstar                | 10        | 8.06%   |
| Chimei Innolux          | 9         | 7.26%   |
| Dell                    | 8         | 6.45%   |
| AU Optronics            | 7         | 5.65%   |
| BOE                     | 6         | 4.84%   |
| Acer                    | 6         | 4.84%   |
| Hewlett-Packard         | 5         | 4.03%   |
| Vizio                   | 4         | 3.23%   |
| ViewSonic               | 4         | 3.23%   |
| Sony                    | 4         | 3.23%   |
| Apple                   | 4         | 3.23%   |
| AOC                     | 4         | 3.23%   |
| Sceptre Tech            | 3         | 2.42%   |
| PANDA                   | 3         | 2.42%   |
| Gateway                 | 3         | 2.42%   |
| Element                 | 3         | 2.42%   |
| VIZ                     | 2         | 1.61%   |
| Tech Concepts           | 2         | 1.61%   |
| RTK                     | 2         | 1.61%   |
| eMachines               | 2         | 1.61%   |
| Unknown                 | 1         | 0.81%   |
| UGD                     | 1         | 0.81%   |
| Seiki                   | 1         | 0.81%   |
| ONN                     | 1         | 0.81%   |
| MTK                     | 1         | 0.81%   |
| MStar                   | 1         | 0.81%   |
| Lenovo                  | 1         | 0.81%   |
| InnoLux Display         | 1         | 0.81%   |
| Chi Mei Optoelectronics | 1         | 0.81%   |
| ASUSTek Computer        | 1         | 0.81%   |
| Ancor Communications    | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 3.85%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch            | 3         | 2.31%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 3         | 2.31%   |
| Element ELEFW328 ELE1366 1366x768 700x400mm 31.7-inch                  | 3         | 2.31%   |
| VIZ LCD Monitor M551d-A2R                                              | 2         | 1.54%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch          | 2         | 1.54%   |
| Sony TV  *00 SNY4B04 3840x2160                                         | 2         | 1.54%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch      | 2         | 1.54%   |
| Gateway LCD Monitor FHX2300                                            | 2         | 1.54%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                  | 2         | 1.54%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 2         | 1.54%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch                | 2         | 1.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.54%   |
| Acer LCD Monitor G236HL 5760x1080                                      | 2         | 1.54%   |
| Vizio M551d-A2R VIZ1006 1920x1080 1430x800mm 64.5-inch                 | 1         | 0.77%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                     | 1         | 0.77%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                    | 1         | 0.77%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                    | 1         | 0.77%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch               | 1         | 0.77%   |
| ViewSonic VA1930wm VSC171F 1440x900 410x260mm 19.1-inch                | 1         | 0.77%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                            | 1         | 0.77%   |
| UGD Artist 156 UGD1501 1920x1080 293x165mm 13.2-inch                   | 1         | 0.77%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                             | 1         | 0.77%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                             | 1         | 0.77%   |
| Sony TV SNYEA01 1920x1080                                              | 1         | 0.77%   |
| Sony TV SNY4502 1920x1080                                              | 1         | 0.77%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                    | 1         | 0.77%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch       | 1         | 0.77%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch         | 1         | 0.77%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch         | 1         | 0.77%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch      | 1         | 0.77%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch   | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch   | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1210x680mm 54.6-inch | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 609x347mm 27.6-inch   | 1         | 0.77%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1         | 0.77%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 44.74%  |
| 1366x768 (WXGA)    | 24        | 21.05%  |
| 3840x2160 (4K)     | 11        | 9.65%   |
| 1440x900 (WXGA+)   | 6         | 5.26%   |
| 1600x900 (HD+)     | 4         | 3.51%   |
| 1280x800 (WXGA)    | 4         | 3.51%   |
| 1280x1024 (SXGA)   | 3         | 2.63%   |
| 5760x1080          | 2         | 1.75%   |
| 2560x1080          | 2         | 1.75%   |
| Unknown            | 2         | 1.75%   |
| 3840x1080          | 1         | 0.88%   |
| 3440x1440          | 1         | 0.88%   |
| 2560x1440 (QHD)    | 1         | 0.88%   |
| 1680x1050 (WSXGA+) | 1         | 0.88%   |
| 1280x720 (HD)      | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 22.5%   |
| 21      | 14        | 11.67%  |
| 23      | 10        | 8.33%   |
| 14      | 8         | 6.67%   |
| 72      | 7         | 5.83%   |
| 17      | 7         | 5.83%   |
| 31      | 6         | 5%      |
| 19      | 6         | 5%      |
| 13      | 5         | 4.17%   |
| Unknown | 5         | 4.17%   |
| 27      | 4         | 3.33%   |
| 20      | 4         | 3.33%   |
| 34      | 3         | 2.5%    |
| 18      | 3         | 2.5%    |
| 11      | 2         | 1.67%   |
| 84      | 1         | 0.83%   |
| 64      | 1         | 0.83%   |
| 52      | 1         | 0.83%   |
| 49      | 1         | 0.83%   |
| 32      | 1         | 0.83%   |
| 26      | 1         | 0.83%   |
| 25      | 1         | 0.83%   |
| 24      | 1         | 0.83%   |
| 22      | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 31.62%  |
| 401-500     | 25        | 21.37%  |
| 501-600     | 16        | 13.68%  |
| 351-400     | 8         | 6.84%   |
| 1501-2000   | 8         | 6.84%   |
| 601-700     | 6         | 5.13%   |
| 201-300     | 5         | 4.27%   |
| Unknown     | 5         | 4.27%   |
| 701-800     | 4         | 3.42%   |
| 1001-1500   | 3         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 82        | 77.36%  |
| 16/10   | 12        | 11.32%  |
| Unknown | 5         | 4.72%   |
| 5/4     | 4         | 3.77%   |
| 21/9    | 3         | 2.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 22.88%  |
| 201-250        | 22        | 18.64%  |
| 151-200        | 14        | 11.86%  |
| 81-90          | 12        | 10.17%  |
| More than 1000 | 10        | 8.47%   |
| 351-500        | 10        | 8.47%   |
| Unknown        | 5         | 4.24%   |
| 301-350        | 4         | 3.39%   |
| 141-150        | 4         | 3.39%   |
| 121-130        | 4         | 3.39%   |
| 51-60          | 2         | 1.69%   |
| 251-300        | 2         | 1.69%   |
| 71-80          | 1         | 0.85%   |
| 131-140        | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 42        | 36.52%  |
| 51-100        | 36        | 31.3%   |
| 121-160       | 19        | 16.52%  |
| 1-50          | 10        | 8.7%    |
| Unknown       | 5         | 4.35%   |
| 161-240       | 2         | 1.74%   |
| More than 240 | 1         | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 90        | 77.59%  |
| 2     | 20        | 17.24%  |
| 0     | 4         | 3.45%   |
| 3     | 2         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 39.56%  |
| Intel                    | 60        | 32.97%  |
| Qualcomm Atheros         | 15        | 8.24%   |
| Broadcom                 | 7         | 3.85%   |
| Ralink Technology        | 5         | 2.75%   |
| NetGear                  | 5         | 2.75%   |
| Marvell Technology Group | 3         | 1.65%   |
| Broadcom Limited         | 3         | 1.65%   |
| TP-Link                  | 2         | 1.1%    |
| Samsung Electronics      | 2         | 1.1%    |
| Nvidia                   | 2         | 1.1%    |
| Ralink                   | 1         | 0.55%   |
| Gemtek                   | 1         | 0.55%   |
| Dell                     | 1         | 0.55%   |
| Belkin Components        | 1         | 0.55%   |
| ASIX Electronics         | 1         | 0.55%   |
| Aquantia                 | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 22.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.86%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 3.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.42%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.93%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.45%   |
| Intel Wireless 7265                                               | 3         | 1.45%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.97%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.97%   |
| Realtek 802.11ac NIC                                              | 2         | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.97%   |
| NetGear LB1120-100NAS                                             | 2         | 0.97%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.97%   |
| Intel Wireless 3160                                               | 2         | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.97%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 2         | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.97%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.97%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 2         | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.48%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1         | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.48%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 40.4%   |
| Realtek Semiconductor | 25        | 25.25%  |
| Qualcomm Atheros      | 12        | 12.12%  |
| Broadcom              | 6         | 6.06%   |
| Ralink Technology     | 5         | 5.05%   |
| NetGear               | 3         | 3.03%   |
| TP-Link               | 2         | 2.02%   |
| Broadcom Limited      | 2         | 2.02%   |
| Ralink                | 1         | 1.01%   |
| Gemtek                | 1         | 1.01%   |
| Dell                  | 1         | 1.01%   |
| Belkin Components     | 1         | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 7         | 6.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 5         | 4.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 4         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4         | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4         | 3.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 3         | 2.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 3         | 2.88%   |
| Intel Wireless 7265                                        | 3         | 2.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 1.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 2         | 1.92%   |
| Realtek 802.11ac NIC                                       | 2         | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 2         | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 1.92%   |
| Intel Wireless 8265 / 8275                                 | 2         | 1.92%   |
| Intel Wireless 3160                                        | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2         | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 2         | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 1.92%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 2         | 1.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 2         | 1.92%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 2         | 1.92%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 2         | 1.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 0.96%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 0.96%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 0.96%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 0.96%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 0.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 0.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1         | 0.96%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 0.96%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                     | 1         | 0.96%   |
| Realtek RTL8187 Wireless Adapter                           | 1         | 0.96%   |
| Ralink RT2870 Wireless Adapter                             | 1         | 0.96%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 1         | 0.96%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 0.96%   |
| Ralink RT2561/RT61 802.11g PCI                             | 1         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 56.31%  |
| Intel                    | 27        | 26.21%  |
| Qualcomm Atheros         | 3         | 2.91%   |
| Marvell Technology Group | 3         | 2.91%   |
| Broadcom                 | 3         | 2.91%   |
| Samsung Electronics      | 2         | 1.94%   |
| Nvidia                   | 2         | 1.94%   |
| NetGear                  | 2         | 1.94%   |
| Broadcom Limited         | 1         | 0.97%   |
| ASIX Electronics         | 1         | 0.97%   |
| Aquantia                 | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 46        | 44.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 7.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 6.8%    |
| Intel I211 Gigabit Network Connection                                          | 5         | 4.85%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 3.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 2.91%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.94%   |
| NetGear LB1120-100NAS                                                          | 2         | 1.94%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.97%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.97%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.97%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.97%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.97%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.97%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.97%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.97%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.97%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.97%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.97%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.97%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 0.97%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.97%   |
| ASIX AX88772B                                                                  | 1         | 0.97%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 98        | 53.26%  |
| WiFi     | 86        | 46.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 53.33%  |
| Ethernet | 56        | 46.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 58        | 50.88%  |
| 1     | 50        | 43.86%  |
| 3     | 3         | 2.63%   |
| 0     | 3         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 91.07%  |
| Yes  | 10        | 8.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 47.89%  |
| Realtek Semiconductor           | 8         | 11.27%  |
| Cambridge Silicon Radio         | 7         | 9.86%   |
| Qualcomm Atheros Communications | 5         | 7.04%   |
| Lite-On Technology              | 3         | 4.23%   |
| Apple                           | 3         | 4.23%   |
| Foxconn / Hon Hai               | 2         | 2.82%   |
| Broadcom                        | 2         | 2.82%   |
| Toshiba                         | 1         | 1.41%   |
| IMC Networks                    | 1         | 1.41%   |
| Hewlett-Packard                 | 1         | 1.41%   |
| Dynex                           | 1         | 1.41%   |
| Dell                            | 1         | 1.41%   |
| Belkin Components               | 1         | 1.41%   |
| Alps Electric                   | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 9         | 12.68%  |
| Intel AX200 Bluetooth                                                               | 7         | 9.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 9.86%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 7.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 7.04%   |
| Intel AX201 Bluetooth                                                               | 5         | 7.04%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 5.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 5.63%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.23%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.82%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.82%   |
| Broadcom Bluetooth Device                                                           | 2         | 2.82%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.82%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.41%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.41%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.41%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.41%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.41%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 1.41%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.41%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 1.41%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.41%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 82        | 58.16%  |
| AMD                                             | 28        | 19.86%  |
| Nvidia                                          | 19        | 13.48%  |
| Logitech                                        | 6         | 4.26%   |
| C-Media Electronics                             | 2         | 1.42%   |
| Nintendo                                        | 1         | 0.71%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.71%   |
| Kingston Technology                             | 1         | 0.71%   |
| Focusrite-Novation                              | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 6.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.78%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 5.78%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 2.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.31%   |
| Logitech EasyCall Speakerphone                                                                    | 3         | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.73%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.73%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.73%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.16%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.16%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.16%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.16%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.16%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.16%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


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

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 3         | 6.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 4.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 4.26%   |
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
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1         | 2.13%   |
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
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1         | 2.13%   |
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

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


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

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 48.78%  |
| DIMM         | 20        | 48.78%  |
| Row Of Chips | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 47.62%  |
| 4096  | 15        | 35.71%  |
| 2048  | 5         | 11.9%   |
| 16384 | 2         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 17.24%  |
| Microdia                               | 8         | 13.79%  |
| Ricoh                                  | 5         | 8.62%   |
| Logitech                               | 5         | 8.62%   |
| Realtek Semiconductor                  | 4         | 6.9%    |
| Quanta                                 | 3         | 5.17%   |
| Apple                                  | 3         | 5.17%   |
| Acer                                   | 3         | 5.17%   |
| Suyin                                  | 2         | 3.45%   |
| Sunplus Innovation Technology          | 2         | 3.45%   |
| Luxvisions Innotech Limited            | 2         | 3.45%   |
| Lite-On Technology                     | 2         | 3.45%   |
| IMC Networks                           | 2         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.45%   |
| Lenovo                                 | 1         | 1.72%   |
| Jieli Technology                       | 1         | 1.72%   |
| Goertek Electronics                    | 1         | 1.72%   |
| Cubeternet                             | 1         | 1.72%   |
| Alpha Imaging Technology               | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Microdia Camera                                          | 4         | 6.9%    |
| Ricoh Integrated Webcam                                  | 3         | 5.17%   |
| Sunplus Integrated_Webcam_HD                             | 2         | 3.45%   |
| Chicony HD WebCam                                        | 2         | 3.45%   |
| Suyin USB 2.0 Camera                                     | 1         | 1.72%   |
| Suyin Integrated_Webcam_HD                               | 1         | 1.72%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam | 1         | 1.72%   |
| Ricoh HD Webcam                                          | 1         | 1.72%   |
| Realtek MTD camera                                       | 1         | 1.72%   |
| Realtek Integrated Webcam HD                             | 1         | 1.72%   |
| Realtek Integrated Webcam                                | 1         | 1.72%   |
| Realtek 2SF022                                           | 1         | 1.72%   |
| Quanta HP Wide Vision HD Camera                          | 1         | 1.72%   |
| Quanta HP TrueVision HD Camera                           | 1         | 1.72%   |
| Quanta HD WebCam                                         | 1         | 1.72%   |
| Microdia USB Live camera                                 | 1         | 1.72%   |
| Microdia Laptop_Integrated_Webcam_HD                     | 1         | 1.72%   |
| Microdia Integrated_Webcam_HD                            | 1         | 1.72%   |
| Microdia Dell Integrated HD Webcam                       | 1         | 1.72%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera     | 1         | 1.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera      | 1         | 1.72%   |
| Logitech Webcam Pro 9000                                 | 1         | 1.72%   |
| Logitech Webcam C310                                     | 1         | 1.72%   |
| Logitech Webcam C270                                     | 1         | 1.72%   |
| Logitech HD Pro Webcam C920                              | 1         | 1.72%   |
| Logitech CrystalCam                                      | 1         | 1.72%   |
| Lite-On HP Wide Vision HD Camera                         | 1         | 1.72%   |
| Lite-On HP HD Webcam                                     | 1         | 1.72%   |
| Lenovo Integrated Webcam [R5U877]                        | 1         | 1.72%   |
| Jieli USB PHY 2.0                                        | 1         | 1.72%   |
| IMC Networks UVC VGA Webcam                              | 1         | 1.72%   |
| IMC Networks Integrated Camera                           | 1         | 1.72%   |
| Goertek USB2.0 VGA UVC WebCam                            | 1         | 1.72%   |
| Cubeternet GL-UPC822 UVC WebCam                          | 1         | 1.72%   |
| Chicony TOSHIBA Web Camera - HD                          | 1         | 1.72%   |
| Chicony Toshiba Integrated Webcam                        | 1         | 1.72%   |
| Chicony Integrated HP HD Webcam                          | 1         | 1.72%   |
| Chicony HP Webcam                                        | 1         | 1.72%   |
| Chicony HP Truevision HD                                 | 1         | 1.72%   |
| Chicony HP HD Camera                                     | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 66.67%  |
| Synaptics             | 2         | 16.67%  |
| LighTuning Technology | 2         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 81        | 66.94%  |
| 1     | 35        | 28.93%  |
| 2     | 5         | 4.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 16        | 39.02%  |
| Fingerprint reader       | 12        | 29.27%  |
| Graphics card            | 7         | 17.07%  |
| Communication controller | 2         | 4.88%   |
| Chipcard                 | 2         | 4.88%   |
| Net/ethernet             | 1         | 2.44%   |
| Multimedia controller    | 1         | 2.44%   |

