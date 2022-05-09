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

Total: 228

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4ce6a4f767](https://linux-hardware.org/?probe=4ce6a4f767) | Feb 21, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7e016ec31](https://linux-hardware.org/?probe=f7e016ec31) | Feb 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a1ecd8a3cb](https://linux-hardware.org/?probe=a1ecd8a3cb) | Feb 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [e7ce3f2f38](https://linux-hardware.org/?probe=e7ce3f2f38) | Feb 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [86dbaf1d07](https://linux-hardware.org/?probe=86dbaf1d07) | Jan 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [51e8a3a34d](https://linux-hardware.org/?probe=51e8a3a34d) | Dec 31, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [2dbfd6ad98](https://linux-hardware.org/?probe=2dbfd6ad98) | Dec 27, 2021 |
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
| HP            | 339A                        | Desktop     | [98dd1a692c](https://linux-hardware.org/?probe=98dd1a692c) | Oct 13, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [29c7fa76a8](https://linux-hardware.org/?probe=29c7fa76a8) | Oct 10, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [6818ec3abc](https://linux-hardware.org/?probe=6818ec3abc) | Oct 10, 2021 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [732c00f018](https://linux-hardware.org/?probe=732c00f018) | Oct 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [7ecda0a147](https://linux-hardware.org/?probe=7ecda0a147) | Sep 23, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [9ed2b3cf12](https://linux-hardware.org/?probe=9ed2b3cf12) | Sep 21, 2021 |
| GPU Compan... | GWTN156-9                   | Notebook    | [a9ac79c22a](https://linux-hardware.org/?probe=a9ac79c22a) | Sep 21, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [a96d28c504](https://linux-hardware.org/?probe=a96d28c504) | Sep 16, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [61b68fb93b](https://linux-hardware.org/?probe=61b68fb93b) | Sep 14, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [686eb55129](https://linux-hardware.org/?probe=686eb55129) | Sep 04, 2021 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [5f87a353c8](https://linux-hardware.org/?probe=5f87a353c8) | Aug 11, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d120a0016d](https://linux-hardware.org/?probe=d120a0016d) | Aug 05, 2021 |
| HP            | ProBook 6450b               | Notebook    | [97ffc89a3a](https://linux-hardware.org/?probe=97ffc89a3a) | Aug 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [2340805fcb](https://linux-hardware.org/?probe=2340805fcb) | Aug 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [1f804fb86d](https://linux-hardware.org/?probe=1f804fb86d) | Jul 31, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [9ad69ca6ad](https://linux-hardware.org/?probe=9ad69ca6ad) | Jul 27, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [75fd544183](https://linux-hardware.org/?probe=75fd544183) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [c58485ad5c](https://linux-hardware.org/?probe=c58485ad5c) | Jul 23, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| HP            | ProBook 6450b               | Notebook    | [b3e8452ed2](https://linux-hardware.org/?probe=b3e8452ed2) | Jul 16, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [5bf401c4d4](https://linux-hardware.org/?probe=5bf401c4d4) | Jul 16, 2021 |
| HP            | ProBook 6450b               | Notebook    | [351a0db115](https://linux-hardware.org/?probe=351a0db115) | Jul 13, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a3b055840b](https://linux-hardware.org/?probe=a3b055840b) | Jul 13, 2021 |
| Sony          | VPCEB36GM                   | Notebook    | [91fa4f16d1](https://linux-hardware.org/?probe=91fa4f16d1) | Jul 08, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [cbcf0ae65d](https://linux-hardware.org/?probe=cbcf0ae65d) | Jul 07, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [c3b8ac12be](https://linux-hardware.org/?probe=c3b8ac12be) | Jul 07, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3a88077121](https://linux-hardware.org/?probe=3a88077121) | Jul 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [17a65dfb0e](https://linux-hardware.org/?probe=17a65dfb0e) | Jul 06, 2021 |
| HP            | ProBook 6450b               | Notebook    | [27e51eb49f](https://linux-hardware.org/?probe=27e51eb49f) | Jul 06, 2021 |
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
| HP            | 1998                        | Desktop     | [4635fe4a94](https://linux-hardware.org/?probe=4635fe4a94) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| HP            | 1998                        | Desktop     | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Lenovo        | ThinkPad T410 2516ADU       | Notebook    | [5feb962d24](https://linux-hardware.org/?probe=5feb962d24) | Apr 07, 2021 |
| Intel         | SKYBAY                      | Desktop     | [472818e347](https://linux-hardware.org/?probe=472818e347) | Apr 04, 2021 |
| Intel         | SKYBAY                      | Desktop     | [870238bbc7](https://linux-hardware.org/?probe=870238bbc7) | Apr 03, 2021 |
| HP            | 1998                        | Desktop     | [efbca1346b](https://linux-hardware.org/?probe=efbca1346b) | Apr 01, 2021 |
| HP            | 1998                        | Desktop     | [f515fbf660](https://linux-hardware.org/?probe=f515fbf660) | Apr 01, 2021 |
| Intel         | SKYBAY                      | Desktop     | [3170801868](https://linux-hardware.org/?probe=3170801868) | Mar 23, 2021 |
| HP            | 1998                        | Desktop     | [3bc0a0dcb6](https://linux-hardware.org/?probe=3bc0a0dcb6) | Mar 20, 2021 |
| HP            | 1998                        | Desktop     | [a10d91fc1b](https://linux-hardware.org/?probe=a10d91fc1b) | Mar 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [2c5223d3c3](https://linux-hardware.org/?probe=2c5223d3c3) | Mar 18, 2021 |
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
| Unknown       | Raspberry Pi                | Soc         | [63a2a56eda](https://linux-hardware.org/?probe=63a2a56eda) | Jan 25, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [b2513f813d](https://linux-hardware.org/?probe=b2513f813d) | Jan 16, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0523ff890c](https://linux-hardware.org/?probe=0523ff890c) | Jan 15, 2021 |
| HP            | 18E4                        | Desktop     | [729391b32e](https://linux-hardware.org/?probe=729391b32e) | Jan 08, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [5780c56d1e](https://linux-hardware.org/?probe=5780c56d1e) | Jan 06, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [ecaae6f562](https://linux-hardware.org/?probe=ecaae6f562) | Jan 05, 2021 |
| AMI           | Intel                       | Notebook    | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Lenovo        | Board                       | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
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
| Dell          | Latitude E6410              | Notebook    | [e62f3de07d](https://linux-hardware.org/?probe=e62f3de07d) | Nov 02, 2020 |
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
| Lenovo        | Board                       | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| HP            | 18E4                        | Desktop     | [277593bde6](https://linux-hardware.org/?probe=277593bde6) | Aug 07, 2020 |
| Acer          | Swift SF314-51              | Notebook    | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [319c98c8a1](https://linux-hardware.org/?probe=319c98c8a1) | Jul 24, 2020 |
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
| HP            | Notebook                    | Notebook    | [3a1b01aaad](https://linux-hardware.org/?probe=3a1b01aaad) | Apr 04, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e2de1ae596](https://linux-hardware.org/?probe=e2de1ae596) | Apr 04, 2020 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [725c46f74c](https://linux-hardware.org/?probe=725c46f74c) | Mar 18, 2020 |
| HP            | ENVY dv7                    | Notebook    | [34e75717fd](https://linux-hardware.org/?probe=34e75717fd) | Mar 14, 2020 |
| HP            | ENVY dv7                    | Notebook    | [97ae3dc919](https://linux-hardware.org/?probe=97ae3dc919) | Mar 14, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [44caca0bb1](https://linux-hardware.org/?probe=44caca0bb1) | Mar 12, 2020 |
| BESSTAR Te... | Cherry Trail CR             | Desktop     | [25f7a780e2](https://linux-hardware.org/?probe=25f7a780e2) | Mar 11, 2020 |
| BESSTAR Te... | Cherry Trail CR             | Desktop     | [0a4dcdb4af](https://linux-hardware.org/?probe=0a4dcdb4af) | Mar 11, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [3d3261ccc3](https://linux-hardware.org/?probe=3d3261ccc3) | Mar 09, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [f48a5318f4](https://linux-hardware.org/?probe=f48a5318f4) | Mar 08, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e56cb163ba](https://linux-hardware.org/?probe=e56cb163ba) | Mar 08, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [c0f180f342](https://linux-hardware.org/?probe=c0f180f342) | Mar 07, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [cb590554ed](https://linux-hardware.org/?probe=cb590554ed) | Mar 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [4ac0a3b1fe](https://linux-hardware.org/?probe=4ac0a3b1fe) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a2582aaec1](https://linux-hardware.org/?probe=a2582aaec1) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a63cd159a1](https://linux-hardware.org/?probe=a63cd159a1) | Mar 06, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [aa32ea3cb7](https://linux-hardware.org/?probe=aa32ea3cb7) | Mar 05, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [efa77a90cb](https://linux-hardware.org/?probe=efa77a90cb) | Mar 01, 2020 |
| HP            | 18E4                        | Desktop     | [44a166f15f](https://linux-hardware.org/?probe=44a166f15f) | Mar 01, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [aca2204df4](https://linux-hardware.org/?probe=aca2204df4) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [a89bcf9811](https://linux-hardware.org/?probe=a89bcf9811) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [40a8750e54](https://linux-hardware.org/?probe=40a8750e54) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [399d92cf32](https://linux-hardware.org/?probe=399d92cf32) | Feb 28, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [7c094d733b](https://linux-hardware.org/?probe=7c094d733b) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [ddebe02bcd](https://linux-hardware.org/?probe=ddebe02bcd) | Feb 28, 2020 |
| HP            | Notebook                    | Notebook    | [80f2a12798](https://linux-hardware.org/?probe=80f2a12798) | Feb 28, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [132413f9bd](https://linux-hardware.org/?probe=132413f9bd) | Feb 21, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [29208aee7d](https://linux-hardware.org/?probe=29208aee7d) | Feb 21, 2020 |
| HP            | 18E4                        | Desktop     | [ee3dae8f72](https://linux-hardware.org/?probe=ee3dae8f72) | Feb 17, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa684e430c](https://linux-hardware.org/?probe=fa684e430c) | Feb 13, 2020 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [2398dc17c1](https://linux-hardware.org/?probe=2398dc17c1) | Feb 03, 2020 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [f8e5a854ee](https://linux-hardware.org/?probe=f8e5a854ee) | Jan 30, 2020 |
| ASRock        | A780GXE/128M                | Desktop     | [2123239208](https://linux-hardware.org/?probe=2123239208) | Nov 10, 2019 |
| MSI           | B150 PC MATE                | Desktop     | [ed98074061](https://linux-hardware.org/?probe=ed98074061) | Oct 08, 2019 |
| ASRock        | G31M-S                      | Desktop     | [d1f69377d4](https://linux-hardware.org/?probe=d1f69377d4) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [595867810d](https://linux-hardware.org/?probe=595867810d) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [556d0f2ca6](https://linux-hardware.org/?probe=556d0f2ca6) | Jun 06, 2019 |
| ASRock        | 945GCM-S                    | Desktop     | [d4ea4c5cb6](https://linux-hardware.org/?probe=d4ea4c5cb6) | May 04, 2019 |
| HP            | 18E4                        | Desktop     | [36f9656af0](https://linux-hardware.org/?probe=36f9656af0) | Feb 15, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [d24fc7f682](https://linux-hardware.org/?probe=d24fc7f682) | Jan 30, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [525707b787](https://linux-hardware.org/?probe=525707b787) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [c5bc3970f7](https://linux-hardware.org/?probe=c5bc3970f7) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [a7616fb055](https://linux-hardware.org/?probe=a7616fb055) | Jan 21, 2019 |
| HP            | 18E4                        | Desktop     | [c0cc4f015a](https://linux-hardware.org/?probe=c0cc4f015a) | Jan 04, 2019 |
| HP            | 18E4                        | Desktop     | [c6cf9c7817](https://linux-hardware.org/?probe=c6cf9c7817) | Jan 04, 2019 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [85398272dc](https://linux-hardware.org/?probe=85398272dc) | Dec 03, 2018 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fcb5925cfa](https://linux-hardware.org/?probe=fcb5925cfa) | Dec 03, 2018 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [10a5b1559d](https://linux-hardware.org/?probe=10a5b1559d) | Dec 03, 2018 |
| Dell          | Inspiron MP061              | Notebook    | [113fc7a00d](https://linux-hardware.org/?probe=113fc7a00d) | Jul 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [82229858ec](https://linux-hardware.org/?probe=82229858ec) | Jun 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [b8b4c87a3c](https://linux-hardware.org/?probe=b8b4c87a3c) | Jun 15, 2018 |
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
| Ubuntu 20.04        | 24        | 19.51%  |
| Ubuntu 18.04        | 13        | 10.57%  |
| OpenMandriva 4.2    | 6         | 4.88%   |
| Ubuntu 21.10        | 4         | 3.25%   |
| Ubuntu 20.10        | 4         | 3.25%   |
| Manjaro             | 4         | 3.25%   |
| Linux Mint 19.3     | 4         | 3.25%   |
| Zorin 16            | 3         | 2.44%   |
| OpenMandriva 4.3    | 3         | 2.44%   |
| Linux Mint 20.1     | 3         | 2.44%   |
| BlackPanther 18.1   | 3         | 2.44%   |
| Xubuntu 20.04       | 2         | 1.63%   |
| Ubuntu 19.10        | 2         | 1.63%   |
| ROSA R11            | 2         | 1.63%   |
| ROSA R10            | 2         | 1.63%   |
| Lubuntu 20.04       | 2         | 1.63%   |
| LMDE 4              | 2         | 1.63%   |
| Linux Mint 20.3     | 2         | 1.63%   |
| Linux Mint 20.2     | 2         | 1.63%   |
| Linux Mint 20       | 2         | 1.63%   |
| KDE neon 20.04      | 2         | 1.63%   |
| Garuda Linux        | 2         | 1.63%   |
| ArcoLinux Rolling   | 2         | 1.63%   |
| Zorin 15            | 1         | 0.81%   |
| Xubuntu 20.10       | 1         | 0.81%   |
| Ubuntu MATE 20.04   | 1         | 0.81%   |
| Ubuntu Budgie 21.04 | 1         | 0.81%   |
| Ubuntu 21.04        | 1         | 0.81%   |
| ROSA R9             | 1         | 0.81%   |
| Pop!_OS 21.10       | 1         | 0.81%   |
| Pop!_OS 21.04       | 1         | 0.81%   |
| Pop!_OS 20.10       | 1         | 0.81%   |
| Pop!_OS 20.04       | 1         | 0.81%   |
| Pop!_OS 19.10       | 1         | 0.81%   |
| Peppermint 9        | 1         | 0.81%   |
| Parrot 4.11         | 1         | 0.81%   |
| openSUSE Leap-15.2  | 1         | 0.81%   |
| OpenMandriva 4.50   | 1         | 0.81%   |
| Manjaro 21.1.5      | 1         | 0.81%   |
| Manjaro 20.1.2      | 1         | 0.81%   |
| LinuxFX 11          | 1         | 0.81%   |
| Linux Mint 19.1     | 1         | 0.81%   |
| Fedora 33           | 1         | 0.81%   |
| Endless 3.9.1       | 1         | 0.81%   |
| Endless 3.7.8       | 1         | 0.81%   |
| EndeavourOS Rolling | 1         | 0.81%   |
| Devuan 4            | 1         | 0.81%   |
| Debian 9            | 1         | 0.81%   |
| Debian 10           | 1         | 0.81%   |
| CentOS 8            | 1         | 0.81%   |
| Arch                | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 46        | 39.66%  |
| Linux Mint    | 11        | 9.48%   |
| OpenMandriva  | 10        | 8.62%   |
| Pop!_OS       | 5         | 4.31%   |
| Manjaro       | 5         | 4.31%   |
| Zorin         | 4         | 3.45%   |
| ROSA          | 4         | 3.45%   |
| Xubuntu       | 3         | 2.59%   |
| BlackPanther  | 3         | 2.59%   |
| Lubuntu       | 2         | 1.72%   |
| LMDE          | 2         | 1.72%   |
| KDE neon      | 2         | 1.72%   |
| Garuda Linux  | 2         | 1.72%   |
| Endless       | 2         | 1.72%   |
| Debian        | 2         | 1.72%   |
| ArcoLinux     | 2         | 1.72%   |
| Ubuntu MATE   | 1         | 0.86%   |
| Ubuntu Budgie | 1         | 0.86%   |
| Peppermint    | 1         | 0.86%   |
| Parrot        | 1         | 0.86%   |
| openSUSE      | 1         | 0.86%   |
| LinuxFX       | 1         | 0.86%   |
| Fedora        | 1         | 0.86%   |
| EndeavourOS   | 1         | 0.86%   |
| Devuan        | 1         | 0.86%   |
| CentOS        | 1         | 0.86%   |
| Arch          | 1         | 0.86%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 6         | 4.08%   |
| 5.8.0-59-generic               | 4         | 2.72%   |
| 5.4.0-58-generic               | 4         | 2.72%   |
| 5.4.0-73-generic               | 3         | 2.04%   |
| 5.3.0-40-generic               | 3         | 2.04%   |
| 5.16.7-desktop-1omv4003        | 3         | 2.04%   |
| 5.11.0-38-generic              | 3         | 2.04%   |
| 4.15.0-43-generic              | 3         | 2.04%   |
| 5.8.18-1-MANJARO               | 2         | 1.36%   |
| 5.8.0-55-generic               | 2         | 1.36%   |
| 5.8.0-45-generic               | 2         | 1.36%   |
| 5.4.0-72-generic               | 2         | 1.36%   |
| 5.4.0-52-generic               | 2         | 1.36%   |
| 5.4.0-48-generic               | 2         | 1.36%   |
| 5.4.0-47-generic               | 2         | 1.36%   |
| 5.4.0-40-generic               | 2         | 1.36%   |
| 5.4.0-109-generic              | 2         | 1.36%   |
| 5.3.0-41-generic               | 2         | 1.36%   |
| 5.3.0-28-generic               | 2         | 1.36%   |
| 5.13.0-39-generic              | 2         | 1.36%   |
| 5.13.0-35-generic              | 2         | 1.36%   |
| 5.13.0-30-generic              | 2         | 1.36%   |
| 5.11.0-41-generic              | 2         | 1.36%   |
| 5.11.0-27-generic              | 2         | 1.36%   |
| 5.11.0-25-generic              | 2         | 1.36%   |
| 4.18.16-desktop-1bP            | 2         | 1.36%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2         | 1.36%   |
| 4.15.0-91-generic              | 2         | 1.36%   |
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
| 5.6.2-1-MANJARO                | 1         | 0.68%   |
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

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 24.19%  |
| 5.8.0   | 14        | 11.29%  |
| 4.15.0  | 12        | 9.68%   |
| 5.13.0  | 10        | 8.06%   |
| 5.11.0  | 10        | 8.06%   |
| 5.3.0   | 7         | 5.65%   |
| 5.10.14 | 6         | 4.84%   |
| 5.16.7  | 3         | 2.42%   |
| 4.19.0  | 3         | 2.42%   |
| 4.18.0  | 3         | 2.42%   |
| 5.9.16  | 2         | 1.61%   |
| 5.8.18  | 2         | 1.61%   |
| 5.10.0  | 2         | 1.61%   |
| 4.9.60  | 2         | 1.61%   |
| 4.18.16 | 2         | 1.61%   |
| 5.9.1   | 1         | 0.81%   |
| 5.8.5   | 1         | 0.81%   |
| 5.8.14  | 1         | 0.81%   |
| 5.6.2   | 1         | 0.81%   |
| 5.6.14  | 1         | 0.81%   |
| 5.3.6   | 1         | 0.81%   |
| 5.3.18  | 1         | 0.81%   |
| 5.17.1  | 1         | 0.81%   |
| 5.15.5  | 1         | 0.81%   |
| 5.14.8  | 1         | 0.81%   |
| 5.13.19 | 1         | 0.81%   |
| 5.12.4  | 1         | 0.81%   |
| 5.11.16 | 1         | 0.81%   |
| 5.11.13 | 1         | 0.81%   |
| 4.9.20  | 1         | 0.81%   |
| 4.9.0   | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 24.59%  |
| 5.8     | 18        | 14.75%  |
| 4.15    | 12        | 9.84%   |
| 5.13    | 11        | 9.02%   |
| 5.11    | 11        | 9.02%   |
| 5.3     | 9         | 7.38%   |
| 5.10    | 8         | 6.56%   |
| 4.9     | 4         | 3.28%   |
| 4.18    | 4         | 3.28%   |
| 5.9     | 3         | 2.46%   |
| 5.16    | 3         | 2.46%   |
| 4.19    | 3         | 2.46%   |
| 5.6     | 2         | 1.64%   |
| 5.17    | 1         | 0.82%   |
| 5.15    | 1         | 0.82%   |
| 5.14    | 1         | 0.82%   |
| 5.12    | 1         | 0.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 98        | 96.08%  |
| i686    | 2         | 1.96%   |
| aarch64 | 2         | 1.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 53        | 46.09%  |
| KDE5       | 20        | 17.39%  |
| X-Cinnamon | 9         | 7.83%   |
| Unknown    | 8         | 6.96%   |
| XFCE       | 7         | 6.09%   |
| MATE       | 4         | 3.48%   |
| LXQt       | 2         | 1.74%   |
| LXDE       | 2         | 1.74%   |
| KDE4       | 2         | 1.74%   |
| KDE        | 2         | 1.74%   |
| Budgie     | 2         | 1.74%   |
| Unity      | 1         | 0.87%   |
| i3         | 1         | 0.87%   |
| Deepin     | 1         | 0.87%   |
| Cinnamon   | 1         | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 95        | 92.23%  |
| Wayland | 6         | 5.83%   |
| Unknown | 2         | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 73        | 64.6%   |
| SDDM    | 14        | 12.39%  |
| GDM3    | 10        | 8.85%   |
| GDM     | 6         | 5.31%   |
| LightDM | 5         | 4.42%   |
| TDM     | 3         | 2.65%   |
| KDM     | 2         | 1.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 84        | 80.77%  |
| Unknown | 13        | 12.5%   |
| es_PR   | 4         | 3.85%   |
| es_ES   | 1         | 0.96%   |
| en_GB   | 1         | 0.96%   |
| C       | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 59        | 55.66%  |
| EFI  | 47        | 44.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 83        | 76.85%  |
| Overlay | 13        | 12.04%  |
| Btrfs   | 5         | 4.63%   |
| Unknown | 5         | 4.63%   |
| Zfs     | 1         | 0.93%   |
| Xfs     | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 79        | 72.48%  |
| GPT     | 22        | 20.18%  |
| MBR     | 8         | 7.34%   |

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
| No        | 80        | 73.39%  |
| Yes       | 29        | 26.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 20        | 19.61%  |
| Dell                    | 17        | 16.67%  |
| Gigabyte Technology     | 9         | 8.82%   |
| ASUSTek Computer        | 8         | 7.84%   |
| ASRock                  | 8         | 7.84%   |
| Lenovo                  | 7         | 6.86%   |
| MSI                     | 6         | 5.88%   |
| Acer                    | 5         | 4.9%    |
| Toshiba                 | 3         | 2.94%   |
| Sony                    | 3         | 2.94%   |
| Intel                   | 3         | 2.94%   |
| Apple                   | 2         | 1.96%   |
| TUXEDO                  | 1         | 0.98%   |
| Raspberry Pi Foundation | 1         | 0.98%   |
| Pegatron                | 1         | 0.98%   |
| GPU Company             | 1         | 0.98%   |
| CompuLab                | 1         | 0.98%   |
| BESSTAR Tech            | 1         | 0.98%   |
| AZW                     | 1         | 0.98%   |
| AMI                     | 1         | 0.98%   |
| Alienware               | 1         | 0.98%   |
| Acidanthera             | 1         | 0.98%   |
| Unknown                 | 1         | 0.98%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Dell Vostro 3550                        | 3         | 2.94%   |
| MSI Cubi N 8GL (MS-B171)                | 2         | 1.96%   |
| Intel SKYBAY                            | 2         | 1.96%   |
| HP Notebook                             | 2         | 1.96%   |
| ASRock Q1900M                           | 2         | 1.96%   |
| ASRock 945GCM-S                         | 2         | 1.96%   |
| TUXEDO Aura 15 Gen1                     | 1         | 0.98%   |
| Toshiba Satellite P755                  | 1         | 0.98%   |
| Toshiba Satellite L655                  | 1         | 0.98%   |
| Toshiba Satellite C55-C                 | 1         | 0.98%   |
| Sony VPCEB36GM                          | 1         | 0.98%   |
| Sony VPCEA36FX                          | 1         | 0.98%   |
| Sony VGN-CS320J                         | 1         | 0.98%   |
| RPi Raspberry Pi                        | 1         | 0.98%   |
| Pegatron QW716AA#ABA                    | 1         | 0.98%   |
| MSI MS-7B48                             | 1         | 0.98%   |
| MSI MS-7971                             | 1         | 0.98%   |
| MSI MS-7817                             | 1         | 0.98%   |
| MSI GF65 Thin 10SDR                     | 1         | 0.98%   |
| Lenovo Yoga 910-13IKB 80VF              | 1         | 0.98%   |
| Lenovo ThinkPad T410 2516ADU            | 1         | 0.98%   |
| Lenovo ThinkCentre M91p 7033CG1         | 1         | 0.98%   |
| Lenovo ThinkCentre M58p 6136A66         | 1         | 0.98%   |
| Lenovo IdeaPad 120S-11IAP 81A4          | 1         | 0.98%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS | 1         | 0.98%   |
| Lenovo G50-45 80E3                      | 1         | 0.98%   |
| Intel NUC8i7BEH                         | 1         | 0.98%   |
| HP Stream Laptop 14-CB1xxx              | 1         | 0.98%   |
| HP ProBook 6560b                        | 1         | 0.98%   |
| HP ProBook 6450b                        | 1         | 0.98%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 0.98%   |
| HP Laptop 15-dy1xxx                     | 1         | 0.98%   |
| HP Laptop 15-dw0xxx                     | 1         | 0.98%   |
| HP Laptop 14-dk1xxx                     | 1         | 0.98%   |
| HP ENVY TS m6 Sleekbook                 | 1         | 0.98%   |
| HP ENVY Laptop 17m-bw0xxx               | 1         | 0.98%   |
| HP ENVY dv7                             | 1         | 0.98%   |
| HP EliteDesk 800 G1 TWR                 | 1         | 0.98%   |
| HP EliteDesk 800 G1 SFF                 | 1         | 0.98%   |
| HP EliteBook 840 G2                     | 1         | 0.98%   |
| HP Compaq Pro 6300 SFF                  | 1         | 0.98%   |
| HP Compaq Pro 6300 MT                   | 1         | 0.98%   |
| HP Compaq nc6400 (RB516UT#ABA)          | 1         | 0.98%   |
| HP Compaq dc7800p Small Form Factor     | 1         | 0.98%   |
| HP Compaq 8200 Elite SFF PC             | 1         | 0.98%   |
| GPU Company GWTN156-9                   | 1         | 0.98%   |
| Gigabyte Z97M-DS3H                      | 1         | 0.98%   |
| Gigabyte X570 GAMING X                  | 1         | 0.98%   |
| Gigabyte X570 AORUS ELITE WIFI          | 1         | 0.98%   |
| Gigabyte X399 AORUS Gaming 7            | 1         | 0.98%   |
| Gigabyte J1900N-D3V                     | 1         | 0.98%   |
| Gigabyte F2A78M-HD2                     | 1         | 0.98%   |
| Gigabyte F2A68HM-H                      | 1         | 0.98%   |
| Gigabyte B450M DS3H                     | 1         | 0.98%   |
| Gigabyte B450 AORUS PRO WIFI            | 1         | 0.98%   |
| Dell Studio 540                         | 1         | 0.98%   |
| Dell OptiPlex 960                       | 1         | 0.98%   |
| Dell OptiPlex 9020                      | 1         | 0.98%   |
| Dell OptiPlex 780                       | 1         | 0.98%   |
| Dell OptiPlex 7020                      | 1         | 0.98%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 7         | 6.86%   |
| HP Compaq             | 5         | 4.9%    |
| Dell OptiPlex         | 4         | 3.92%   |
| Toshiba Satellite     | 3         | 2.94%   |
| HP Laptop             | 3         | 2.94%   |
| HP ENVY               | 3         | 2.94%   |
| Dell Vostro           | 3         | 2.94%   |
| Acer Aspire           | 3         | 2.94%   |
| MSI Cubi              | 2         | 1.96%   |
| Lenovo ThinkCentre    | 2         | 1.96%   |
| Intel SKYBAY          | 2         | 1.96%   |
| HP ProBook            | 2         | 1.96%   |
| HP Notebook           | 2         | 1.96%   |
| HP EliteDesk          | 2         | 1.96%   |
| Gigabyte X570         | 2         | 1.96%   |
| Dell Latitude         | 2         | 1.96%   |
| ASUS ROG              | 2         | 1.96%   |
| ASRock Q1900M         | 2         | 1.96%   |
| ASRock 945GCM-S       | 2         | 1.96%   |
| Acer Swift            | 2         | 1.96%   |
| TUXEDO Aura           | 1         | 0.98%   |
| Sony VPCEB36GM        | 1         | 0.98%   |
| Sony VPCEA36FX        | 1         | 0.98%   |
| Sony VGN-CS320J       | 1         | 0.98%   |
| RPi Raspberry         | 1         | 0.98%   |
| Pegatron QW716AA#ABA  | 1         | 0.98%   |
| MSI MS-7B48           | 1         | 0.98%   |
| MSI MS-7971           | 1         | 0.98%   |
| MSI MS-7817           | 1         | 0.98%   |
| MSI GF65              | 1         | 0.98%   |
| Lenovo Yoga           | 1         | 0.98%   |
| Lenovo ThinkPad       | 1         | 0.98%   |
| Lenovo IdeaPad        | 1         | 0.98%   |
| Lenovo IdeaCentre     | 1         | 0.98%   |
| Lenovo G50-45         | 1         | 0.98%   |
| Intel NUC8i7BEH       | 1         | 0.98%   |
| HP Stream             | 1         | 0.98%   |
| HP Pavilion           | 1         | 0.98%   |
| HP EliteBook          | 1         | 0.98%   |
| GPU Company GWTN156-9 | 1         | 0.98%   |
| Gigabyte Z97M-DS3H    | 1         | 0.98%   |
| Gigabyte X399         | 1         | 0.98%   |
| Gigabyte J1900N-D3V   | 1         | 0.98%   |
| Gigabyte F2A78M-HD2   | 1         | 0.98%   |
| Gigabyte F2A68HM-H    | 1         | 0.98%   |
| Gigabyte B450M        | 1         | 0.98%   |
| Gigabyte B450         | 1         | 0.98%   |
| Dell Studio           | 1         | 0.98%   |
| CompuLab fit-PC3      | 1         | 0.98%   |
| BESSTAR Tech Z83-W    | 1         | 0.98%   |
| AZW GT-R              | 1         | 0.98%   |
| ASUS X540SAA          | 1         | 0.98%   |
| ASUS TUF              | 1         | 0.98%   |
| ASUS PRIME            | 1         | 0.98%   |
| ASUS M5A78L-M         | 1         | 0.98%   |
| ASUS M2N-E            | 1         | 0.98%   |
| ASUS K53E             | 1         | 0.98%   |
| ASRock Z270           | 1         | 0.98%   |
| ASRock G31M-S         | 1         | 0.98%   |
| ASRock B450M-HDV      | 1         | 0.98%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 13        | 12.75%  |
| 2011    | 12        | 11.76%  |
| 2019    | 11        | 10.78%  |
| 2014    | 9         | 8.82%   |
| 2020    | 7         | 6.86%   |
| 2016    | 7         | 6.86%   |
| 2015    | 7         | 6.86%   |
| 2010    | 7         | 6.86%   |
| 2008    | 6         | 5.88%   |
| 2013    | 5         | 4.9%    |
| 2012    | 4         | 3.92%   |
| 2017    | 3         | 2.94%   |
| 2009    | 3         | 2.94%   |
| 2021    | 2         | 1.96%   |
| 2006    | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| 2007    | 1         | 0.98%   |
| 2005    | 1         | 0.98%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 49        | 48.04%  |
| Notebook       | 46        | 45.1%   |
| System on chip | 2         | 1.96%   |
| Mini pc        | 2         | 1.96%   |
| All in one     | 2         | 1.96%   |
| Convertible    | 1         | 0.98%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 97        | 94.17%  |
| Enabled  | 6         | 5.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 32        | 30.48%  |
| 3.01-4.0    | 24        | 22.86%  |
| 8.01-16.0   | 20        | 19.05%  |
| 16.01-24.0  | 12        | 11.43%  |
| 32.01-64.0  | 7         | 6.67%   |
| 1.01-2.0    | 6         | 5.71%   |
| 24.01-32.0  | 2         | 1.9%    |
| 64.01-256.0 | 2         | 1.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 60        | 48.78%  |
| 2.01-3.0  | 24        | 19.51%  |
| 3.01-4.0  | 17        | 13.82%  |
| 4.01-8.0  | 12        | 9.76%   |
| 0.51-1.0  | 9         | 7.32%   |
| 8.01-16.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 57.14%  |
| 2      | 26        | 23.21%  |
| 3      | 14        | 12.5%   |
| 4      | 5         | 4.46%   |
| 6      | 1         | 0.89%   |
| 5      | 1         | 0.89%   |
| 0      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 50.49%  |
| No        | 51        | 49.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 88.24%  |
| No        | 12        | 11.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 74.04%  |
| No        | 27        | 25.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 59.05%  |
| No        | 43        | 40.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Puerto Rico | 102       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San Juan      | 48        | 42.11%  |
| BayamÃ³n    | 5         | 4.39%   |
| Ponce         | 4         | 3.51%   |
| Caguas        | 4         | 3.51%   |
| BayamГіn    | 4         | 3.51%   |
| Juncos        | 3         | 2.63%   |
| Guayama       | 3         | 2.63%   |
| Cayey         | 3         | 2.63%   |
| Aguadilla     | 3         | 2.63%   |
| Vega Alta     | 2         | 1.75%   |
| Toa Baja      | 2         | 1.75%   |
| San Sebastian | 2         | 1.75%   |
| Las Piedras   | 2         | 1.75%   |
| Lares         | 2         | 1.75%   |
| Dorado        | 2         | 1.75%   |
| Cabo Rojo     | 2         | 1.75%   |
| Bayamón      | 2         | 1.75%   |
| Yabucoa       | 1         | 0.88%   |
| Vega Baja     | 1         | 0.88%   |
| Rio Grande    | 1         | 0.88%   |
| Penuelas      | 1         | 0.88%   |
| Naranjito     | 1         | 0.88%   |
| Morovis       | 1         | 0.88%   |
| MayagГјez   | 1         | 0.88%   |
| MayagÃ¼ez   | 1         | 0.88%   |
| Maunabo       | 1         | 0.88%   |
| Juana Diaz    | 1         | 0.88%   |
| Isabela       | 1         | 0.88%   |
| Humacao       | 1         | 0.88%   |
| Guaynabo      | 1         | 0.88%   |
| Ensenada      | 1         | 0.88%   |
| Coamo         | 1         | 0.88%   |
| Catano        | 1         | 0.88%   |
| Carolina      | 1         | 0.88%   |
| Canovanas     | 1         | 0.88%   |
| Arroyo        | 1         | 0.88%   |
| Arecibo       | 1         | 0.88%   |
| Angeles       | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 34        | 79     | 23.13%  |
| Seagate                   | 20        | 38     | 13.61%  |
| Toshiba                   | 15        | 18     | 10.2%   |
| Samsung Electronics       | 10        | 19     | 6.8%    |
| Crucial                   | 9         | 12     | 6.12%   |
| Unknown                   | 8         | 12     | 5.44%   |
| Hitachi                   | 7         | 21     | 4.76%   |
| China                     | 4         | 6      | 2.72%   |
| A-DATA Technology         | 4         | 9      | 2.72%   |
| Silicon Motion            | 3         | 3      | 2.04%   |
| SanDisk                   | 3         | 3      | 2.04%   |
| External                  | 3         | 4      | 2.04%   |
| Team                      | 2         | 2      | 1.36%   |
| TDAS                      | 2         | 10     | 1.36%   |
| PNY                       | 2         | 2      | 1.36%   |
| Phison                    | 2         | 2      | 1.36%   |
| Micron/Crucial Technology | 2         | 2      | 1.36%   |
| LITEONIT                  | 2         | 2      | 1.36%   |
| HGST                      | 2         | 4      | 1.36%   |
| WD MediaMax               | 1         | 3      | 0.68%   |
| W800SH                    | 1         | 1      | 0.68%   |
| USB3.0                    | 1         | 1      | 0.68%   |
| SPCC                      | 1         | 1      | 0.68%   |
| SK Hynix                  | 1         | 2      | 0.68%   |
| SABRENT                   | 1         | 1      | 0.68%   |
| Micron Technology         | 1         | 1      | 0.68%   |
| Kingston                  | 1         | 1      | 0.68%   |
| JMicron                   | 1         | 4      | 0.68%   |
| Intel                     | 1         | 1      | 0.68%   |
| AXIOM                     | 1         | 5      | 0.68%   |
| Argon                     | 1         | 1      | 0.68%   |
| addlink                   | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB         | 5         | 3.09%   |
| WDC WD5000LPVT-22G33T0 500GB         | 3         | 1.85%   |
| Unknown MMC Card  32GB               | 3         | 1.85%   |
| Toshiba DT01ACA100 1TB               | 3         | 1.85%   |
| External USB3.0 1TB                  | 3         | 1.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 1.23%   |
| WDC WDBNCE2500PNC 250GB SSD          | 2         | 1.23%   |
| WDC WD5000LPLX-22ZNTT0 500GB         | 2         | 1.23%   |
| WDC WD2500BEVS-60UST0 250GB          | 2         | 1.23%   |
| Unknown MMC Card  2GB                | 2         | 1.23%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.23%   |
| Toshiba MK3261GSYN 320GB             | 2         | 1.23%   |
| Toshiba DT01ACA050 500GB             | 2         | 1.23%   |
| TDAS TerraMaster 1TB                 | 2         | 1.23%   |
| Seagate ST320DM001 HD322GJ 320GB     | 2         | 1.23%   |
| Seagate ST2000VM003-1CT164 2TB       | 2         | 1.23%   |
| Seagate Expansion+ 2TB               | 2         | 1.23%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.23%   |
| Samsung NVMe SSD Drive 500GB         | 2         | 1.23%   |
| Micron/Crucial NVMe SSD Drive 500GB  | 2         | 1.23%   |
| Hitachi HTS547550A9E384 500GB        | 2         | 1.23%   |
| Crucial CT240M500SSD1 240GB          | 2         | 1.23%   |
| China SATA SSD 512GB                 | 2         | 1.23%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.62%   |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 0.62%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.62%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 0.62%   |
| WDC WD5000BPVT-75HXZT1 500GB         | 1         | 0.62%   |
| WDC WD5000BEVT-55A0RT0 500GB         | 1         | 0.62%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 0.62%   |
| WDC WD40EZRZ-22GXCB0 4TB             | 1         | 0.62%   |
| WDC WD30EZRZ-00WN9B0 3TB             | 1         | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.62%   |
| WDC WD1600AAJS-00PSA0 160GB          | 1         | 0.62%   |
| WDC WD1500HLFS-01G6U1 150GB          | 1         | 0.62%   |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 0.62%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.62%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.62%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.62%   |
| WDC WD10SPCX-75KHST0 1TB             | 1         | 0.62%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.62%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.62%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.62%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.62%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 0.62%   |
| WDC WD10EAVS-00D7B1 1TB              | 1         | 0.62%   |
| WDC WD1003FBYZ-010FB0 1TB            | 1         | 0.62%   |
| WDC WD1003FBYX-05Y7B0 1TB            | 1         | 0.62%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1         | 0.62%   |
| WD MediaMax WL500GSA3272 500GB       | 1         | 0.62%   |
| W800SH 512GB SSD                     | 1         | 0.62%   |
| USB3.0 Super Speed 320GB             | 1         | 0.62%   |
| Unknown MMC Card  64GB               | 1         | 0.62%   |
| Unknown MMC Card  10GB               | 1         | 0.62%   |
| Unknown HBG4a2  32GB                 | 1         | 0.62%   |
| Unknown DA4064  64GB                 | 1         | 0.62%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.62%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.62%   |
| Toshiba MK3276GSX 320GB              | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 69     | 38.36%  |
| Seagate             | 20        | 38     | 27.4%   |
| Toshiba             | 14        | 17     | 19.18%  |
| Hitachi             | 7         | 21     | 9.59%   |
| HGST                | 2         | 4      | 2.74%   |
| Samsung Electronics | 1         | 1      | 1.37%   |
| SABRENT             | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 12     | 21.43%  |
| Samsung Electronics | 7         | 11     | 16.67%  |
| WDC                 | 5         | 8      | 11.9%   |
| China               | 4         | 6      | 9.52%   |
| A-DATA Technology   | 4         | 9      | 9.52%   |
| External            | 3         | 4      | 7.14%   |
| PNY                 | 2         | 2      | 4.76%   |
| LITEONIT            | 2         | 2      | 4.76%   |
| W800SH              | 1         | 1      | 2.38%   |
| USB3.0              | 1         | 1      | 2.38%   |
| SPCC                | 1         | 1      | 2.38%   |
| SanDisk             | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| Argon               | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 65        | 151    | 47.79%  |
| SSD     | 40        | 60     | 29.41%  |
| NVMe    | 18        | 26     | 13.24%  |
| MMC     | 8         | 12     | 5.88%   |
| Unknown | 5         | 22     | 3.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 209    | 70.31%  |
| NVMe | 18        | 26     | 14.06%  |
| SAS  | 12        | 24     | 9.38%   |
| MMC  | 8         | 12     | 6.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 99     | 50.91%  |
| 0.51-1.0   | 37        | 77     | 33.64%  |
| 1.01-2.0   | 13        | 26     | 11.82%  |
| 3.01-4.0   | 3         | 8      | 2.73%   |
| 2.01-3.0   | 1         | 1      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 28        | 22.4%   |
| 101-250        | 24        | 19.2%   |
| 501-1000       | 24        | 19.2%   |
| 1001-2000      | 11        | 8.8%    |
| 1-20           | 11        | 8.8%    |
| More than 3000 | 9         | 7.2%    |
| 2001-3000      | 8         | 6.4%    |
| 51-100         | 4         | 3.2%    |
| 21-50          | 3         | 2.4%    |
| Unknown        | 3         | 2.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 35.2%   |
| 21-50     | 21        | 16.8%   |
| 101-250   | 16        | 12.8%   |
| 251-500   | 13        | 10.4%   |
| 51-100    | 11        | 8.8%    |
| 501-1000  | 9         | 7.2%    |
| 1001-2000 | 7         | 5.6%    |
| Unknown   | 3         | 2.4%    |
| 2001-3000 | 1         | 0.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 8.33%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 8.33%   |
| Seagate ST3250310AS 249GB                        | 1         | 1      | 8.33%   |
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
| Detected | 80        | 225    | 71.43%  |
| Works    | 22        | 34     | 19.64%  |
| Malfunc  | 10        | 12     | 8.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 69        | 60.53%  |
| AMD                          | 25        | 21.93%  |
| Silicon Motion               | 5         | 4.39%   |
| Samsung Electronics          | 3         | 2.63%   |
| Phison Electronics           | 3         | 2.63%   |
| Sandisk                      | 2         | 1.75%   |
| Micron/Crucial Technology    | 2         | 1.75%   |
| Toshiba America Info Systems | 1         | 0.88%   |
| SK Hynix                     | 1         | 0.88%   |
| Nvidia                       | 1         | 0.88%   |
| Kingston Technology Company  | 1         | 0.88%   |
| ASMedia Technology           | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20        | 14.49%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 5.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 4.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 3.62%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 3.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 2.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 2.9%    |
| Phison E12 NVMe Controller                                                              | 3         | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 2.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 2.17%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 2.17%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.45%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 1.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.45%   |
| AMD FCH IDE Controller                                                                  | 2         | 1.45%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.72%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.72%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1         | 0.72%   |
| Nvidia CK804 IDE                                                                        | 1         | 0.72%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1         | 0.72%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.72%   |
| Intel NVMe Optane Memory Series                                                         | 1         | 0.72%   |
| Intel Comet Lake PCH-H RAID                                                             | 1         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.72%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 1         | 0.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.72%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1         | 0.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.72%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.72%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 0.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.72%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 0.72%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.72%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 74        | 60.66%  |
| IDE  | 19        | 15.57%  |
| NVMe | 18        | 14.75%  |
| RAID | 11        | 9.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 71.57%  |
| AMD    | 27        | 26.47%  |
| ARM    | 2         | 1.96%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 2.94%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 2.94%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 2.94%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.96%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 2         | 1.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.96%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 2         | 1.96%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2         | 1.96%   |
| ARM Processor                               | 2         | 1.96%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.96%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.96%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 2         | 1.96%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.98%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.98%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.98%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.98%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 1         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.98%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.98%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.98%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.98%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 0.98%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.98%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.98%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 0.98%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.98%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.98%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.98%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.98%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 0.98%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.98%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 0.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 0.98%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 0.98%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1         | 0.98%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1         | 0.98%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 0.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 0.98%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1         | 0.98%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 0.98%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 1         | 0.98%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 0.98%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 0.98%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 0.98%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 0.98%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1         | 0.98%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 0.98%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 0.98%   |
| Intel Celeron J4115 CPU @ 1.80GHz           | 1         | 0.98%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 0.98%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 0.98%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 0.98%   |
| Intel Celeron CPU G1850 @ 2.90GHz           | 1         | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 19.61%  |
| Intel Celeron           | 14        | 13.73%  |
| Intel Core i7           | 11        | 10.78%  |
| Intel Core i3           | 10        | 9.8%    |
| Intel Core 2 Duo        | 6         | 5.88%   |
| AMD Ryzen 5             | 5         | 4.9%    |
| Other                   | 4         | 3.92%   |
| AMD Ryzen 7             | 4         | 3.92%   |
| AMD A8                  | 4         | 3.92%   |
| Intel Pentium Silver    | 3         | 2.94%   |
| AMD Ryzen 3             | 3         | 2.94%   |
| Intel Pentium Dual-Core | 2         | 1.96%   |
| Intel Pentium           | 2         | 1.96%   |
| AMD A6                  | 2         | 1.96%   |
| AMD A10                 | 2         | 1.96%   |
| Intel Genuine           | 1         | 0.98%   |
| Intel Core 2            | 1         | 0.98%   |
| Intel Atom              | 1         | 0.98%   |
| AMD Ryzen Threadripper  | 1         | 0.98%   |
| AMD Phenom              | 1         | 0.98%   |
| AMD G                   | 1         | 0.98%   |
| AMD FX                  | 1         | 0.98%   |
| AMD E2                  | 1         | 0.98%   |
| AMD Athlon 64 X2        | 1         | 0.98%   |
| AMD Athlon              | 1         | 0.98%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 55        | 53.92%  |
| 4      | 31        | 30.39%  |
| 6      | 7         | 6.86%   |
| 8      | 5         | 4.9%    |
| 1      | 3         | 2.94%   |
| 16     | 1         | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 102       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 52.94%  |
| 1      | 48        | 47.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 96.12%  |
| Unknown        | 3         | 2.91%   |
| 32-bit         | 1         | 0.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 19.81%  |
| 0x206a7    | 9         | 8.49%   |
| 0x306c3    | 6         | 5.66%   |
| 0x20655    | 5         | 4.72%   |
| 0x806e9    | 4         | 3.77%   |
| 0x706a1    | 4         | 3.77%   |
| 0x306a9    | 4         | 3.77%   |
| 0x1067a    | 4         | 3.77%   |
| 0x06001119 | 4         | 3.77%   |
| 0x806ea    | 3         | 2.83%   |
| 0x30678    | 3         | 2.83%   |
| 0x906ea    | 2         | 1.89%   |
| 0x6fd      | 2         | 1.89%   |
| 0x406e3    | 2         | 1.89%   |
| 0x406c4    | 2         | 1.89%   |
| 0x306d4    | 2         | 1.89%   |
| 0x08701013 | 2         | 1.89%   |
| 0x08108109 | 2         | 1.89%   |
| 0x06003106 | 2         | 1.89%   |
| 0xa0671    | 1         | 0.94%   |
| 0xa0652    | 1         | 0.94%   |
| 0x906ed    | 1         | 0.94%   |
| 0x906e9    | 1         | 0.94%   |
| 0x806c1    | 1         | 0.94%   |
| 0x706e5    | 1         | 0.94%   |
| 0x6fb      | 1         | 0.94%   |
| 0x6e8      | 1         | 0.94%   |
| 0x506e3    | 1         | 0.94%   |
| 0x506c9    | 1         | 0.94%   |
| 0x406c3    | 1         | 0.94%   |
| 0x40651    | 1         | 0.94%   |
| 0x30679    | 1         | 0.94%   |
| 0x20652    | 1         | 0.94%   |
| 0x10676    | 1         | 0.94%   |
| 0x08600106 | 1         | 0.94%   |
| 0x08101007 | 1         | 0.94%   |
| 0x0800820d | 1         | 0.94%   |
| 0x08001137 | 1         | 0.94%   |
| 0x07030105 | 1         | 0.94%   |
| 0x06000852 | 1         | 0.94%   |
| 0x05000119 | 1         | 0.94%   |
| 0x03000027 | 1         | 0.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 10.78%  |
| SandyBridge   | 10        | 9.8%    |
| Silvermont    | 7         | 6.86%   |
| Penryn        | 7         | 6.86%   |
| Haswell       | 7         | 6.86%   |
| Westmere      | 6         | 5.88%   |
| Zen+          | 5         | 4.9%    |
| Zen 2         | 5         | 4.9%    |
| Piledriver    | 5         | 4.9%    |
| Goldmont plus | 5         | 4.9%    |
| Skylake       | 4         | 3.92%   |
| IvyBridge     | 4         | 3.92%   |
| Core          | 4         | 3.92%   |
| Zen           | 3         | 2.94%   |
| Unknown       | 3         | 2.94%   |
| Steamroller   | 2         | 1.96%   |
| Puma          | 2         | 1.96%   |
| Broadwell     | 2         | 1.96%   |
| Zen 3         | 1         | 0.98%   |
| TigerLake     | 1         | 0.98%   |
| P6            | 1         | 0.98%   |
| K8 Hammer     | 1         | 0.98%   |
| K10 Llano     | 1         | 0.98%   |
| K10           | 1         | 0.98%   |
| IceLake       | 1         | 0.98%   |
| Goldmont      | 1         | 0.98%   |
| CometLake     | 1         | 0.98%   |
| Bobcat        | 1         | 0.98%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 68        | 61.26%  |
| AMD    | 25        | 22.52%  |
| Nvidia | 18        | 16.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 8.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 5.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 4.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.39%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 3.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.54%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.54%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 1.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.69%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 1.69%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 2         | 1.69%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.69%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 1.69%   |
| Intel HD Graphics 620                                                                    | 2         | 1.69%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 1.69%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 2         | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.69%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.85%   |
| Nvidia GK208 [GeForce GT 720]                                                            | 1         | 0.85%   |
| Nvidia GK110GL [Tesla K20Xm]                                                             | 1         | 0.85%   |
| Nvidia GK104GL [GRID K2]                                                                 | 1         | 0.85%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.85%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 1         | 0.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.85%   |
| Intel HD Graphics 630                                                                    | 1         | 0.85%   |
| Intel HD Graphics 500                                                                    | 1         | 0.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.85%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.85%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 0.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 0.85%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 0.85%   |
| AMD Trinity [Radeon HD 7660G]                                                            | 1         | 0.85%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1         | 0.85%   |
| AMD RS780 [Radeon HD 3200]                                                               | 1         | 0.85%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 0.85%   |
| AMD Renoir                                                                               | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 59        | 56.73%  |
| 1 x AMD            | 22        | 21.15%  |
| 1 x Nvidia         | 11        | 10.58%  |
| Intel + Nvidia     | 5         | 4.81%   |
| Intel + AMD        | 3         | 2.88%   |
| Other              | 2         | 1.92%   |
| Intel + 2 x Nvidia | 2         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 86        | 81.9%   |
| Proprietary | 12        | 11.43%  |
| Unknown     | 7         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 62.96%  |
| 0.51-1.0   | 11        | 10.19%  |
| 0.01-0.5   | 11        | 10.19%  |
| 1.01-2.0   | 7         | 6.48%   |
| 3.01-4.0   | 5         | 4.63%   |
| 5.01-6.0   | 3         | 2.78%   |
| 8.01-16.0  | 2         | 1.85%   |
| 2.01-3.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 10.09%  |
| LG Display              | 9         | 8.26%   |
| Goldstar                | 8         | 7.34%   |
| Chimei Innolux          | 8         | 7.34%   |
| Dell                    | 7         | 6.42%   |
| BOE                     | 6         | 5.5%    |
| AU Optronics            | 6         | 5.5%    |
| Acer                    | 6         | 5.5%    |
| Hewlett-Packard         | 5         | 4.59%   |
| AOC                     | 5         | 4.59%   |
| ViewSonic               | 4         | 3.67%   |
| Sony                    | 4         | 3.67%   |
| Sceptre Tech            | 3         | 2.75%   |
| Gateway                 | 3         | 2.75%   |
| Element                 | 3         | 2.75%   |
| Vizio                   | 2         | 1.83%   |
| VIZ                     | 2         | 1.83%   |
| Tech Concepts           | 2         | 1.83%   |
| MStar                   | 2         | 1.83%   |
| eMachines               | 2         | 1.83%   |
| Apple                   | 2         | 1.83%   |
| Unknown                 | 1         | 0.92%   |
| UGD                     | 1         | 0.92%   |
| Seiki                   | 1         | 0.92%   |
| PANDA                   | 1         | 0.92%   |
| ONN                     | 1         | 0.92%   |
| Lenovo                  | 1         | 0.92%   |
| InnoLux Display         | 1         | 0.92%   |
| Chi Mei Optoelectronics | 1         | 0.92%   |
| ASUSTek Computer        | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 4         | 3.51%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch             | 3         | 2.63%   |
| Element ELEFW504A ELE1366 1920x1080                                     | 3         | 2.63%   |
| VIZ LCD Monitor M551d-A2R                                               | 2         | 1.75%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch           | 2         | 1.75%   |
| Sony TV  *00 SNY4B04 3840x2160                                          | 2         | 1.75%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch       | 2         | 1.75%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 1.75%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                  | 2         | 1.75%   |
| Gateway LCD Monitor FHX2300                                             | 2         | 1.75%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                   | 2         | 1.75%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                   | 2         | 1.75%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch                 | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.75%   |
| Acer LCD Monitor G236HL 5760x1080                                       | 2         | 1.75%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                    | 1         | 0.88%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                     | 1         | 0.88%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch                | 1         | 0.88%   |
| ViewSonic VA1930wm VSC171F 1440x900 410x260mm 19.1-inch                 | 1         | 0.88%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                             | 1         | 0.88%   |
| UGD Artist 156 UGD1501 1920x1080 293x165mm 13.2-inch                    | 1         | 0.88%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                              | 1         | 0.88%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                              | 1         | 0.88%   |
| Sony TV SNYEA01 1920x1080 1600x900mm 72.3-inch                          | 1         | 0.88%   |
| Sony TV SNY4502 1920x1080                                               | 1         | 0.88%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                     | 1         | 0.88%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch        | 1         | 0.88%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch          | 1         | 0.88%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                  | 1         | 0.88%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch       | 1         | 0.88%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1872x1053mm 84.6-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.88%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 0.88%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch                 | 1         | 0.88%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                     | 1         | 0.88%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD051E 3840x2160 309x174mm 14.0-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch             | 1         | 0.88%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch             | 1         | 0.88%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                 | 1         | 0.88%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch        | 1         | 0.88%   |
| Hewlett-Packard P17A HWP3142 1280x1024 338x270mm 17.0-inch              | 1         | 0.88%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch            | 1         | 0.88%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch           | 1         | 0.88%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 553x311mm 25.0-inch              | 1         | 0.88%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch             | 1         | 0.88%   |
| Goldstar W2240 GSM57A1 1920x1080 477x268mm 21.5-inch                    | 1         | 0.88%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch             | 1         | 0.88%   |
| Gateway LCD Monitor FHX2300 3840x1080                                   | 1         | 0.88%   |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                      | 1         | 0.88%   |
| Dell S2330MX DELD049 1920x1080 509x286mm 23.0-inch                      | 1         | 0.88%   |
| Dell Inspiron 3043 DEL0690 1600x900 443x249mm 20.0-inch                 | 1         | 0.88%   |
| Dell E2316H DELF06B 1920x1080 510x290mm 23.1-inch                       | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 40%     |
| 1366x768 (WXGA)    | 25        | 25%     |
| 3840x2160 (4K)     | 10        | 10%     |
| 1440x900 (WXGA+)   | 5         | 5%      |
| 1600x900 (HD+)     | 4         | 4%      |
| 1280x800 (WXGA)    | 4         | 4%      |
| 5760x1080          | 2         | 2%      |
| 1280x1024 (SXGA)   | 2         | 2%      |
| Unknown            | 2         | 2%      |
| 3840x1080          | 1         | 1%      |
| 3440x1440          | 1         | 1%      |
| 2560x1440 (QHD)    | 1         | 1%      |
| 2560x1080          | 1         | 1%      |
| 1680x1050 (WSXGA+) | 1         | 1%      |
| 1280x720 (HD)      | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 22.64%  |
| 21      | 12        | 11.32%  |
| 23      | 10        | 9.43%   |
| 72      | 7         | 6.6%    |
| 14      | 7         | 6.6%    |
| 31      | 6         | 5.66%   |
| 17      | 6         | 5.66%   |
| 19      | 5         | 4.72%   |
| Unknown | 5         | 4.72%   |
| 20      | 4         | 3.77%   |
| 13      | 4         | 3.77%   |
| 27      | 3         | 2.83%   |
| 52      | 2         | 1.89%   |
| 34      | 2         | 1.89%   |
| 11      | 2         | 1.89%   |
| 84      | 1         | 0.94%   |
| 64      | 1         | 0.94%   |
| 32      | 1         | 0.94%   |
| 25      | 1         | 0.94%   |
| 24      | 1         | 0.94%   |
| 22      | 1         | 0.94%   |
| 18      | 1         | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 30.77%  |
| 401-500     | 22        | 21.15%  |
| 501-600     | 14        | 13.46%  |
| 1501-2000   | 8         | 7.69%   |
| 601-700     | 6         | 5.77%   |
| 351-400     | 6         | 5.77%   |
| 201-300     | 5         | 4.81%   |
| Unknown     | 5         | 4.81%   |
| 701-800     | 3         | 2.88%   |
| 1001-1500   | 3         | 2.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 73        | 77.66%  |
| 16/10   | 11        | 11.7%   |
| Unknown | 5         | 5.32%   |
| 5/4     | 3         | 3.19%   |
| 21/9    | 2         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 22.86%  |
| 201-250        | 20        | 19.05%  |
| 151-200        | 13        | 12.38%  |
| More than 1000 | 10        | 9.52%   |
| 81-90          | 10        | 9.52%   |
| 351-500        | 9         | 8.57%   |
| Unknown        | 5         | 4.76%   |
| 301-350        | 3         | 2.86%   |
| 141-150        | 3         | 2.86%   |
| 121-130        | 3         | 2.86%   |
| 51-60          | 2         | 1.9%    |
| 71-80          | 1         | 0.95%   |
| 251-300        | 1         | 0.95%   |
| 131-140        | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 39        | 38.61%  |
| 51-100        | 33        | 32.67%  |
| 121-160       | 12        | 11.88%  |
| 1-50          | 10        | 9.9%    |
| Unknown       | 5         | 4.95%   |
| More than 240 | 1         | 0.99%   |
| 161-240       | 1         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 78.3%   |
| 2     | 16        | 15.09%  |
| 0     | 5         | 4.72%   |
| 3     | 2         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 39.63%  |
| Intel                    | 52        | 31.71%  |
| Qualcomm Atheros         | 16        | 9.76%   |
| NetGear                  | 5         | 3.05%   |
| Broadcom                 | 5         | 3.05%   |
| Ralink Technology        | 4         | 2.44%   |
| Marvell Technology Group | 4         | 2.44%   |
| Broadcom Limited         | 3         | 1.83%   |
| TP-Link                  | 2         | 1.22%   |
| Samsung Electronics      | 2         | 1.22%   |
| Ralink                   | 2         | 1.22%   |
| Nvidia                   | 1         | 0.61%   |
| Gemtek                   | 1         | 0.61%   |
| Belkin Components        | 1         | 0.61%   |
| Aquantia                 | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 21.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 4.76%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 2.12%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 2.12%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 4         | 2.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 3         | 1.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 3         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 3         | 1.59%   |
| Intel Wireless 7265                                                            | 3         | 1.59%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 1.59%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 1.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 1.06%   |
| Realtek 802.11ac NIC                                                           | 2         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 1.06%   |
| NetGear AirCard 790S                                                           | 2         | 1.06%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.06%   |
| Intel Wireless 3160                                                            | 2         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.06%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 2         | 1.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.06%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                  | 2         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.06%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                        | 2         | 1.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.53%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                     | 1         | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1         | 0.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.53%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.53%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                         | 1         | 0.53%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.53%   |
| Ralink RT5370 Wireless Adapter                                                 | 1         | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.53%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                              | 1         | 0.53%   |
| Ralink MT7601U Wireless Adapter                                                | 1         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.53%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 1         | 0.53%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                     | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.53%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.53%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 0.53%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                               | 1         | 0.53%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                    | 1         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 37.5%   |
| Realtek Semiconductor | 23        | 26.14%  |
| Qualcomm Atheros      | 13        | 14.77%  |
| Ralink Technology     | 4         | 4.55%   |
| Broadcom              | 4         | 4.55%   |
| NetGear               | 3         | 3.41%   |
| TP-Link               | 2         | 2.27%   |
| Ralink                | 2         | 2.27%   |
| Broadcom Limited      | 2         | 2.27%   |
| Gemtek                | 1         | 1.14%   |
| Belkin Components     | 1         | 1.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                     | Computers | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                       | 6         | 6.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                | 5         | 5.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                  | 4         | 4.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                          | 4         | 4.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                        | 3         | 3.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                   | 3         | 3.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                | 3         | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                          | 3         | 3.23%   |
| Intel Wireless 7265                                                                       | 3         | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                           | 2         | 2.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                     | 2         | 2.15%   |
| Realtek 802.11ac NIC                                                                      | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                | 2         | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                | 2         | 2.15%   |
| Intel Wireless 3160                                                                       | 2         | 2.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                     | 2         | 2.15%   |
| Intel Comet Lake PCH CNVi WiFi                                                            | 2         | 2.15%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                             | 2         | 2.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                              | 2         | 2.15%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                             | 2         | 2.15%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                                   | 2         | 2.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                              | 1         | 1.08%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                | 1         | 1.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                   | 1         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                           | 1         | 1.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                           | 1         | 1.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                    | 1         | 1.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                               | 1         | 1.08%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                    | 1         | 1.08%   |
| Realtek RTL8187 Wireless Adapter                                                          | 1         | 1.08%   |
| Ralink RT5370 Wireless Adapter                                                            | 1         | 1.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                     | 1         | 1.08%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                         | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                           | 1         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                 | 1         | 1.08%   |
| Ralink RT2561/RT61 802.11g PCI                                                            | 1         | 1.08%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                | 1         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                          | 1         | 1.08%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                     | 1         | 1.08%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                                          | 1         | 1.08%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                               | 1         | 1.08%   |
| Intel Wireless 8265 / 8275                                                                | 1         | 1.08%   |
| Intel Wireless 7260                                                                       | 1         | 1.08%   |
| Intel Wireless 3165                                                                       | 1         | 1.08%   |
| Intel WiFi Link 5100                                                                      | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                                       | 1         | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                                           | 1         | 1.08%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                      | 1         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                  | 1         | 1.08%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                         | 1         | 1.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                                            | 1         | 1.08%   |
| Broadcom BCM4321 802.11a/b/g/n                                                            | 1         | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                                             | 1         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                       | 1         | 1.08%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU] | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 55.21%  |
| Intel                    | 27        | 28.13%  |
| Marvell Technology Group | 4         | 4.17%   |
| Qualcomm Atheros         | 3         | 3.13%   |
| Samsung Electronics      | 2         | 2.08%   |
| NetGear                  | 2         | 2.08%   |
| Broadcom                 | 2         | 2.08%   |
| Nvidia                   | 1         | 1.04%   |
| Broadcom Limited         | 1         | 1.04%   |
| Aquantia                 | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 42.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 9.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 6.25%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 4.17%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 4.17%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 3.13%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.08%   |
| NetGear AirCard 790S                                                           | 2         | 2.08%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.04%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.04%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.04%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 1.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.04%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 1.04%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.04%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.04%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.04%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 1.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.04%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.04%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.04%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 90        | 53.89%  |
| WiFi     | 77        | 46.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 52.31%  |
| WiFi     | 62        | 47.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 52        | 50%     |
| 1     | 47        | 45.19%  |
| 3     | 3         | 2.88%   |
| 0     | 2         | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 95.15%  |
| Yes  | 5         | 4.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 40.91%  |
| Cambridge Silicon Radio         | 9         | 13.64%  |
| Realtek Semiconductor           | 8         | 12.12%  |
| Qualcomm Atheros Communications | 5         | 7.58%   |
| Lite-On Technology              | 3         | 4.55%   |
| Toshiba                         | 2         | 3.03%   |
| Foxconn / Hon Hai               | 2         | 3.03%   |
| Broadcom                        | 2         | 3.03%   |
| Apple                           | 2         | 3.03%   |
| Ralink                          | 1         | 1.52%   |
| IMC Networks                    | 1         | 1.52%   |
| Hewlett-Packard                 | 1         | 1.52%   |
| Dynex                           | 1         | 1.52%   |
| Belkin Components               | 1         | 1.52%   |
| Alps Electric                   | 1         | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 13.64%  |
| Intel Bluetooth wireless interface                                                  | 8         | 12.12%  |
| Intel AX200 Bluetooth                                                               | 6         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 7.58%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 6.06%   |
| Intel Bluetooth Device                                                              | 4         | 6.06%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.55%   |
| Realtek Bluetooth Radio                                                             | 2         | 3.03%   |
| Lite-On Bluetooth Device                                                            | 2         | 3.03%   |
| Intel AX201 Bluetooth                                                               | 2         | 3.03%   |
| Broadcom Bluetooth Device                                                           | 2         | 3.03%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.52%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 1.52%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.52%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.52%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.52%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.52%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 1.52%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 1.52%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.52%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.52%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 71        | 57.72%  |
| AMD                                             | 26        | 21.14%  |
| Nvidia                                          | 15        | 12.2%   |
| Logitech                                        | 6         | 4.88%   |
| C-Media Electronics                             | 2         | 1.63%   |
| Nintendo                                        | 1         | 0.81%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.81%   |
| Kingston Technology                             | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.49%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 5.84%   |
| AMD FCH Azalia Controller                                                                         | 9         | 5.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.6%    |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 2.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.6%    |
| Logitech EasyCall Speakerphone                                                                    | 3         | 1.95%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.95%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.3%    |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 1.3%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.3%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.3%    |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.3%    |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.3%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.65%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nintendo WUP-021-0                                                                                | 1         | 0.65%   |
| Logitech QuickCam Fusion                                                                          | 1         | 0.65%   |
| Logitech Headset H390                                                                             | 1         | 0.65%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.65%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset                           | 1         | 0.65%   |
| Kingston Technology HyperX SoloCast                                                               | 1         | 0.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.65%   |
| Intel Audio device                                                                                | 1         | 0.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.65%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.65%   |
| C-Media Electronics CM6501                                                                        | 1         | 0.65%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.65%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 0.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 22.22%  |
| SK Hynix            | 8         | 22.22%  |
| Samsung Electronics | 8         | 22.22%  |
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
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 4.88%   |
| Unknown RAM WPBS26D408SWC-8G 8192MB SODIMM DDR4 2667MT/s  | 1         | 2.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1         | 2.44%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1         | 2.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s               | 1         | 2.44%   |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s  | 1         | 2.44%   |
| SK Hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 2.44%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1333MT/s   | 1         | 2.44%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 2.44%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1         | 2.44%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 2.44%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 2.44%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 2.44%   |
| Sesame RAM S939A2UGS-ITR 8192MB DIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 2.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM DDR3 1867MT/s    | 1         | 2.44%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1         | 2.44%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1         | 2.44%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 2.44%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 2.44%   |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s           | 1         | 2.44%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s | 1         | 2.44%   |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 2667MT/s        | 1         | 2.44%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 2.44%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s    | 1         | 2.44%   |
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
| DDR4    | 13        | 36.11%  |
| SDRAM   | 3         | 8.33%   |
| LPDDR4  | 2         | 5.56%   |
| DDR2    | 1         | 2.78%   |
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
| 8192  | 13        | 35.14%  |
| 2048  | 6         | 16.22%  |
| 16384 | 2         | 5.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 29.73%  |
| 2667    | 8         | 21.62%  |
| 1333    | 3         | 8.11%   |
| Unknown | 3         | 8.11%   |
| 3600    | 2         | 5.41%   |
| 3200    | 2         | 5.41%   |
| 667     | 2         | 5.41%   |
| 3466    | 1         | 2.7%    |
| 3266    | 1         | 2.7%    |
| 1867    | 1         | 2.7%    |
| 1866    | 1         | 2.7%    |
| 800     | 1         | 2.7%    |
| 200     | 1         | 2.7%    |

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
| Chicony Electronics                    | 9         | 17.65%  |
| Microdia                               | 7         | 13.73%  |
| Ricoh                                  | 5         | 9.8%    |
| Logitech                               | 5         | 9.8%    |
| Realtek Semiconductor                  | 4         | 7.84%   |
| Quanta                                 | 3         | 5.88%   |
| Acer                                   | 3         | 5.88%   |
| Suyin                                  | 2         | 3.92%   |
| Sunplus Innovation Technology          | 2         | 3.92%   |
| Lite-On Technology                     | 2         | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.92%   |
| Luxvisions Innotech Limited            | 1         | 1.96%   |
| Lenovo                                 | 1         | 1.96%   |
| Jieli Technology                       | 1         | 1.96%   |
| IMC Networks                           | 1         | 1.96%   |
| Goertek Electronics                    | 1         | 1.96%   |
| Cubeternet                             | 1         | 1.96%   |
| Apple                                  | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Camera                                                | 4         | 7.84%   |
| Ricoh Integrated Webcam                                        | 3         | 5.88%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 3.92%   |
| Microdia USB 2.0 Camera                                        | 2         | 3.92%   |
| Chicony HD WebCam                                              | 2         | 3.92%   |
| Suyin USB 2.0 Camera                                           | 1         | 1.96%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.96%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 1.96%   |
| Ricoh HD Webcam                                                | 1         | 1.96%   |
| Realtek USB2.0 camera                                          | 1         | 1.96%   |
| Realtek USB Camera                                             | 1         | 1.96%   |
| Realtek Integrated Webcam HD                                   | 1         | 1.96%   |
| Realtek HP Truevision HD                                       | 1         | 1.96%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.96%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.96%   |
| Quanta HD WebCam                                               | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.96%   |
| Logitech Webcam Pro 9000                                       | 1         | 1.96%   |
| Logitech Webcam C310                                           | 1         | 1.96%   |
| Logitech Webcam C270                                           | 1         | 1.96%   |
| Logitech HD Pro Webcam C920                                    | 1         | 1.96%   |
| Logitech CrystalCam                                            | 1         | 1.96%   |
| Lite-On HP Wide Vision HD Camera                               | 1         | 1.96%   |
| Lite-On HP HD Webcam                                           | 1         | 1.96%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.96%   |
| Jieli USB PHY 2.0                                              | 1         | 1.96%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 1.96%   |
| Goertek USB2.0 VGA UVC WebCam                                  | 1         | 1.96%   |
| Cubeternet GL-UPC822 UVC WebCam                                | 1         | 1.96%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 1.96%   |
| Chicony Toshiba Integrated Webcam                              | 1         | 1.96%   |
| Chicony Integrated HP HD Webcam                                | 1         | 1.96%   |
| Chicony HP Webcam                                              | 1         | 1.96%   |
| Chicony HP Truevision HD                                       | 1         | 1.96%   |
| Chicony EasyCamera                                             | 1         | 1.96%   |
| Chicony CNF9055 Toshiba Webcam                                 | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 1         | 1.96%   |
| Apple FaceTime HD Camera                                       | 1         | 1.96%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.96%   |
| Acer EasyCamera                                                | 1         | 1.96%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 77.78%  |
| LighTuning Technology | 2         | 22.22%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 3         | 33.33%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 2         | 22.22%  |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader  | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI             | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner        | 1         | 11.11%  |

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
| 0     | 78        | 70.91%  |
| 1     | 29        | 26.36%  |
| 2     | 3         | 2.73%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 13        | 40.63%  |
| Fingerprint reader       | 9         | 28.13%  |
| Graphics card            | 6         | 18.75%  |
| Communication controller | 2         | 6.25%   |
| Net/ethernet             | 1         | 3.13%   |
| Chipcard                 | 1         | 3.13%   |

