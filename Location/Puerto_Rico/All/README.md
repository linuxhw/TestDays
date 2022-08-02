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

Total: 207

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [3f1e6ca5cb](https://linux-hardware.org/?probe=3f1e6ca5cb) | Jul 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [012b0c7fa9](https://linux-hardware.org/?probe=012b0c7fa9) | Jul 23, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c444890ad0](https://linux-hardware.org/?probe=c444890ad0) | Jul 21, 2022 |
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
| Ubuntu 20.04        | 23        | 18.25%  |
| Ubuntu 18.04        | 11        | 8.73%   |
| OpenMandriva 4.2    | 6         | 4.76%   |
| Ubuntu 21.10        | 4         | 3.17%   |
| Ubuntu 20.10        | 4         | 3.17%   |
| OpenMandriva 4.3    | 4         | 3.17%   |
| Zorin 16            | 3         | 2.38%   |
| Ubuntu 22.04        | 3         | 2.38%   |
| Manjaro             | 3         | 2.38%   |
| Linux Mint 20.1     | 3         | 2.38%   |
| Linux Mint 19.3     | 3         | 2.38%   |
| KDE neon 20.04      | 3         | 2.38%   |
| BlackPanther 18.1   | 3         | 2.38%   |
| Xubuntu 20.04       | 2         | 1.59%   |
| Ubuntu 19.10        | 2         | 1.59%   |
| ROSA R11            | 2         | 1.59%   |
| ROSA R10            | 2         | 1.59%   |
| Lubuntu 20.04       | 2         | 1.59%   |
| LMDE 4              | 2         | 1.59%   |
| Linux Mint 20.3     | 2         | 1.59%   |
| Linux Mint 20.2     | 2         | 1.59%   |
| Linux Mint 20       | 2         | 1.59%   |
| Garuda Linux        | 2         | 1.59%   |
| Fedora 36           | 2         | 1.59%   |
| ArcoLinux Rolling   | 2         | 1.59%   |
| Zorin 15            | 1         | 0.79%   |
| Xubuntu 20.10       | 1         | 0.79%   |
| Ubuntu MATE 20.04   | 1         | 0.79%   |
| Ubuntu Budgie 21.04 | 1         | 0.79%   |
| ROSA R9             | 1         | 0.79%   |
| Pop!_OS 21.10       | 1         | 0.79%   |
| Pop!_OS 21.04       | 1         | 0.79%   |
| Pop!_OS 20.10       | 1         | 0.79%   |
| Pop!_OS 20.04       | 1         | 0.79%   |
| Pop!_OS 19.10       | 1         | 0.79%   |
| Peppermint 9        | 1         | 0.79%   |
| Parrot 5.0          | 1         | 0.79%   |
| Parrot 4.11         | 1         | 0.79%   |
| openSUSE Leap-15.2  | 1         | 0.79%   |
| OpenMandriva 4.50   | 1         | 0.79%   |
| Manjaro 21.1.5      | 1         | 0.79%   |
| Manjaro 20.1.2      | 1         | 0.79%   |
| LinuxFX 11          | 1         | 0.79%   |
| Linux Mint 21       | 1         | 0.79%   |
| Linux Mint 19.1     | 1         | 0.79%   |
| Fedora 33           | 1         | 0.79%   |
| Endless 3.9.1       | 1         | 0.79%   |
| Endless 3.7.8       | 1         | 0.79%   |
| EndeavourOS Rolling | 1         | 0.79%   |
| Devuan 4            | 1         | 0.79%   |
| Debian 9            | 1         | 0.79%   |
| Debian 10           | 1         | 0.79%   |
| CentOS 8            | 1         | 0.79%   |
| Arch                | 1         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 45        | 37.82%  |
| OpenMandriva  | 11        | 9.24%   |
| Linux Mint    | 11        | 9.24%   |
| Pop!_OS       | 5         | 4.2%    |
| Zorin         | 4         | 3.36%   |
| ROSA          | 4         | 3.36%   |
| Manjaro       | 4         | 3.36%   |
| Xubuntu       | 3         | 2.52%   |
| KDE neon      | 3         | 2.52%   |
| Fedora        | 3         | 2.52%   |
| BlackPanther  | 3         | 2.52%   |
| Parrot        | 2         | 1.68%   |
| Lubuntu       | 2         | 1.68%   |
| LMDE          | 2         | 1.68%   |
| Garuda Linux  | 2         | 1.68%   |
| Endless       | 2         | 1.68%   |
| Debian        | 2         | 1.68%   |
| ArcoLinux     | 2         | 1.68%   |
| Ubuntu MATE   | 1         | 0.84%   |
| Ubuntu Budgie | 1         | 0.84%   |
| Peppermint    | 1         | 0.84%   |
| openSUSE      | 1         | 0.84%   |
| LinuxFX       | 1         | 0.84%   |
| EndeavourOS   | 1         | 0.84%   |
| Devuan        | 1         | 0.84%   |
| CentOS        | 1         | 0.84%   |
| Arch          | 1         | 0.84%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 6         | 4.05%   |
| 5.4.0-58-generic               | 4         | 2.7%    |
| 5.16.7-desktop-1omv4003        | 4         | 2.7%    |
| 5.8.0-59-generic               | 3         | 2.03%   |
| 5.11.0-38-generic              | 3         | 2.03%   |
| 4.15.0-43-generic              | 3         | 2.03%   |
| 5.8.18-1-MANJARO               | 2         | 1.35%   |
| 5.8.0-55-generic               | 2         | 1.35%   |
| 5.8.0-45-generic               | 2         | 1.35%   |
| 5.4.0-73-generic               | 2         | 1.35%   |
| 5.4.0-72-generic               | 2         | 1.35%   |
| 5.4.0-52-generic               | 2         | 1.35%   |
| 5.4.0-48-generic               | 2         | 1.35%   |
| 5.4.0-47-generic               | 2         | 1.35%   |
| 5.4.0-40-generic               | 2         | 1.35%   |
| 5.4.0-109-generic              | 2         | 1.35%   |
| 5.3.0-41-generic               | 2         | 1.35%   |
| 5.3.0-28-generic               | 2         | 1.35%   |
| 5.15.0-40-generic              | 2         | 1.35%   |
| 5.13.0-40-generic              | 2         | 1.35%   |
| 5.13.0-39-generic              | 2         | 1.35%   |
| 5.13.0-35-generic              | 2         | 1.35%   |
| 5.13.0-30-generic              | 2         | 1.35%   |
| 5.11.0-41-generic              | 2         | 1.35%   |
| 5.11.0-27-generic              | 2         | 1.35%   |
| 4.18.16-desktop-1bP            | 2         | 1.35%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2         | 1.35%   |
| 5.9.16-200.fc33.x86_64         | 1         | 0.68%   |
| 5.9.16-1-MANJARO               | 1         | 0.68%   |
| 5.9.1-1-MANJARO                | 1         | 0.68%   |
| 5.8.5-zen1-1-zen               | 1         | 0.68%   |
| 5.8.14-zen1-1-zen              | 1         | 0.68%   |
| 5.8.0-7630-generic             | 1         | 0.68%   |
| 5.8.0-63-generic               | 1         | 0.68%   |
| 5.8.0-54-generic               | 1         | 0.68%   |
| 5.8.0-53-generic               | 1         | 0.68%   |
| 5.8.0-49-generic               | 1         | 0.68%   |
| 5.8.0-44-generic               | 1         | 0.68%   |
| 5.8.0-29-generic               | 1         | 0.68%   |
| 5.8.0-25-generic               | 1         | 0.68%   |
| 5.8.0-14-generic               | 1         | 0.68%   |
| 5.8.0-1011-raspi               | 1         | 0.68%   |
| 5.8.0-1008-raspi               | 1         | 0.68%   |
| 5.8.0-1006-raspi               | 1         | 0.68%   |
| 5.6.14-desktop-2bP             | 1         | 0.68%   |
| 5.4.0-89-generic               | 1         | 0.68%   |
| 5.4.0-88-generic               | 1         | 0.68%   |
| 5.4.0-84-generic               | 1         | 0.68%   |
| 5.4.0-77-generic               | 1         | 0.68%   |
| 5.4.0-7634-generic             | 1         | 0.68%   |
| 5.4.0-70-generic               | 1         | 0.68%   |
| 5.4.0-65-generic               | 1         | 0.68%   |
| 5.4.0-62-generic               | 1         | 0.68%   |
| 5.4.0-60-generic               | 1         | 0.68%   |
| 5.4.0-59-generic               | 1         | 0.68%   |
| 5.4.0-55-generic               | 1         | 0.68%   |
| 5.4.0-42-generic               | 1         | 0.68%   |
| 5.4.0-37-generic               | 1         | 0.68%   |
| 5.4.0-29-generic               | 1         | 0.68%   |
| 5.3.6-050306-generic           | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 29        | 22.66%  |
| 5.8.0   | 14        | 10.94%  |
| 5.13.0  | 11        | 8.59%   |
| 4.15.0  | 10        | 7.81%   |
| 5.11.0  | 9         | 7.03%   |
| 5.3.0   | 6         | 4.69%   |
| 5.10.14 | 6         | 4.69%   |
| 5.16.7  | 4         | 3.13%   |
| 5.15.0  | 4         | 3.13%   |
| 4.19.0  | 3         | 2.34%   |
| 4.18.0  | 3         | 2.34%   |
| 5.9.16  | 2         | 1.56%   |
| 5.8.18  | 2         | 1.56%   |
| 5.10.0  | 2         | 1.56%   |
| 4.9.60  | 2         | 1.56%   |
| 4.18.16 | 2         | 1.56%   |
| 5.9.1   | 1         | 0.78%   |
| 5.8.5   | 1         | 0.78%   |
| 5.8.14  | 1         | 0.78%   |
| 5.6.14  | 1         | 0.78%   |
| 5.3.6   | 1         | 0.78%   |
| 5.3.18  | 1         | 0.78%   |
| 5.18.9  | 1         | 0.78%   |
| 5.18.6  | 1         | 0.78%   |
| 5.18.5  | 1         | 0.78%   |
| 5.18.0  | 1         | 0.78%   |
| 5.17.1  | 1         | 0.78%   |
| 5.15.5  | 1         | 0.78%   |
| 5.14.8  | 1         | 0.78%   |
| 5.13.19 | 1         | 0.78%   |
| 5.12.4  | 1         | 0.78%   |
| 5.11.16 | 1         | 0.78%   |
| 5.11.13 | 1         | 0.78%   |
| 4.9.20  | 1         | 0.78%   |
| 4.9.0   | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 29        | 23.39%  |
| 5.8     | 18        | 14.52%  |
| 5.13    | 12        | 9.68%   |
| 5.11    | 10        | 8.06%   |
| 4.15    | 10        | 8.06%   |
| 5.3     | 8         | 6.45%   |
| 5.10    | 8         | 6.45%   |
| 5.15    | 5         | 4.03%   |
| 5.16    | 4         | 3.23%   |
| 4.9     | 4         | 3.23%   |
| 4.18    | 4         | 3.23%   |
| 5.9     | 3         | 2.42%   |
| 4.19    | 3         | 2.42%   |
| 5.18    | 2         | 1.61%   |
| 5.6     | 1         | 0.81%   |
| 5.17    | 1         | 0.81%   |
| 5.14    | 1         | 0.81%   |
| 5.12    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 99        | 96.12%  |
| i686    | 2         | 1.94%   |
| aarch64 | 2         | 1.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 56        | 47.06%  |
| KDE5       | 22        | 18.49%  |
| X-Cinnamon | 9         | 7.56%   |
| XFCE       | 7         | 5.88%   |
| Unknown    | 6         | 5.04%   |
| MATE       | 5         | 4.2%    |
| LXQt       | 2         | 1.68%   |
| LXDE       | 2         | 1.68%   |
| KDE4       | 2         | 1.68%   |
| KDE        | 2         | 1.68%   |
| Budgie     | 2         | 1.68%   |
| Unity      | 1         | 0.84%   |
| i3         | 1         | 0.84%   |
| Deepin     | 1         | 0.84%   |
| Cinnamon   | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 95        | 90.48%  |
| Wayland | 9         | 8.57%   |
| Unknown | 1         | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 71        | 62.28%  |
| SDDM    | 15        | 13.16%  |
| GDM3    | 12        | 10.53%  |
| GDM     | 6         | 5.26%   |
| LightDM | 5         | 4.39%   |
| TDM     | 3         | 2.63%   |
| KDM     | 2         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 86        | 81.9%   |
| Unknown | 12        | 11.43%  |
| es_PR   | 5         | 4.76%   |
| es_ES   | 1         | 0.95%   |
| C       | 1         | 0.95%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 61        | 56.48%  |
| EFI  | 47        | 43.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 81        | 74.31%  |
| Overlay | 15        | 13.76%  |
| Btrfs   | 6         | 5.5%    |
| Unknown | 5         | 4.59%   |
| Zfs     | 1         | 0.92%   |
| Xfs     | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 80        | 72.73%  |
| GPT     | 21        | 19.09%  |
| MBR     | 9         | 8.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 85.19%  |
| Yes       | 16        | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 74.55%  |
| Yes       | 28        | 25.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 19        | 18.45%  |
| Dell                    | 18        | 17.48%  |
| Gigabyte Technology     | 9         | 8.74%   |
| MSI                     | 8         | 7.77%   |
| ASUSTek Computer        | 8         | 7.77%   |
| ASRock                  | 8         | 7.77%   |
| Lenovo                  | 7         | 6.8%    |
| Acer                    | 5         | 4.85%   |
| Apple                   | 4         | 3.88%   |
| Toshiba                 | 3         | 2.91%   |
| Sony                    | 2         | 1.94%   |
| Raspberry Pi Foundation | 2         | 1.94%   |
| Intel                   | 2         | 1.94%   |
| TUXEDO                  | 1         | 0.97%   |
| Pegatron                | 1         | 0.97%   |
| GPU Company             | 1         | 0.97%   |
| CompuLab                | 1         | 0.97%   |
| AZW                     | 1         | 0.97%   |
| AMI                     | 1         | 0.97%   |
| Alienware               | 1         | 0.97%   |
| Acidanthera             | 1         | 0.97%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Dell Vostro 3550                        | 3         | 2.91%   |
| RPi Raspberry Pi                        | 2         | 1.94%   |
| MSI Cubi N 8GL (MS-B171)                | 2         | 1.94%   |
| Intel SKYBAY                            | 2         | 1.94%   |
| ASRock Q1900M                           | 2         | 1.94%   |
| ASRock 945GCM-S                         | 2         | 1.94%   |
| TUXEDO Aura 15 Gen1                     | 1         | 0.97%   |
| Toshiba Satellite P755                  | 1         | 0.97%   |
| Toshiba Satellite L655                  | 1         | 0.97%   |
| Toshiba Satellite C55-C                 | 1         | 0.97%   |
| Sony VPCEA36FX                          | 1         | 0.97%   |
| Sony VGN-CS320J                         | 1         | 0.97%   |
| Pegatron QW716AA#ABA                    | 1         | 0.97%   |
| MSI US PIO PRO AP241                    | 1         | 0.97%   |
| MSI MS-7B48                             | 1         | 0.97%   |
| MSI MS-7971                             | 1         | 0.97%   |
| MSI MS-7817                             | 1         | 0.97%   |
| MSI GF65 Thin 10SDR                     | 1         | 0.97%   |
| MSI Cubi N JSL (MS-B0A1)                | 1         | 0.97%   |
| Lenovo Yoga 910-13IKB 80VF              | 1         | 0.97%   |
| Lenovo ThinkPad T410 2516ADU            | 1         | 0.97%   |
| Lenovo ThinkCentre M91p 7033CG1         | 1         | 0.97%   |
| Lenovo ThinkCentre M58p 6136A66         | 1         | 0.97%   |
| Lenovo IdeaPad 120S-11IAP 81A4          | 1         | 0.97%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS | 1         | 0.97%   |
| Lenovo G50-45 80E3                      | 1         | 0.97%   |
| HP Stream Laptop 14-CB1xxx              | 1         | 0.97%   |
| HP ProBook 6560b                        | 1         | 0.97%   |
| HP ProBook 6450b                        | 1         | 0.97%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 0.97%   |
| HP Notebook                             | 1         | 0.97%   |
| HP Laptop 15-dy1xxx                     | 1         | 0.97%   |
| HP Laptop 15-dw0xxx                     | 1         | 0.97%   |
| HP Laptop 14-dk1xxx                     | 1         | 0.97%   |
| HP ENVY Laptop 17m-bw0xxx               | 1         | 0.97%   |
| HP ENVY Laptop 17-ce1xxx                | 1         | 0.97%   |
| HP ENVY dv7                             | 1         | 0.97%   |
| HP EliteDesk 800 G1 TWR                 | 1         | 0.97%   |
| HP EliteDesk 800 G1 SFF                 | 1         | 0.97%   |
| HP EliteBook 840 G2                     | 1         | 0.97%   |
| HP Compaq Pro 6300 SFF                  | 1         | 0.97%   |
| HP Compaq Pro 6300 MT                   | 1         | 0.97%   |
| HP Compaq nc6400 (RB516UT#ABA)          | 1         | 0.97%   |
| HP Compaq dc7800p Small Form Factor     | 1         | 0.97%   |
| HP Compaq 8200 Elite SFF PC             | 1         | 0.97%   |
| GPU Company GWTN156-9                   | 1         | 0.97%   |
| Gigabyte Z97M-DS3H                      | 1         | 0.97%   |
| Gigabyte X570 GAMING X                  | 1         | 0.97%   |
| Gigabyte X570 AORUS ELITE WIFI          | 1         | 0.97%   |
| Gigabyte X399 AORUS Gaming 7            | 1         | 0.97%   |
| Gigabyte J1900N-D3V                     | 1         | 0.97%   |
| Gigabyte F2A78M-HD2                     | 1         | 0.97%   |
| Gigabyte F2A68HM-H                      | 1         | 0.97%   |
| Gigabyte B450M DS3H                     | 1         | 0.97%   |
| Gigabyte B450 AORUS PRO WIFI            | 1         | 0.97%   |
| Dell Venue 11 Pro 7130 MS               | 1         | 0.97%   |
| Dell Studio 540                         | 1         | 0.97%   |
| Dell OptiPlex 960                       | 1         | 0.97%   |
| Dell OptiPlex 9020                      | 1         | 0.97%   |
| Dell OptiPlex 780                       | 1         | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 7         | 6.8%    |
| HP Compaq             | 5         | 4.85%   |
| Dell OptiPlex         | 4         | 3.88%   |
| Toshiba Satellite     | 3         | 2.91%   |
| MSI Cubi              | 3         | 2.91%   |
| HP Laptop             | 3         | 2.91%   |
| HP ENVY               | 3         | 2.91%   |
| Dell Vostro           | 3         | 2.91%   |
| Acer Aspire           | 3         | 2.91%   |
| RPi Raspberry         | 2         | 1.94%   |
| Lenovo ThinkCentre    | 2         | 1.94%   |
| Intel SKYBAY          | 2         | 1.94%   |
| HP ProBook            | 2         | 1.94%   |
| HP EliteDesk          | 2         | 1.94%   |
| Gigabyte X570         | 2         | 1.94%   |
| Dell Latitude         | 2         | 1.94%   |
| ASUS ROG              | 2         | 1.94%   |
| ASRock Q1900M         | 2         | 1.94%   |
| ASRock B450M-HDV      | 2         | 1.94%   |
| ASRock 945GCM-S       | 2         | 1.94%   |
| Acer Swift            | 2         | 1.94%   |
| TUXEDO Aura           | 1         | 0.97%   |
| Sony VPCEA36FX        | 1         | 0.97%   |
| Sony VGN-CS320J       | 1         | 0.97%   |
| Pegatron QW716AA#ABA  | 1         | 0.97%   |
| MSI US                | 1         | 0.97%   |
| MSI MS-7B48           | 1         | 0.97%   |
| MSI MS-7971           | 1         | 0.97%   |
| MSI MS-7817           | 1         | 0.97%   |
| MSI GF65              | 1         | 0.97%   |
| Lenovo Yoga           | 1         | 0.97%   |
| Lenovo ThinkPad       | 1         | 0.97%   |
| Lenovo IdeaPad        | 1         | 0.97%   |
| Lenovo IdeaCentre     | 1         | 0.97%   |
| Lenovo G50-45         | 1         | 0.97%   |
| HP Stream             | 1         | 0.97%   |
| HP Pavilion           | 1         | 0.97%   |
| HP Notebook           | 1         | 0.97%   |
| HP EliteBook          | 1         | 0.97%   |
| GPU Company GWTN156-9 | 1         | 0.97%   |
| Gigabyte Z97M-DS3H    | 1         | 0.97%   |
| Gigabyte X399         | 1         | 0.97%   |
| Gigabyte J1900N-D3V   | 1         | 0.97%   |
| Gigabyte F2A78M-HD2   | 1         | 0.97%   |
| Gigabyte F2A68HM-H    | 1         | 0.97%   |
| Gigabyte B450M        | 1         | 0.97%   |
| Gigabyte B450         | 1         | 0.97%   |
| Dell Venue            | 1         | 0.97%   |
| Dell Studio           | 1         | 0.97%   |
| CompuLab fit-PC3      | 1         | 0.97%   |
| AZW GT-R              | 1         | 0.97%   |
| ASUS X540SAA          | 1         | 0.97%   |
| ASUS TUF              | 1         | 0.97%   |
| ASUS PRIME            | 1         | 0.97%   |
| ASUS M5A78L-M         | 1         | 0.97%   |
| ASUS M2N-E            | 1         | 0.97%   |
| ASUS K53E             | 1         | 0.97%   |
| ASRock Z270           | 1         | 0.97%   |
| ASRock G31M-S         | 1         | 0.97%   |
| Apple MacBookPro8     | 1         | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 13        | 12.62%  |
| 2018    | 13        | 12.62%  |
| 2011    | 12        | 11.65%  |
| 2014    | 9         | 8.74%   |
| 2020    | 7         | 6.8%    |
| 2015    | 7         | 6.8%    |
| 2016    | 6         | 5.83%   |
| 2008    | 6         | 5.83%   |
| 2012    | 5         | 4.85%   |
| 2010    | 5         | 4.85%   |
| 2021    | 4         | 3.88%   |
| 2013    | 4         | 3.88%   |
| 2017    | 3         | 2.91%   |
| 2009    | 3         | 2.91%   |
| 2006    | 2         | 1.94%   |
| Unknown | 2         | 1.94%   |
| 2007    | 1         | 0.97%   |
| 2005    | 1         | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 49        | 47.57%  |
| Notebook       | 46        | 44.66%  |
| All in one     | 4         | 3.88%   |
| System on chip | 2         | 1.94%   |
| Convertible    | 1         | 0.97%   |
| Mini pc        | 1         | 0.97%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 97        | 93.27%  |
| Enabled  | 7         | 6.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 30.84%  |
| 3.01-4.0    | 23        | 21.5%   |
| 8.01-16.0   | 21        | 19.63%  |
| 16.01-24.0  | 14        | 13.08%  |
| 32.01-64.0  | 6         | 5.61%   |
| 1.01-2.0    | 5         | 4.67%   |
| 24.01-32.0  | 3         | 2.8%    |
| 64.01-256.0 | 2         | 1.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 61        | 48.03%  |
| 2.01-3.0  | 24        | 18.9%   |
| 3.01-4.0  | 17        | 13.39%  |
| 4.01-8.0  | 14        | 11.02%  |
| 0.51-1.0  | 9         | 7.09%   |
| 8.01-16.0 | 2         | 1.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 63        | 56.76%  |
| 2      | 25        | 22.52%  |
| 3      | 15        | 13.51%  |
| 4      | 5         | 4.5%    |
| 6      | 1         | 0.9%    |
| 5      | 1         | 0.9%    |
| 0      | 1         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 50%     |
| No        | 52        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 88.35%  |
| No        | 12        | 11.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 74.29%  |
| No        | 27        | 25.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 57.55%  |
| No        | 45        | 42.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Puerto Rico | 103       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San Juan      | 43        | 37.72%  |
| Bayamón      | 20        | 17.54%  |
| Carolina      | 9         | 7.89%   |
| Ponce         | 4         | 3.51%   |
| Cayey         | 4         | 3.51%   |
| Caguas        | 4         | 3.51%   |
| Aguadilla     | 3         | 2.63%   |
| Vega Alta     | 2         | 1.75%   |
| Sabana Grande | 2         | 1.75%   |
| Mayagüez     | 2         | 1.75%   |
| Lares         | 2         | 1.75%   |
| Guayama       | 2         | 1.75%   |
| Dorado        | 2         | 1.75%   |
| San Sebastian | 1         | 0.88%   |
| Rio Grande    | 1         | 0.88%   |
| Patillas      | 1         | 0.88%   |
| Morovis       | 1         | 0.88%   |
| Maunabo       | 1         | 0.88%   |
| Las Piedras   | 1         | 0.88%   |
| Humacao       | 1         | 0.88%   |
| Hatillo       | 1         | 0.88%   |
| Gurabo        | 1         | 0.88%   |
| Fajardo       | 1         | 0.88%   |
| Ensenada      | 1         | 0.88%   |
| Coamo         | 1         | 0.88%   |
| Catano        | 1         | 0.88%   |
| Barceloneta   | 1         | 0.88%   |
| Arecibo       | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 31        | 72     | 20.39%  |
| Seagate                     | 20        | 37     | 13.16%  |
| Toshiba                     | 15        | 18     | 9.87%   |
| Samsung Electronics         | 11        | 20     | 7.24%   |
| Crucial                     | 9         | 13     | 5.92%   |
| Hitachi                     | 8         | 23     | 5.26%   |
| Unknown                     | 7         | 11     | 4.61%   |
| China                       | 5         | 8      | 3.29%   |
| A-DATA Technology           | 5         | 10     | 3.29%   |
| SanDisk                     | 4         | 4      | 2.63%   |
| Silicon Motion              | 3         | 3      | 1.97%   |
| Micron/Crucial Technology   | 3         | 4      | 1.97%   |
| External                    | 3         | 4      | 1.97%   |
| TDAS                        | 2         | 10     | 1.32%   |
| SABRENT                     | 2         | 3      | 1.32%   |
| PNY                         | 2         | 2      | 1.32%   |
| Phison                      | 2         | 2      | 1.32%   |
| LITEONIT                    | 2         | 2      | 1.32%   |
| Intel                       | 2         | 3      | 1.32%   |
| WD MediaMax                 | 1         | 3      | 0.66%   |
| W800SH                      | 1         | 1      | 0.66%   |
| USB3.0                      | 1         | 1      | 0.66%   |
| Team                        | 1         | 1      | 0.66%   |
| SK hynix                    | 1         | 2      | 0.66%   |
| Micron Technology           | 1         | 1      | 0.66%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.66%   |
| Kingston                    | 1         | 1      | 0.66%   |
| JMicron Technology          | 1         | 4      | 0.66%   |
| INTEL SS                    | 1         | 1      | 0.66%   |
| HGST                        | 1         | 1      | 0.66%   |
| Axiom                       | 1         | 3      | 0.66%   |
| Argon                       | 1         | 1      | 0.66%   |
| Apple                       | 1         | 1      | 0.66%   |
| addlink                     | 1         | 1      | 0.66%   |
| Unknown                     | 1         | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB         | 5         | 2.98%   |
| WDC WD5000LPVT-22G33T0 500GB         | 3         | 1.79%   |
| Toshiba DT01ACA100 1TB               | 3         | 1.79%   |
| External USB3.0 1TB                  | 3         | 1.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 1.19%   |
| WDC WDBNCE2500PNC 250GB SSD          | 2         | 1.19%   |
| WDC WD5000LPLX-22ZNTT0 500GB         | 2         | 1.19%   |
| WDC WD2500BEVS-60UST0 250GB          | 2         | 1.19%   |
| Unknown MMC Card  2GB                | 2         | 1.19%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.19%   |
| Toshiba MK3261GSYN 320GB             | 2         | 1.19%   |
| Toshiba DT01ACA050 500GB             | 2         | 1.19%   |
| TDAS TerraMaster 1TB                 | 2         | 1.19%   |
| Seagate ST320DM001 HD322GJ 320GB     | 2         | 1.19%   |
| Seagate ST2000VM003-1CT164 2TB       | 2         | 1.19%   |
| Seagate Expansion 1TB                | 2         | 1.19%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.19%   |
| Samsung NVMe SSD Drive 500GB         | 2         | 1.19%   |
| SABRENT Disk 1TB                     | 2         | 1.19%   |
| Micron/Crucial NVMe SSD Drive 500GB  | 2         | 1.19%   |
| Hitachi HTS547550A9E384 500GB        | 2         | 1.19%   |
| Crucial CT240M500SSD1 240GB          | 2         | 1.19%   |
| China SATA SSD 512GB                 | 2         | 1.19%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.6%    |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 0.6%    |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 0.6%    |
| WDC WD5000BPVT-75HXZT1 500GB         | 1         | 0.6%    |
| WDC WD40EZRZ-22GXCB0 4TB             | 1         | 0.6%    |
| WDC WD30EZRZ-00WN9B0 3TB             | 1         | 0.6%    |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.6%    |
| WDC WD1600AAJS-00PSA0 160GB          | 1         | 0.6%    |
| WDC WD1500HLFS-01G6U1 150GB          | 1         | 0.6%    |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 0.6%    |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.6%    |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.6%    |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.6%    |
| WDC WD10SPCX-75KHST0 1TB             | 1         | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.6%    |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-75WN4A1 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.6%    |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 0.6%    |
| WDC WD10EAVS-00D7B1 1TB              | 1         | 0.6%    |
| WDC WD1003FBYZ-010FB0 1TB            | 1         | 0.6%    |
| WDC WD1003FBYX-05Y7B0 1TB            | 1         | 0.6%    |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1         | 0.6%    |
| WD MediaMax WL500GSA3272 500GB       | 1         | 0.6%    |
| W800SH 512GB SSD                     | 1         | 0.6%    |
| USB3.0 Super Speed 1TB               | 1         | 0.6%    |
| Unknown MMC Card  64GB               | 1         | 0.6%    |
| Unknown MMC Card  32GB               | 1         | 0.6%    |
| Unknown MMC Card  10GB               | 1         | 0.6%    |
| Unknown HBG4a2  32GB                 | 1         | 0.6%    |
| Unknown Externa 250GB                | 1         | 0.6%    |
| Unknown DA4064  64GB                 | 1         | 0.6%    |
| Toshiba MQ04ABF100 1TB               | 1         | 0.6%    |
| Toshiba MQ01ABF050 500GB             | 1         | 0.6%    |
| Toshiba MK3276GSX 320GB              | 1         | 0.6%    |
| Toshiba MK3254GSY 320GB              | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 62     | 34.72%  |
| Seagate             | 20        | 37     | 27.78%  |
| Toshiba             | 14        | 17     | 19.44%  |
| Hitachi             | 8         | 23     | 11.11%  |
| SABRENT             | 2         | 3      | 2.78%   |
| Samsung Electronics | 1         | 1      | 1.39%   |
| HGST                | 1         | 1      | 1.39%   |
| Apple               | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 13     | 21.43%  |
| Samsung Electronics | 7         | 11     | 16.67%  |
| WDC                 | 5         | 8      | 11.9%   |
| China               | 5         | 8      | 11.9%   |
| A-DATA Technology   | 5         | 10     | 11.9%   |
| SanDisk             | 2         | 2      | 4.76%   |
| PNY                 | 2         | 2      | 4.76%   |
| LITEONIT            | 2         | 2      | 4.76%   |
| W800SH              | 1         | 1      | 2.38%   |
| USB3.0              | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| INTEL SS            | 1         | 1      | 2.38%   |
| Argon               | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 145    | 45.71%  |
| SSD     | 39        | 61     | 27.86%  |
| NVMe    | 24        | 35     | 17.14%  |
| MMC     | 7         | 10     | 5%      |
| Unknown | 6         | 22     | 4.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 203    | 68.18%  |
| NVMe | 21        | 31     | 15.91%  |
| SAS  | 14        | 29     | 10.61%  |
| MMC  | 7         | 10     | 5.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 103    | 53.7%   |
| 0.51-1.0   | 37        | 74     | 34.26%  |
| 1.01-2.0   | 9         | 20     | 8.33%   |
| 3.01-4.0   | 3         | 8      | 2.78%   |
| 2.01-3.0   | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 21.43%  |
| 101-250        | 26        | 20.63%  |
| 501-1000       | 23        | 18.25%  |
| 1-20           | 12        | 9.52%   |
| 1001-2000      | 11        | 8.73%   |
| 2001-3000      | 9         | 7.14%   |
| More than 3000 | 8         | 6.35%   |
| 51-100         | 4         | 3.17%   |
| 21-50          | 3         | 2.38%   |
| Unknown        | 3         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 35.38%  |
| 21-50     | 24        | 18.46%  |
| 101-250   | 14        | 10.77%  |
| 51-100    | 13        | 10%     |
| 251-500   | 12        | 9.23%   |
| 501-1000  | 10        | 7.69%   |
| 1001-2000 | 7         | 5.38%   |
| Unknown   | 3         | 2.31%   |
| 2001-3000 | 1         | 0.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 8.33%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 8.33%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 8.33%   |
| Seagate ST320DM001 HD322GJ 320GB                 | 1         | 1      | 8.33%   |
| Seagate ST2000VM003-1CT164 2TB                   | 1         | 1      | 8.33%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 1      | 8.33%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 8.33%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 8.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 8.33%   |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 8.33%   |
| A-DATA Technology SU630 240GB SSD                | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 40%     |
| WDC                 | 1         | 1      | 10%     |
| Toshiba             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 57.14%  |
| WDC     | 1         | 1      | 14.29%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 9      | 70%     |
| SSD  | 3         | 3      | 30%     |

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
| Detected | 81        | 228    | 71.68%  |
| Works    | 22        | 33     | 19.47%  |
| Malfunc  | 10        | 12     | 8.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 72        | 61.02%  |
| AMD                          | 23        | 19.49%  |
| Silicon Motion               | 4         | 3.39%   |
| Samsung Electronics          | 4         | 3.39%   |
| Phison Electronics           | 3         | 2.54%   |
| Micron/Crucial Technology    | 3         | 2.54%   |
| SanDisk                      | 2         | 1.69%   |
| Nvidia                       | 2         | 1.69%   |
| Toshiba America Info Systems | 1         | 0.85%   |
| SK hynix                     | 1         | 0.85%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.85%   |
| Kingston Technology Company  | 1         | 0.85%   |
| ASMedia Technology           | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 19        | 13.29%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 5.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 4.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 4.2%    |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 3.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 2.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 2.8%    |
| Phison E12 NVMe Controller                                                              | 3         | 2.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 2.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 2.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 2.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 2.1%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 2.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.4%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.4%    |
| AMD FCH IDE Controller                                                                  | 2         | 1.4%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.7%    |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.7%    |
| Nvidia CK804 Serial ATA Controller                                                      | 1         | 0.7%    |
| Nvidia CK804 IDE                                                                        | 1         | 0.7%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1002                                            | 1         | 0.7%    |
| Kingston Company KC2000 NVMe SSD                                                        | 1         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.7%    |
| Intel NVMe Optane Memory Series                                                         | 1         | 0.7%    |
| Intel Non-Volatile memory controller                                                    | 1         | 0.7%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1         | 0.7%    |
| Intel Comet Lake PCH-H RAID                                                             | 1         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.7%    |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 1         | 0.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.7%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 1         | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.7%    |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 75        | 59.52%  |
| NVMe | 21        | 16.67%  |
| IDE  | 18        | 14.29%  |
| RAID | 12        | 9.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 76        | 73.79%  |
| AMD    | 25        | 24.27%  |
| ARM    | 2         | 1.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 2.91%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 2.91%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 2.91%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.94%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 2         | 1.94%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2         | 1.94%   |
| ARM Processor                               | 2         | 1.94%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.94%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.94%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.94%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 2         | 1.94%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.97%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.97%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.97%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.97%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.97%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.97%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.97%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 0.97%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.97%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.97%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.97%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 0.97%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.97%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.97%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.97%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.97%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 0.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.97%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 0.97%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 0.97%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 0.97%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 0.97%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1         | 0.97%   |
| Intel Core i3-4020Y CPU @ 1.50GHz           | 1         | 0.97%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1         | 0.97%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 0.97%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 0.97%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 0.97%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1         | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 0.97%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 1         | 0.97%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 0.97%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 0.97%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1         | 0.97%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 0.97%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 19.42%  |
| Intel Celeron           | 14        | 13.59%  |
| Intel Core i7           | 11        | 10.68%  |
| Intel Core i3           | 11        | 10.68%  |
| Intel Core 2 Duo        | 7         | 6.8%    |
| Other                   | 5         | 4.85%   |
| AMD Ryzen 5             | 5         | 4.85%   |
| Intel Pentium Silver    | 4         | 3.88%   |
| AMD Ryzen 7             | 4         | 3.88%   |
| AMD Ryzen 3             | 4         | 3.88%   |
| AMD A8                  | 4         | 3.88%   |
| Intel Pentium Dual-Core | 2         | 1.94%   |
| Intel Pentium           | 2         | 1.94%   |
| AMD A6                  | 2         | 1.94%   |
| Intel Genuine           | 1         | 0.97%   |
| Intel Core 2            | 1         | 0.97%   |
| AMD Ryzen Threadripper  | 1         | 0.97%   |
| AMD G                   | 1         | 0.97%   |
| AMD FX                  | 1         | 0.97%   |
| AMD Athlon 64 X2        | 1         | 0.97%   |
| AMD Athlon              | 1         | 0.97%   |
| AMD A10                 | 1         | 0.97%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 55        | 53.4%   |
| 4      | 30        | 29.13%  |
| 6      | 9         | 8.74%   |
| 8      | 5         | 4.85%   |
| 1      | 3         | 2.91%   |
| 16     | 1         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 52.43%  |
| 1      | 49        | 47.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 96.15%  |
| Unknown        | 3         | 2.88%   |
| 32-bit         | 1         | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 21.3%   |
| 0x206a7    | 9         | 8.33%   |
| 0x306c3    | 6         | 5.56%   |
| 0x806e9    | 4         | 3.7%    |
| 0x706a1    | 4         | 3.7%    |
| 0x306a9    | 4         | 3.7%    |
| 0x20655    | 4         | 3.7%    |
| 0x1067a    | 4         | 3.7%    |
| 0x30678    | 3         | 2.78%   |
| 0x06001119 | 3         | 2.78%   |
| 0xa0671    | 2         | 1.85%   |
| 0x906ea    | 2         | 1.85%   |
| 0x806ea    | 2         | 1.85%   |
| 0x6fd      | 2         | 1.85%   |
| 0x406e3    | 2         | 1.85%   |
| 0x306d4    | 2         | 1.85%   |
| 0x08701013 | 2         | 1.85%   |
| 0x08108109 | 2         | 1.85%   |
| 0x06003106 | 2         | 1.85%   |
| 0xa0652    | 1         | 0.93%   |
| 0x906ed    | 1         | 0.93%   |
| 0x906e9    | 1         | 0.93%   |
| 0x906c0    | 1         | 0.93%   |
| 0x806ec    | 1         | 0.93%   |
| 0x806c1    | 1         | 0.93%   |
| 0x706e5    | 1         | 0.93%   |
| 0x6fb      | 1         | 0.93%   |
| 0x6e8      | 1         | 0.93%   |
| 0x506e3    | 1         | 0.93%   |
| 0x506c9    | 1         | 0.93%   |
| 0x406c4    | 1         | 0.93%   |
| 0x406c3    | 1         | 0.93%   |
| 0x40651    | 1         | 0.93%   |
| 0x30679    | 1         | 0.93%   |
| 0x20652    | 1         | 0.93%   |
| 0x10676    | 1         | 0.93%   |
| 0x08600106 | 1         | 0.93%   |
| 0x0810100b | 1         | 0.93%   |
| 0x08101007 | 1         | 0.93%   |
| 0x0800820d | 1         | 0.93%   |
| 0x08001137 | 1         | 0.93%   |
| 0x07030105 | 1         | 0.93%   |
| 0x06000852 | 1         | 0.93%   |
| 0x05000119 | 1         | 0.93%   |
| 0x03000027 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 11.65%  |
| SandyBridge   | 10        | 9.71%   |
| Penryn        | 8         | 7.77%   |
| Haswell       | 8         | 7.77%   |
| Silvermont    | 6         | 5.83%   |
| Zen+          | 5         | 4.85%   |
| Zen 2         | 5         | 4.85%   |
| Westmere      | 5         | 4.85%   |
| Goldmont plus | 5         | 4.85%   |
| Zen           | 4         | 3.88%   |
| Skylake       | 4         | 3.88%   |
| Piledriver    | 4         | 3.88%   |
| IvyBridge     | 4         | 3.88%   |
| Core          | 4         | 3.88%   |
| Unknown       | 3         | 2.91%   |
| Steamroller   | 2         | 1.94%   |
| IceLake       | 2         | 1.94%   |
| Broadwell     | 2         | 1.94%   |
| Zen 3         | 1         | 0.97%   |
| Tremont       | 1         | 0.97%   |
| TigerLake     | 1         | 0.97%   |
| Puma          | 1         | 0.97%   |
| P6            | 1         | 0.97%   |
| K8 Hammer     | 1         | 0.97%   |
| K10 Llano     | 1         | 0.97%   |
| Goldmont      | 1         | 0.97%   |
| CometLake     | 1         | 0.97%   |
| Bobcat        | 1         | 0.97%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 69        | 61.06%  |
| AMD    | 23        | 20.35%  |
| Nvidia | 21        | 18.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 8.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 4.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 4.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 3.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.48%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.48%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.48%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 1.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 1.65%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 2         | 1.65%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.65%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.65%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.65%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 1.65%   |
| Intel HD Graphics 620                                                                    | 2         | 1.65%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 1.65%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 2         | 1.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.83%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.83%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.83%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.83%   |
| Nvidia GK208 [GeForce GT 720]                                                            | 1         | 0.83%   |
| Nvidia GK110GL [Tesla K20Xm]                                                             | 1         | 0.83%   |
| Nvidia GK104GL [GRID K2]                                                                 | 1         | 0.83%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.83%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.83%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 1         | 0.83%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.83%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.83%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.83%   |
| Intel HD Graphics 630                                                                    | 1         | 0.83%   |
| Intel HD Graphics 500                                                                    | 1         | 0.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 0.83%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.83%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 0.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 59        | 56.19%  |
| 1 x AMD            | 20        | 19.05%  |
| 1 x Nvidia         | 12        | 11.43%  |
| Intel + Nvidia     | 6         | 5.71%   |
| Intel + AMD        | 3         | 2.86%   |
| Other              | 2         | 1.9%    |
| Intel + 2 x Nvidia | 2         | 1.9%    |
| 2 x Nvidia         | 1         | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 89        | 83.18%  |
| Proprietary | 12        | 11.21%  |
| Unknown     | 6         | 5.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 62.73%  |
| 0.01-0.5   | 11        | 10%     |
| 0.51-1.0   | 10        | 9.09%   |
| 1.01-2.0   | 8         | 7.27%   |
| 3.01-4.0   | 6         | 5.45%   |
| 5.01-6.0   | 3         | 2.73%   |
| 8.01-16.0  | 2         | 1.82%   |
| 2.01-3.0   | 1         | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 12        | 10.62%  |
| LG Display              | 9         | 7.96%   |
| Goldstar                | 9         | 7.96%   |
| Chimei Innolux          | 8         | 7.08%   |
| Dell                    | 7         | 6.19%   |
| AU Optronics            | 6         | 5.31%   |
| Acer                    | 6         | 5.31%   |
| Hewlett-Packard         | 5         | 4.42%   |
| BOE                     | 5         | 4.42%   |
| ViewSonic               | 4         | 3.54%   |
| Sony                    | 4         | 3.54%   |
| Apple                   | 4         | 3.54%   |
| AOC                     | 4         | 3.54%   |
| Vizio                   | 3         | 2.65%   |
| Sceptre Tech            | 3         | 2.65%   |
| Gateway                 | 3         | 2.65%   |
| Element                 | 3         | 2.65%   |
| VIZ                     | 2         | 1.77%   |
| Tech Concepts           | 2         | 1.77%   |
| eMachines               | 2         | 1.77%   |
| Unknown                 | 1         | 0.88%   |
| UGD                     | 1         | 0.88%   |
| Seiki                   | 1         | 0.88%   |
| RTK                     | 1         | 0.88%   |
| PANDA                   | 1         | 0.88%   |
| ONN                     | 1         | 0.88%   |
| MStar                   | 1         | 0.88%   |
| Lenovo                  | 1         | 0.88%   |
| InnoLux Display         | 1         | 0.88%   |
| Chi Mei Optoelectronics | 1         | 0.88%   |
| ASUSTek Computer        | 1         | 0.88%   |
| Ancor Communications    | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 4.2%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch            | 3         | 2.52%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 3         | 2.52%   |
| Element ELEFW328B ELE1366 1366x768 700x400mm 31.7-inch                 | 3         | 2.52%   |
| VIZ LCD Monitor M551d-A2R                                              | 2         | 1.68%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch          | 2         | 1.68%   |
| Sony TV  *00 SNY4B04 3840x2160                                         | 2         | 1.68%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch      | 2         | 1.68%   |
| Gateway LCD Monitor FHX2300                                            | 2         | 1.68%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                  | 2         | 1.68%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 2         | 1.68%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch                | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.68%   |
| Acer LCD Monitor G236HL 5760x1080                                      | 2         | 1.68%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                   | 1         | 0.84%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1         | 0.84%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                    | 1         | 0.84%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch               | 1         | 0.84%   |
| ViewSonic VA1930wm VSC171F 1440x900 410x260mm 19.1-inch                | 1         | 0.84%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                            | 1         | 0.84%   |
| UGD Artist 156 UGD1501 1920x1080 293x165mm 13.2-inch                   | 1         | 0.84%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                             | 1         | 0.84%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                             | 1         | 0.84%   |
| Sony TV SNYEA01 1920x1080                                              | 1         | 0.84%   |
| Sony TV SNY4502 1920x1080                                              | 1         | 0.84%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                    | 1         | 0.84%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch       | 1         | 0.84%   |
| Sceptre Tech Sceptre C27 SPT0AD7 1920x1080 598x336mm 27.0-inch         | 1         | 0.84%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                 | 1         | 0.84%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch      | 1         | 0.84%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1210x680mm 54.6-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 0.84%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1         | 0.84%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                   | 1         | 0.84%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch                | 1         | 0.84%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                 | 1         | 0.84%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 1         | 0.84%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD051E 3840x2160 309x174mm 14.0-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch            | 1         | 0.84%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                | 1         | 0.84%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch       | 1         | 0.84%   |
| Hewlett-Packard P17A HWP3142 1280x1024 338x270mm 17.0-inch             | 1         | 0.84%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 1         | 0.84%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch          | 1         | 0.84%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 553x311mm 25.0-inch             | 1         | 0.84%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 0.84%   |
| Goldstar W2240 GSM57A1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.84%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1         | 0.84%   |
| Gateway LCD Monitor FHX2300 3840x1080                                  | 1         | 0.84%   |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                     | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 42.31%  |
| 1366x768 (WXGA)    | 23        | 22.12%  |
| 3840x2160 (4K)     | 11        | 10.58%  |
| 1440x900 (WXGA+)   | 6         | 5.77%   |
| 1600x900 (HD+)     | 4         | 3.85%   |
| 1280x800 (WXGA)    | 4         | 3.85%   |
| 5760x1080          | 2         | 1.92%   |
| 1280x1024 (SXGA)   | 2         | 1.92%   |
| Unknown            | 2         | 1.92%   |
| 3840x1080          | 1         | 0.96%   |
| 3440x1440          | 1         | 0.96%   |
| 2560x1440 (QHD)    | 1         | 0.96%   |
| 2560x1080          | 1         | 0.96%   |
| 1680x1050 (WSXGA+) | 1         | 0.96%   |
| 1280x720 (HD)      | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 20.91%  |
| 21      | 14        | 12.73%  |
| 23      | 10        | 9.09%   |
| 72      | 7         | 6.36%   |
| 17      | 7         | 6.36%   |
| 14      | 7         | 6.36%   |
| 31      | 6         | 5.45%   |
| 19      | 5         | 4.55%   |
| Unknown | 5         | 4.55%   |
| 27      | 4         | 3.64%   |
| 20      | 4         | 3.64%   |
| 13      | 4         | 3.64%   |
| 34      | 2         | 1.82%   |
| 18      | 2         | 1.82%   |
| 11      | 2         | 1.82%   |
| 84      | 1         | 0.91%   |
| 64      | 1         | 0.91%   |
| 52      | 1         | 0.91%   |
| 49      | 1         | 0.91%   |
| 32      | 1         | 0.91%   |
| 25      | 1         | 0.91%   |
| 24      | 1         | 0.91%   |
| 22      | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 28.7%   |
| 401-500     | 25        | 23.15%  |
| 501-600     | 15        | 13.89%  |
| 1501-2000   | 8         | 7.41%   |
| 351-400     | 7         | 6.48%   |
| 601-700     | 6         | 5.56%   |
| 201-300     | 5         | 4.63%   |
| Unknown     | 5         | 4.63%   |
| 701-800     | 3         | 2.78%   |
| 1001-1500   | 3         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 75        | 77.32%  |
| 16/10   | 12        | 12.37%  |
| Unknown | 5         | 5.15%   |
| 5/4     | 3         | 3.09%   |
| 21/9    | 2         | 2.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 21.1%   |
| 201-250        | 22        | 20.18%  |
| 151-200        | 13        | 11.93%  |
| More than 1000 | 10        | 9.17%   |
| 81-90          | 10        | 9.17%   |
| 351-500        | 9         | 8.26%   |
| Unknown        | 5         | 4.59%   |
| 301-350        | 4         | 3.67%   |
| 141-150        | 4         | 3.67%   |
| 121-130        | 4         | 3.67%   |
| 51-60          | 2         | 1.83%   |
| 71-80          | 1         | 0.92%   |
| 251-300        | 1         | 0.92%   |
| 131-140        | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 41        | 39.05%  |
| 51-100        | 33        | 31.43%  |
| 121-160       | 13        | 12.38%  |
| 1-50          | 10        | 9.52%   |
| Unknown       | 5         | 4.76%   |
| 161-240       | 2         | 1.9%    |
| More than 240 | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 77.57%  |
| 2     | 18        | 16.82%  |
| 0     | 4         | 3.74%   |
| 3     | 2         | 1.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 66        | 39.05%  |
| Intel                    | 53        | 31.36%  |
| Qualcomm Atheros         | 15        | 8.88%   |
| Broadcom                 | 7         | 4.14%   |
| Ralink Technology        | 5         | 2.96%   |
| NetGear                  | 5         | 2.96%   |
| Marvell Technology Group | 3         | 1.78%   |
| Broadcom Limited         | 3         | 1.78%   |
| TP-Link                  | 2         | 1.18%   |
| Samsung Electronics      | 2         | 1.18%   |
| Nvidia                   | 2         | 1.18%   |
| Ralink                   | 1         | 0.59%   |
| Gemtek                   | 1         | 0.59%   |
| Dell                     | 1         | 0.59%   |
| Belkin Components        | 1         | 0.59%   |
| ASIX Electronics         | 1         | 0.59%   |
| Aquantia                 | 1         | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 42        | 21.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 4.17%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 2.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 4         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 2.08%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 2.08%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 4         | 2.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 3         | 1.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 1.56%   |
| Intel Wireless 7265                                                            | 3         | 1.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 1.56%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 1.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 1.04%   |
| Realtek 802.11ac NIC                                                           | 2         | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2         | 1.04%   |
| NetGear LB1120-100NAS                                                          | 2         | 1.04%   |
| Intel Wireless 3160                                                            | 2         | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.04%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 2         | 1.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.04%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                  | 2         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.04%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                        | 2         | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.52%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                     | 1         | 0.52%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1         | 0.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.52%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                         | 1         | 0.52%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.52%   |
| Ralink RT2870 Wireless Adapter                                                 | 1         | 0.52%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                              | 1         | 0.52%   |
| Ralink MT7601U Wireless Adapter                                                | 1         | 0.52%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 1         | 0.52%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                     | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.52%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.52%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 0.52%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                               | 1         | 0.52%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                    | 1         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 37.36%  |
| Realtek Semiconductor | 23        | 25.27%  |
| Qualcomm Atheros      | 12        | 13.19%  |
| Broadcom              | 6         | 6.59%   |
| Ralink Technology     | 5         | 5.49%   |
| NetGear               | 3         | 3.3%    |
| TP-Link               | 2         | 2.2%    |
| Broadcom Limited      | 2         | 2.2%    |
| Ralink                | 1         | 1.1%    |
| Gemtek                | 1         | 1.1%    |
| Dell                  | 1         | 1.1%    |
| Belkin Components     | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                     | Computers | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                       | 6         | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                | 5         | 5.21%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                        | 4         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                  | 4         | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                          | 4         | 4.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                   | 3         | 3.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                | 3         | 3.13%   |
| Intel Wireless 7265                                                                       | 3         | 3.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                           | 2         | 2.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                     | 2         | 2.08%   |
| Realtek 802.11ac NIC                                                                      | 2         | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                     | 2         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                | 2         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                | 2         | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                          | 2         | 2.08%   |
| Intel Wireless 3160                                                                       | 2         | 2.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                     | 2         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                                            | 2         | 2.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                             | 2         | 2.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                              | 2         | 2.08%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                             | 2         | 2.08%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                                   | 2         | 2.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                              | 1         | 1.04%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                | 1         | 1.04%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                   | 1         | 1.04%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                | 1         | 1.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                           | 1         | 1.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                    | 1         | 1.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                               | 1         | 1.04%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                    | 1         | 1.04%   |
| Realtek RTL8187 Wireless Adapter                                                          | 1         | 1.04%   |
| Ralink RT2870 Wireless Adapter                                                            | 1         | 1.04%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                         | 1         | 1.04%   |
| Ralink MT7601U Wireless Adapter                                                           | 1         | 1.04%   |
| Ralink RT2561/RT61 802.11g PCI                                                            | 1         | 1.04%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                | 1         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                          | 1         | 1.04%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                     | 1         | 1.04%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                                          | 1         | 1.04%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                               | 1         | 1.04%   |
| Intel Wireless 8265 / 8275                                                                | 1         | 1.04%   |
| Intel Wireless 7260                                                                       | 1         | 1.04%   |
| Intel Wireless 3165                                                                       | 1         | 1.04%   |
| Intel WiFi Link 5100                                                                      | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                                                | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201                                                                       | 1         | 1.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                                            | 1         | 1.04%   |
| Intel Gemini Lake PCH CNVi WiFi                                                           | 1         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                         | 1         | 1.04%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                         | 1         | 1.04%   |
| Dell Wireless 5808e Gobiâ¢ 4G LTE Mobile Broadband Card                               | 1         | 1.04%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                        | 1         | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                                            | 1         | 1.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                    | 1         | 1.04%   |
| Broadcom BCM4321 802.11a/b/g/n                                                            | 1         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                                             | 1         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                       | 1         | 1.04%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU] | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 55.21%  |
| Intel                    | 25        | 26.04%  |
| Qualcomm Atheros         | 3         | 3.13%   |
| Marvell Technology Group | 3         | 3.13%   |
| Broadcom                 | 3         | 3.13%   |
| Samsung Electronics      | 2         | 2.08%   |
| Nvidia                   | 2         | 2.08%   |
| NetGear                  | 2         | 2.08%   |
| Broadcom Limited         | 1         | 1.04%   |
| ASIX Electronics         | 1         | 1.04%   |
| Aquantia                 | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 42        | 43.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 6.25%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 4.17%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 4.17%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 3.13%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.08%   |
| NetGear LB1120-100NAS                                                          | 2         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.04%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.04%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.04%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.04%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 1.04%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.04%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.04%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.04%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.04%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 1.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 1.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.04%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.04%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.04%   |
| ASIX AX88772B                                                                  | 1         | 1.04%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 91        | 53.85%  |
| WiFi     | 78        | 46.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 51.35%  |
| Ethernet | 54        | 48.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 52        | 49.52%  |
| 1     | 47        | 44.76%  |
| 3     | 3         | 2.86%   |
| 0     | 3         | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 96.12%  |
| Yes  | 4         | 3.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 45.31%  |
| Realtek Semiconductor           | 7         | 10.94%  |
| Cambridge Silicon Radio         | 7         | 10.94%  |
| Qualcomm Atheros Communications | 5         | 7.81%   |
| Lite-On Technology              | 3         | 4.69%   |
| Apple                           | 3         | 4.69%   |
| Foxconn / Hon Hai               | 2         | 3.13%   |
| Broadcom                        | 2         | 3.13%   |
| Toshiba                         | 1         | 1.56%   |
| IMC Networks                    | 1         | 1.56%   |
| Hewlett-Packard                 | 1         | 1.56%   |
| Dynex                           | 1         | 1.56%   |
| Belkin Components               | 1         | 1.56%   |
| Alps Electric                   | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 8         | 12.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 10.94%  |
| Intel AX200 Bluetooth                                                               | 6         | 9.38%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 7.81%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 6.25%   |
| Intel Bluetooth Device                                                              | 4         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 6.25%   |
| Intel AX201 Bluetooth                                                               | 3         | 4.69%   |
| Lite-On Bluetooth Device                                                            | 2         | 3.13%   |
| Broadcom Bluetooth Device                                                           | 2         | 3.13%   |
| Apple Bluetooth Host Controller                                                     | 2         | 3.13%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.56%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.56%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.56%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.56%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 1.56%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 1.56%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.56%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 75        | 58.14%  |
| AMD                                             | 25        | 19.38%  |
| Nvidia                                          | 17        | 13.18%  |
| Logitech                                        | 6         | 4.65%   |
| C-Media Electronics                             | 2         | 1.55%   |
| Nintendo                                        | 1         | 0.78%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.78%   |
| Kingston Technology                             | 1         | 0.78%   |
| Focusrite-Novation                              | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 5.7%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 5.06%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.53%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.53%   |
| Logitech EasyCall Speakerphone                                                                    | 3         | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.9%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.9%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.27%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 1.27%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.27%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.27%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.27%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.63%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nintendo WUP-021-0                                                                                | 1         | 0.63%   |
| Logitech QuickCam Fusion                                                                          | 1         | 0.63%   |
| Logitech Headset H390                                                                             | 1         | 0.63%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.63%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset                           | 1         | 0.63%   |
| Kingston Technology HyperX SoloCast                                                               | 1         | 0.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.63%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.63%   |
| Intel Audio device                                                                                | 1         | 0.63%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.63%   |
| Focusrite-Novation Scarlett 18i8 2nd Gen                                                          | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 25%     |
| SK hynix            | 8         | 22.22%  |
| Unknown             | 7         | 19.44%  |
| Kingston            | 3         | 8.33%   |
| G.Skill             | 2         | 5.56%   |
| Corsair             | 2         | 5.56%   |
| Sesame              | 1         | 2.78%   |
| PNY                 | 1         | 2.78%   |
| Micron Technology   | 1         | 2.78%   |
| Crucial             | 1         | 2.78%   |
| A-DATA Technology   | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 3         | 7.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 4.88%   |
| Unknown RAM WPBS26D408SWC-8G 8192MB SODIMM DDR4 2667MT/s  | 1         | 2.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1         | 2.44%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1         | 2.44%   |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s  | 1         | 2.44%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 2.44%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1         | 2.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1         | 2.44%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 2.44%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8192MB SODIMM DDR4 2667MT/s | 1         | 2.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 2.44%   |
| Sesame RAM S939A2UGS-ITR 8192MB DIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s  | 1         | 2.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1         | 2.44%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1         | 2.44%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1         | 2.44%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 2.44%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 2.44%   |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s           | 1         | 2.44%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 3200MT/s        | 1         | 2.44%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 2.44%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1         | 2.44%   |
| G.Skill RAM F3-10666CL9-8GBSQ 8GB DIMM DDR3 1333MT/s      | 1         | 2.44%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1         | 2.44%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 1         | 2.44%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s       | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 15        | 41.67%  |
| DDR4    | 14        | 38.89%  |
| SDRAM   | 3         | 8.33%   |
| LPDDR4  | 2         | 5.56%   |
| DDR     | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 19        | 54.29%  |
| SODIMM | 16        | 45.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 16        | 43.24%  |
| 8192  | 15        | 40.54%  |
| 2048  | 5         | 13.51%  |
| 16384 | 1         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 29.73%  |
| 2667    | 7         | 18.92%  |
| 3200    | 4         | 10.81%  |
| 1333    | 3         | 8.11%   |
| Unknown | 3         | 8.11%   |
| 3600    | 2         | 5.41%   |
| 667     | 2         | 5.41%   |
| 3466    | 1         | 2.7%    |
| 3266    | 1         | 2.7%    |
| 1867    | 1         | 2.7%    |
| 1866    | 1         | 2.7%    |
| 800     | 1         | 2.7%    |

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
| Chicony Electronics                    | 9         | 16.98%  |
| Microdia                               | 6         | 11.32%  |
| Ricoh                                  | 5         | 9.43%   |
| Logitech                               | 5         | 9.43%   |
| Realtek Semiconductor                  | 4         | 7.55%   |
| Quanta                                 | 3         | 5.66%   |
| Apple                                  | 3         | 5.66%   |
| Acer                                   | 3         | 5.66%   |
| Suyin                                  | 2         | 3.77%   |
| Sunplus Innovation Technology          | 2         | 3.77%   |
| Lite-On Technology                     | 2         | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.77%   |
| Luxvisions Innotech Limited            | 1         | 1.89%   |
| Lenovo                                 | 1         | 1.89%   |
| Jieli Technology                       | 1         | 1.89%   |
| IMC Networks                           | 1         | 1.89%   |
| Goertek Electronics                    | 1         | 1.89%   |
| Cubeternet                             | 1         | 1.89%   |
| Alpha Imaging Technology               | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Camera                                                 | 4         | 7.55%   |
| Ricoh Integrated Webcam                                         | 3         | 5.66%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 3.77%   |
| Chicony HD WebCam                                               | 2         | 3.77%   |
| Suyin USB 2.0 Camera                                            | 1         | 1.89%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 1.89%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam        | 1         | 1.89%   |
| Ricoh HD Webcam                                                 | 1         | 1.89%   |
| Realtek MTD camera                                              | 1         | 1.89%   |
| Realtek Integrated Webcam HD                                    | 1         | 1.89%   |
| Realtek Integrated Webcam                                       | 1         | 1.89%   |
| Realtek HP Webcam-101                                           | 1         | 1.89%   |
| Quanta HP Wide Vision HD Camera                                 | 1         | 1.89%   |
| Quanta HP TrueVision HD Camera                                  | 1         | 1.89%   |
| Quanta HD WebCam                                                | 1         | 1.89%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 1         | 1.89%   |
| Microdia HDP Webcam USB                                         | 1         | 1.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 1.89%   |
| Logitech Webcam Pro 9000                                        | 1         | 1.89%   |
| Logitech Webcam C310                                            | 1         | 1.89%   |
| Logitech Webcam C270                                            | 1         | 1.89%   |
| Logitech HD Pro Webcam C920                                     | 1         | 1.89%   |
| Logitech CrystalCam                                             | 1         | 1.89%   |
| Lite-On HP Wide Vision HD Camera                                | 1         | 1.89%   |
| Lite-On HP HD Webcam                                            | 1         | 1.89%   |
| Lenovo Integrated Webcam [R5U877]                               | 1         | 1.89%   |
| Jieli USB PHY 2.0                                               | 1         | 1.89%   |
| IMC Networks UVC VGA Webcam                                     | 1         | 1.89%   |
| Goertek USB2.0 VGA UVC WebCam                                   | 1         | 1.89%   |
| Cubeternet GL-UPC822 UVC WebCam                                 | 1         | 1.89%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 1.89%   |
| Chicony Toshiba Integrated Webcam                               | 1         | 1.89%   |
| Chicony Integrated HP HD Webcam                                 | 1         | 1.89%   |
| Chicony HP Webcam                                               | 1         | 1.89%   |
| Chicony HP Truevision HD                                        | 1         | 1.89%   |
| Chicony EasyCamera                                              | 1         | 1.89%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 1.89%   |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 1.89%   |
| Apple FaceTime HD Camera                                        | 1         | 1.89%   |
| Apple Built-in iSight                                           | 1         | 1.89%   |
| Alpha Imaging Integrated_Webcam_8M                              | 1         | 1.89%   |
| Acer Lenovo EasyCamera                                          | 1         | 1.89%   |
| Acer EasyCamera                                                 | 1         | 1.89%   |
| Acer BisonCam,NB Pro                                            | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 70%     |
| LighTuning Technology | 2         | 20%     |
| Synaptics             | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 3         | 30%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 2         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader  | 1         | 10%     |
| Validity Sensors Synaptics WBDI             | 1         | 10%     |
| Validity Sensors Fingerprint scanner        | 1         | 10%     |
| Unknown                                     | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 75        | 66.96%  |
| 1     | 33        | 29.46%  |
| 2     | 4         | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 16        | 42.11%  |
| Fingerprint reader       | 10        | 26.32%  |
| Graphics card            | 7         | 18.42%  |
| Communication controller | 2         | 5.26%   |
| Net/ethernet             | 1         | 2.63%   |
| Multimedia controller    | 1         | 2.63%   |
| Chipcard                 | 1         | 2.63%   |

