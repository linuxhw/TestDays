Lubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

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

Total: 99

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 3646h                       | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| HP            | 3646h                       | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 3397                        | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Unknown       | Unknown                     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| Foxconn       | G41MXE-V                    | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| ASUSTek       | A88XM-A                     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| ZOTAC         | NM10                        | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| Acer          | EQ45M                       | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| ASUSTek       | M4A87TD/USB3                | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| NEC Comput... | ECS-945G                    | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| MSI           | H310M PRO-VD                | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| MSI           | B550-A PRO                  | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| YANYU         | ITX-S192                    | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Pegatron      | Acacia                      | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Gigabyte      | MJPLNBB-00                  | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| BANGHO        | LITE E34                    | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| Gigabyte      | B360M DS3H                  | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Pegatron      | 2AD5                        | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| MSI           | MS-7267                     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| ECS           | G41T-M7                     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| ASUSTek       | M5A78L-M LX3                | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| Dell          | 0FPP7F A00                  | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| MSI           | B550-A PRO                  | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| MSI           | MS-7032                     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| NEC Comput... | ECS-945G                    | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| ASRock        | ION3D-HT                    | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| MSI           | A320M-A PRO                 | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| ASUSTek       | M5A97 PRO                   | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Positivo      | POS-AG31AP                  | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| HP            | 21B4 A01                    | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| ZOTAC         | NM10                        | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| Intel         | BTC-T37                     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| ASUSTek       | EB1501P                     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| ASRock        | H110M-HDV                   | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Gigabyte      | F2A58M-HD2                  | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| HP            | 0B4Ch D                     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Dell          | 0R849J A00                  | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Dell          | 09M8Y8 A01                  | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| MSI           | B450-A PRO MAX              | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| AMI           | Cherry Trail CR             | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Dell          | 0J584C A00                  | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| MSI           | Z590-A PRO                  | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| MSI           | Z170A GAMING M3             | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| ASRock        | G41M-VS3                    | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| HP            | 8768 A                      | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | 0WR7PY A03                  | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | M5A78L LE                   | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| HP            | 1495                        | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| MSI           | 760GM-P23                   | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| ASUSTek       | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | PRIME X370-A                | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Unknown       | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Unknown       | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Unknown       | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Dell          | 02YYK5 A01                  | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.15.0-43-generic           | 11       | 13.1%   |
| 5.15.0-60-generic           | 5        | 5.95%   |
| 5.15.0-41-generic           | 5        | 5.95%   |
| 5.15.0-56-generic           | 4        | 4.76%   |
| 5.15.0-47-generic           | 4        | 4.76%   |
| 5.15.0-25-generic           | 4        | 4.76%   |
| 5.19.0-32-generic           | 3        | 3.57%   |
| 5.15.0-67-generic           | 3        | 3.57%   |
| 5.15.0-52-generic           | 3        | 3.57%   |
| 5.15.0-48-generic           | 3        | 3.57%   |
| 5.15.0-40-generic           | 3        | 3.57%   |
| 5.15.0-39-generic           | 3        | 3.57%   |
| 5.19.0-35-generic           | 2        | 2.38%   |
| 5.15.0-58-generic           | 2        | 2.38%   |
| 5.15.0-53-generic           | 2        | 2.38%   |
| 5.15.0-50-generic           | 2        | 2.38%   |
| 5.15.0-46-generic           | 2        | 2.38%   |
| 5.15.0-30-generic           | 2        | 2.38%   |
| 5.15.0-27-generic           | 2        | 2.38%   |
| 6.3.3-custom                | 1        | 1.19%   |
| 6.2.8-x64v3-xanmod1         | 1        | 1.19%   |
| 6.1.0-custom                | 1        | 1.19%   |
| 6.0.8-060008-generic        | 1        | 1.19%   |
| 6.0.14                      | 1        | 1.19%   |
| 5.19.0-43-generic           | 1        | 1.19%   |
| 5.19.0-41-generic           | 1        | 1.19%   |
| 5.19.0-16.2-liquorix-amd64  | 1        | 1.19%   |
| 5.15.0-72-generic           | 1        | 1.19%   |
| 5.15.0-71-generic           | 1        | 1.19%   |
| 5.15.0-69-lowlatency        | 1        | 1.19%   |
| 5.15.0-59-lowlatency        | 1        | 1.19%   |
| 5.15.0-58-lowlatency        | 1        | 1.19%   |
| 5.15.0-57-generic           | 1        | 1.19%   |
| 5.15.0-41-lowlatency        | 1        | 1.19%   |
| 5.15.0-362206031516-generic | 1        | 1.19%   |
| 5.15.0-35-generic           | 1        | 1.19%   |
| 5.15.0-23-generic           | 1        | 1.19%   |
| 5.15.0-18-generic           | 1        | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 66       | 83.54%  |
| 5.19.0  | 8        | 10.13%  |
| 6.3.3   | 1        | 1.27%   |
| 6.2.8   | 1        | 1.27%   |
| 6.1.0   | 1        | 1.27%   |
| 6.0.8   | 1        | 1.27%   |
| 6.0.14  | 1        | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 66       | 83.54%  |
| 5.19    | 8        | 10.13%  |
| 6.0     | 2        | 2.53%   |
| 6.3     | 1        | 1.27%   |
| 6.2     | 1        | 1.27%   |
| 6.1     | 1        | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 76       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LXQt | 73       | 96.05%  |
| LXDE | 2        | 2.63%   |
| XFCE | 1        | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 72       | 92.31%  |
| Tty         | 4        | 5.13%   |
| Wayland     | 1        | 1.28%   |
| Unspecified | 1        | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 65       | 85.53%  |
| LightDM | 4        | 5.26%   |
| Unknown | 3        | 3.95%   |
| XDM     | 1        | 1.32%   |
| SLiM    | 1        | 1.32%   |
| LXDM    | 1        | 1.32%   |
| GDM3    | 1        | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 20       | 26.32%  |
| fr_FR | 11       | 14.47%  |
| de_DE | 8        | 10.53%  |
| it_IT | 6        | 7.89%   |
| es_ES | 5        | 6.58%   |
| en_GB | 4        | 5.26%   |
| es_AR | 3        | 3.95%   |
| C     | 3        | 3.95%   |
| pt_BR | 2        | 2.63%   |
| es_MX | 2        | 2.63%   |
| es_CR | 2        | 2.63%   |
| tr_TR | 1        | 1.32%   |
| sv_SE | 1        | 1.32%   |
| ru_UA | 1        | 1.32%   |
| pl_PL | 1        | 1.32%   |
| nl_BE | 1        | 1.32%   |
| es_PE | 1        | 1.32%   |
| en_AU | 1        | 1.32%   |
| en_AG | 1        | 1.32%   |
| el_GR | 1        | 1.32%   |
| cv_RU | 1        | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 56       | 73.68%  |
| EFI  | 20       | 26.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 70       | 90.91%  |
| Overlay | 3        | 3.9%    |
| Tmpfs   | 2        | 2.6%    |
| XXX4    | 1        | 1.3%    |
| Btrfs   | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 32       | 42.11%  |
| MBR     | 26       | 34.21%  |
| Unknown | 18       | 23.68%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 80.26%  |
| Yes       | 15       | 19.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 57.89%  |
| Yes       | 32       | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 13       | 17.11%  |
| ASUSTek Computer    | 13       | 17.11%  |
| Dell                | 9        | 11.84%  |
| ASRock              | 6        | 7.89%   |
| Hewlett-Packard     | 5        | 6.58%   |
| Gigabyte Technology | 5        | 6.58%   |
| Unknown             | 4        | 5.26%   |
| Pegatron            | 3        | 3.95%   |
| Acer                | 3        | 3.95%   |
| Positivo            | 2        | 2.63%   |
| Lenovo              | 2        | 2.63%   |
| Intel               | 2        | 2.63%   |
| AMI                 | 2        | 2.63%   |
| ZOTAC               | 1        | 1.32%   |
| YANYU               | 1        | 1.32%   |
| NEC Computers       | 1        | 1.32%   |
| Fujitsu             | 1        | 1.32%   |
| Foxconn             | 1        | 1.32%   |
| ECS                 | 1        | 1.32%   |
| BANGHO              | 1        | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 4        | 5.26%   |
| MSI MS-7C37                            | 2        | 2.63%   |
| Dell Dimension 9100                    | 2        | 2.63%   |
| ZOTAC NM10                             | 1        | 1.32%   |
| YANYU ITX-S192                         | 1        | 1.32%   |
| Positivo POS-AG31AP                    | 1        | 1.32%   |
| Positivo P5VD2-MX                      | 1        | 1.32%   |
| Pegatron NC689AA-ABA s3700y            | 1        | 1.32%   |
| Pegatron h8-1350ef                     | 1        | 1.32%   |
| Pegatron AY748AA-ABA p6320y            | 1        | 1.32%   |
| NEC Computers ECS-945G                 | 1        | 1.32%   |
| MSI MS-7D09                            | 1        | 1.32%   |
| MSI MS-7C96                            | 1        | 1.32%   |
| MSI MS-7C56                            | 1        | 1.32%   |
| MSI MS-7C51                            | 1        | 1.32%   |
| MSI MS-7B86                            | 1        | 1.32%   |
| MSI MS-7B33                            | 1        | 1.32%   |
| MSI MS-7978                            | 1        | 1.32%   |
| MSI MS-7641                            | 1        | 1.32%   |
| MSI MS-7501                            | 1        | 1.32%   |
| MSI MS-7267                            | 1        | 1.32%   |
| MSI MS-7032                            | 1        | 1.32%   |
| Lenovo ThinkCentre M83 10ANCTO1WW      | 1        | 1.32%   |
| Lenovo ThinkCentre M600 10KGS09S00     | 1        | 1.32%   |
| Intel X79 V2.72A                       | 1        | 1.32%   |
| Intel BTC-T37                          | 1        | 1.32%   |
| HP Z400 Workstation                    | 1        | 1.32%   |
| HP t620 Quad Core TC                   | 1        | 1.32%   |
| HP Slim Desktop S01-pF1xxx             | 1        | 1.32%   |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1        | 1.32%   |
| HP Compaq 8000 Elite SFF PC            | 1        | 1.32%   |
| Gigabyte GB-BMCE-5105                  | 1        | 1.32%   |
| Gigabyte G31M-S2C                      | 1        | 1.32%   |
| Gigabyte G31M-ES2C                     | 1        | 1.32%   |
| Gigabyte F2A58M-HD2                    | 1        | 1.32%   |
| Gigabyte B360M-DS3H                    | 1        | 1.32%   |
| Fujitsu FUTRO S900                     | 1        | 1.32%   |
| Foxconn G41MXE-V                       | 1        | 1.32%   |
| ECS G41T-M7                            | 1        | 1.32%   |
| Dell Vostro 410                        | 1        | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 4        | 5.26%   |
| Dell OptiPlex          | 3        | 3.95%   |
| MSI MS-7C37            | 2        | 2.63%   |
| Lenovo ThinkCentre     | 2        | 2.63%   |
| HP Compaq              | 2        | 2.63%   |
| Dell Vostro            | 2        | 2.63%   |
| Dell Dimension         | 2        | 2.63%   |
| ASUS PRIME             | 2        | 2.63%   |
| ZOTAC NM10             | 1        | 1.32%   |
| YANYU ITX-S192         | 1        | 1.32%   |
| Positivo POS-AG31AP    | 1        | 1.32%   |
| Positivo P5VD2-MX      | 1        | 1.32%   |
| Pegatron NC689AA-ABA   | 1        | 1.32%   |
| Pegatron h8-1350ef     | 1        | 1.32%   |
| Pegatron AY748AA-ABA   | 1        | 1.32%   |
| NEC Computers ECS-945G | 1        | 1.32%   |
| MSI MS-7D09            | 1        | 1.32%   |
| MSI MS-7C96            | 1        | 1.32%   |
| MSI MS-7C56            | 1        | 1.32%   |
| MSI MS-7C51            | 1        | 1.32%   |
| MSI MS-7B86            | 1        | 1.32%   |
| MSI MS-7B33            | 1        | 1.32%   |
| MSI MS-7978            | 1        | 1.32%   |
| MSI MS-7641            | 1        | 1.32%   |
| MSI MS-7501            | 1        | 1.32%   |
| MSI MS-7267            | 1        | 1.32%   |
| MSI MS-7032            | 1        | 1.32%   |
| Intel X79              | 1        | 1.32%   |
| Intel BTC-T37          | 1        | 1.32%   |
| HP Z400                | 1        | 1.32%   |
| HP t620                | 1        | 1.32%   |
| HP Slim                | 1        | 1.32%   |
| Gigabyte GB-BMCE-5105  | 1        | 1.32%   |
| Gigabyte G31M-S2C      | 1        | 1.32%   |
| Gigabyte G31M-ES2C     | 1        | 1.32%   |
| Gigabyte F2A58M-HD2    | 1        | 1.32%   |
| Gigabyte B360M-DS3H    | 1        | 1.32%   |
| Fujitsu FUTRO          | 1        | 1.32%   |
| Foxconn G41MXE-V       | 1        | 1.32%   |
| ECS G41T-M7            | 1        | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 8        | 10.53%  |
| 2008 | 8        | 10.53%  |
| 2019 | 6        | 7.89%   |
| 2020 | 5        | 6.58%   |
| 2018 | 5        | 6.58%   |
| 2017 | 5        | 6.58%   |
| 2011 | 5        | 6.58%   |
| 2009 | 5        | 6.58%   |
| 2007 | 5        | 6.58%   |
| 2021 | 4        | 5.26%   |
| 2015 | 4        | 5.26%   |
| 2014 | 4        | 5.26%   |
| 2013 | 4        | 5.26%   |
| 2016 | 2        | 2.63%   |
| 2012 | 2        | 2.63%   |
| 2006 | 2        | 2.63%   |
| 2022 | 1        | 1.32%   |
| 2001 | 1        | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 76       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 75       | 98.68%  |
| Enabled  | 1        | 1.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 15       | 19.48%  |
| 3.01-4.0    | 14       | 18.18%  |
| 16.01-24.0  | 13       | 16.88%  |
| 8.01-16.0   | 11       | 14.29%  |
| 32.01-64.0  | 8        | 10.39%  |
| 1.01-2.0    | 8        | 10.39%  |
| 2.01-3.0    | 3        | 3.9%    |
| 0.51-1.0    | 3        | 3.9%    |
| 64.01-256.0 | 2        | 2.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 35       | 43.75%  |
| 0.51-1.0  | 18       | 22.5%   |
| 2.01-3.0  | 15       | 18.75%  |
| 4.01-8.0  | 7        | 8.75%   |
| 3.01-4.0  | 3        | 3.75%   |
| 8.01-16.0 | 1        | 1.25%   |
| 0.01-0.5  | 1        | 1.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 50%     |
| 2      | 25       | 32.89%  |
| 3      | 5        | 6.58%   |
| 5      | 2        | 2.63%   |
| 4      | 2        | 2.63%   |
| 12     | 1        | 1.32%   |
| 7      | 1        | 1.32%   |
| 6      | 1        | 1.32%   |
| 0      | 1        | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 58.44%  |
| Yes       | 32       | 41.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 75       | 98.68%  |
| No        | 1        | 1.32%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 57.89%  |
| Yes       | 32       | 42.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 80.77%  |
| Yes       | 15       | 19.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 15       | 19.74%  |
| France     | 11       | 14.47%  |
| Germany    | 9        | 11.84%  |
| Italy      | 6        | 7.89%   |
| Spain      | 5        | 6.58%   |
| Poland     | 4        | 5.26%   |
| UK         | 3        | 3.95%   |
| Brazil     | 3        | 3.95%   |
| Argentina  | 3        | 3.95%   |
| Sweden     | 2        | 2.63%   |
| Costa Rica | 2        | 2.63%   |
| Venezuela  | 1        | 1.32%   |
| Ukraine    | 1        | 1.32%   |
| Turkey     | 1        | 1.32%   |
| Romania    | 1        | 1.32%   |
| Peru       | 1        | 1.32%   |
| Mexico     | 1        | 1.32%   |
| Latvia     | 1        | 1.32%   |
| Ireland    | 1        | 1.32%   |
| Iran       | 1        | 1.32%   |
| Greece     | 1        | 1.32%   |
| Bulgaria   | 1        | 1.32%   |
| Belgium    | 1        | 1.32%   |
| Australia  | 1        | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 3        | 3.75%   |
| Largo                | 2        | 2.5%    |
| Heredia              | 2        | 2.5%    |
| Wetteren             | 1        | 1.25%   |
| Washington           | 1        | 1.25%   |
| Warsaw               | 1        | 1.25%   |
| Versailles           | 1        | 1.25%   |
| Varna                | 1        | 1.25%   |
| Valentigney          | 1        | 1.25%   |
| Turin                | 1        | 1.25%   |
| Torrejón de Ardoz   | 1        | 1.25%   |
| Tehran               | 1        | 1.25%   |
| Tandil               | 1        | 1.25%   |
| St Louis             | 1        | 1.25%   |
| Sonico               | 1        | 1.25%   |
| Sao Paulo            | 1        | 1.25%   |
| Saltsjoe-Boo         | 1        | 1.25%   |
| Riverenert           | 1        | 1.25%   |
| Rio Segundo          | 1        | 1.25%   |
| Richmond             | 1        | 1.25%   |
| Resistencia          | 1        | 1.25%   |
| Port Washington      | 1        | 1.25%   |
| Palencia             | 1        | 1.25%   |
| Ostrów Wielkopolski | 1        | 1.25%   |
| Oberkotzau           | 1        | 1.25%   |
| Novo Gama            | 1        | 1.25%   |
| Notting Hill Gate    | 1        | 1.25%   |
| Nederland            | 1        | 1.25%   |
| Mostoles             | 1        | 1.25%   |
| Monheim am Rhein     | 1        | 1.25%   |
| Mobile               | 1        | 1.25%   |
| Mexico City          | 1        | 1.25%   |
| Melbourne            | 1        | 1.25%   |
| Marseille            | 1        | 1.25%   |
| Madrid               | 1        | 1.25%   |
| Lima                 | 1        | 1.25%   |
| Lebanon              | 1        | 1.25%   |
| Larissa              | 1        | 1.25%   |
| Kyiv                 | 1        | 1.25%   |
| Koblenz              | 1        | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 24       | 33     | 19.83%  |
| WDC                       | 18       | 29     | 14.88%  |
| Samsung Electronics       | 17       | 24     | 14.05%  |
| Hitachi                   | 11       | 14     | 9.09%   |
| Kingston                  | 9        | 10     | 7.44%   |
| SanDisk                   | 5        | 5      | 4.13%   |
| Crucial                   | 4        | 4      | 3.31%   |
| Toshiba                   | 3        | 3      | 2.48%   |
| Maxtor                    | 2        | 2      | 1.65%   |
| HGST                      | 2        | 2      | 1.65%   |
| GOODRAM                   | 2        | 2      | 1.65%   |
| A-DATA Technology         | 2        | 2      | 1.65%   |
| WD MediaMax               | 1        | 1      | 0.83%   |
| Unknown                   | 1        | 1      | 0.83%   |
| Transcend                 | 1        | 2      | 0.83%   |
| TO Exter                  | 1        | 1      | 0.83%   |
| Team                      | 1        | 1      | 0.83%   |
| T-FORCE                   | 1        | 1      | 0.83%   |
| RSH-319                   | 1        | 1      | 0.83%   |
| PNY                       | 1        | 1      | 0.83%   |
| Patriot                   | 1        | 1      | 0.83%   |
| Micron/Crucial Technology | 1        | 2      | 0.83%   |
| LITEONIT                  | 1        | 1      | 0.83%   |
| Kston                     | 1        | 3      | 0.83%   |
| Intel                     | 1        | 1      | 0.83%   |
| HGST HUS                  | 1        | 2      | 0.83%   |
| Gigabyte Technology       | 1        | 1      | 0.83%   |
| External                  | 1        | 1      | 0.83%   |
| Emtec                     | 1        | 1      | 0.83%   |
| China                     | 1        | 1      | 0.83%   |
| BR                        | 1        | 1      | 0.83%   |
| Apricorn                  | 1        | 1      | 0.83%   |
| Apacer                    | 1        | 1      | 0.83%   |
| AMD                       | 1        | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 6        | 4.29%   |
| Kingston SA400S37240G 240GB SSD      | 4        | 2.86%   |
| Toshiba DT01ACA100 1TB               | 2        | 1.43%   |
| Seagate ST3120213AS 120GB            | 2        | 1.43%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 1.43%   |
| SanDisk DF4032  32GB                 | 2        | 1.43%   |
| Samsung SSD 870 EVO 500GB            | 2        | 1.43%   |
| Samsung HD502HJ 500GB                | 2        | 1.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.71%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1        | 0.71%   |
| WDC WD800BB-00CAA1 80GB              | 1        | 0.71%   |
| WDC WD60EFRX-68L0BN1 6TB             | 1        | 0.71%   |
| WDC WD5000LUCT-63RC2Y0 500GB         | 1        | 0.71%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1        | 0.71%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 0.71%   |
| WDC WD3200BPVT-80JJ5T0 320GB         | 1        | 0.71%   |
| WDC WD3200BPVT-00HXZT3 320GB         | 1        | 0.71%   |
| WDC WD3200AAJS-65M0A0 320GB          | 1        | 0.71%   |
| WDC WD3200AAJS-56M0A0 320GB          | 1        | 0.71%   |
| WDC WD3200AAJS-56B4A0 320GB          | 1        | 0.71%   |
| WDC WD3200AACS-00M6B0 320GB          | 1        | 0.71%   |
| WDC WD30EZRZ-00GXCB0 3TB             | 1        | 0.71%   |
| WDC WD2500KS-00MJB0 250GB            | 1        | 0.71%   |
| WDC WD2500AAJS-07M0A0 250GB          | 1        | 0.71%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1        | 0.71%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1        | 0.71%   |
| WDC WD2003FYYS-02W0B0 2TB            | 1        | 0.71%   |
| WDC WD10SPZX-08Z10 1TB               | 1        | 0.71%   |
| WDC WD10S21X-24R1BT0-SSHD-8GB        | 1        | 0.71%   |
| WDC WD10EZRZ-00Z5HB0 1TB             | 1        | 0.71%   |
| WDC WD10EZEX-60WN4A1 1TB             | 1        | 0.71%   |
| WDC WD10EURX-63C57Y0 1TB             | 1        | 0.71%   |
| WDC WD10EACS-00D6B1 1TB              | 1        | 0.71%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1        | 0.71%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB | 1        | 0.71%   |
| WD MediaMax WL250GSA872 250GB        | 1        | 0.71%   |
| Unknown 032G72  32GB                 | 1        | 0.71%   |
| Transcend TS128GSSD340 128GB         | 1        | 0.71%   |
| Toshiba MK6465GSX 640GB              | 1        | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 32     | 35.29%  |
| WDC                 | 16       | 24     | 23.53%  |
| Hitachi             | 11       | 14     | 16.18%  |
| Samsung Electronics | 6        | 7      | 8.82%   |
| Toshiba             | 3        | 3      | 4.41%   |
| Maxtor              | 2        | 2      | 2.94%   |
| HGST                | 2        | 2      | 2.94%   |
| WD MediaMax         | 1        | 1      | 1.47%   |
| RSH-319             | 1        | 1      | 1.47%   |
| External            | 1        | 1      | 1.47%   |
| Apricorn            | 1        | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 13     | 21.95%  |
| Kingston            | 8        | 9      | 19.51%  |
| SanDisk             | 3        | 3      | 7.32%   |
| WDC                 | 2        | 2      | 4.88%   |
| GOODRAM             | 2        | 2      | 4.88%   |
| Crucial             | 2        | 2      | 4.88%   |
| A-DATA Technology   | 2        | 2      | 4.88%   |
| Transcend           | 1        | 2      | 2.44%   |
| TO Exter            | 1        | 1      | 2.44%   |
| Team                | 1        | 1      | 2.44%   |
| PNY                 | 1        | 1      | 2.44%   |
| Patriot             | 1        | 1      | 2.44%   |
| LITEONIT            | 1        | 1      | 2.44%   |
| Kston               | 1        | 3      | 2.44%   |
| Intel               | 1        | 1      | 2.44%   |
| Gigabyte Technology | 1        | 1      | 2.44%   |
| Emtec               | 1        | 1      | 2.44%   |
| China               | 1        | 1      | 2.44%   |
| BR                  | 1        | 1      | 2.44%   |
| Apacer              | 1        | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 50       | 88     | 48.54%  |
| SSD     | 38       | 49     | 36.89%  |
| NVMe    | 11       | 14     | 10.68%  |
| MMC     | 3        | 3      | 2.91%   |
| Unknown | 1        | 3      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 70       | 133    | 79.55%  |
| NVMe | 11       | 14     | 12.5%   |
| SAS  | 4        | 7      | 4.55%   |
| MMC  | 3        | 3      | 3.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 60       | 87     | 63.83%  |
| 0.51-1.0   | 16       | 23     | 17.02%  |
| 1.01-2.0   | 11       | 16     | 11.7%   |
| 2.01-3.0   | 3        | 4      | 3.19%   |
| 4.01-10.0  | 3        | 6      | 3.19%   |
| 3.01-4.0   | 1        | 1      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 21       | 27.27%  |
| 251-500        | 13       | 16.88%  |
| 21-50          | 9        | 11.69%  |
| 1001-2000      | 8        | 10.39%  |
| 501-1000       | 6        | 7.79%   |
| 51-100         | 6        | 7.79%   |
| More than 3000 | 5        | 6.49%   |
| 1-20           | 5        | 6.49%   |
| 2001-3000      | 4        | 5.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 40%     |
| 21-50          | 14       | 17.5%   |
| 101-250        | 9        | 11.25%  |
| 51-100         | 8        | 10%     |
| 501-1000       | 6        | 7.5%    |
| 1001-2000      | 4        | 5%      |
| More than 3000 | 3        | 3.75%   |
| 251-500        | 3        | 3.75%   |
| 2001-3000      | 1        | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 2      | 6.25%   |
| WDC WD3200AACS-00M6B0 320GB         | 1        | 1      | 6.25%   |
| WDC WD2003FYYS-02W0B0 2TB           | 1        | 1      | 6.25%   |
| WDC WD10SPZX-08Z10 1TB              | 1        | 1      | 6.25%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 1      | 6.25%   |
| WDC WD10EACS-00D6B1 1TB             | 1        | 1      | 6.25%   |
| Toshiba MK6465GSX 640GB             | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 6.25%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 2      | 6.25%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 6.25%   |
| Maxtor 6L200M0 208GB                | 1        | 1      | 6.25%   |
| Hitachi HTS543216L9A300 160GB       | 1        | 1      | 6.25%   |
| Hitachi HTE545050B9A300 500GB       | 1        | 1      | 6.25%   |
| Apacer 16GB SATA Flash Drive SSD    | 1        | 1      | 6.25%   |
| A-DATA Technology SP920SS 256GB SSD | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 28.57%  |
| Seagate             | 3        | 4      | 21.43%  |
| Hitachi             | 2        | 2      | 14.29%  |
| Toshiba             | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Maxtor              | 1        | 1      | 7.14%   |
| Apacer              | 1        | 1      | 7.14%   |
| A-DATA Technology   | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 33.33%  |
| Seagate             | 3        | 4      | 25%     |
| Hitachi             | 2        | 2      | 16.67%  |
| Toshiba             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Maxtor              | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 16     | 84.62%  |
| SSD  | 2        | 2      | 15.38%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1        | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1        | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |
| HGST                | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 37       | 65     | 42.53%  |
| Detected | 34       | 71     | 39.08%  |
| Malfunc  | 13       | 18     | 14.94%  |
| Failed   | 3        | 3      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 44       | 46.32%  |
| AMD                         | 24       | 25.26%  |
| Samsung Electronics         | 4        | 4.21%   |
| Nvidia                      | 4        | 4.21%   |
| SanDisk                     | 3        | 3.16%   |
| Micron/Crucial Technology   | 3        | 3.16%   |
| JMicron Technology          | 3        | 3.16%   |
| ASMedia Technology          | 3        | 3.16%   |
| VIA Technologies            | 2        | 2.11%   |
| Marvell Technology Group    | 2        | 2.11%   |
| Seagate Technology          | 1        | 1.05%   |
| LSI Logic / Symbios Logic   | 1        | 1.05%   |
| Kingston Technology Company | 1        | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12       | 9.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 11       | 8.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10       | 7.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5        | 3.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4        | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 3.08%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 2.31%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3        | 2.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 2.31%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 1.54%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 1.54%   |
| Nvidia MCP61 IDE                                                               | 2        | 1.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 1.54%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2        | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2        | 1.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.54%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2        | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.54%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.54%   |
| AMD FCH IDE Controller                                                         | 2        | 1.54%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.54%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 1        | 0.77%   |
| VIA Serial ATA Controller                                                      | 1        | 0.77%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.77%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.77%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.77%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1        | 0.77%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 1        | 0.77%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 1        | 0.77%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 0.77%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 51       | 51%     |
| IDE  | 33       | 33%     |
| NVMe | 11       | 11%     |
| RAID | 4        | 4%      |
| SAS  | 1        | 1%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 47       | 61.84%  |
| AMD    | 29       | 38.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 3.95%   |
| Intel Atom CPU D525 @ 1.80GHz                   | 3        | 3.95%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz          | 2        | 2.63%   |
| Intel Pentium D CPU 2.80GHz                     | 2        | 2.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 2.63%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 2        | 2.63%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 2.63%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 2        | 2.63%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 2.63%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 1.32%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz             | 1        | 1.32%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz             | 1        | 1.32%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 1.32%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 1.32%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 1.32%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 1.32%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1.32%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 1.32%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1.32%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1.32%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 1.32%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.32%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1.32%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 1        | 1.32%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.32%   |
| Intel Core i3-10105 CPU @ 3.70GHz               | 1        | 1.32%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 1        | 1.32%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.32%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz            | 1        | 1.32%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz            | 1        | 1.32%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 1.32%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 1.32%   |
| Intel Celeron N5105 @ 2.00GHz                   | 1        | 1.32%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1        | 1.32%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1        | 1.32%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 1        | 1.32%   |
| Intel Celeron CPU E3300 @ 2.50GHz               | 1        | 1.32%   |
| Intel Celeron CPU 847 @ 1.10GHz                 | 1        | 1.32%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 1        | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 9        | 11.84%  |
| Intel Celeron           | 8        | 10.53%  |
| Intel Core 2 Duo        | 6        | 7.89%   |
| Intel Atom              | 6        | 7.89%   |
| AMD Ryzen 5             | 5        | 6.58%   |
| AMD Ryzen 7             | 4        | 5.26%   |
| Intel Xeon              | 3        | 3.95%   |
| Intel Pentium Dual      | 3        | 3.95%   |
| Intel Core i3           | 3        | 3.95%   |
| AMD FX                  | 3        | 3.95%   |
| AMD Athlon 64 X2        | 3        | 3.95%   |
| Intel Pentium Dual-Core | 2        | 2.63%   |
| Intel Pentium D         | 2        | 2.63%   |
| Intel Core i7           | 2        | 2.63%   |
| Intel Core 2 Quad       | 2        | 2.63%   |
| AMD Phenom II X4        | 2        | 2.63%   |
| AMD A10                 | 2        | 2.63%   |
| Other                   | 1        | 1.32%   |
| Intel Core i9           | 1        | 1.32%   |
| AMD Ryzen 9             | 1        | 1.32%   |
| AMD Ryzen 5 PRO         | 1        | 1.32%   |
| AMD Phenom II X6        | 1        | 1.32%   |
| AMD GX                  | 1        | 1.32%   |
| AMD G                   | 1        | 1.32%   |
| AMD Athlon II X3        | 1        | 1.32%   |
| AMD Athlon II X2        | 1        | 1.32%   |
| AMD A8                  | 1        | 1.32%   |
| AMD A4                  | 1        | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 39.47%  |
| 4      | 25       | 32.89%  |
| 6      | 9        | 11.84%  |
| 8      | 5        | 6.58%   |
| 3      | 3        | 3.95%   |
| 1      | 3        | 3.95%   |
| 10     | 1        | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 65.79%  |
| 2      | 26       | 34.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 76       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 46.15%  |
| 0x1067a    | 5        | 6.41%   |
| 0x906ea    | 3        | 3.85%   |
| 0x106ca    | 3        | 3.85%   |
| 0x6fb      | 2        | 2.56%   |
| 0x406c4    | 2        | 2.56%   |
| 0x306c3    | 2        | 2.56%   |
| 0x206a7    | 2        | 2.56%   |
| 0x06003106 | 2        | 2.56%   |
| 0x010000db | 2        | 2.56%   |
| 0xa0653    | 1        | 1.28%   |
| 0x906c0    | 1        | 1.28%   |
| 0x706a8    | 1        | 1.28%   |
| 0x6fd      | 1        | 1.28%   |
| 0x506e3    | 1        | 1.28%   |
| 0x506c9    | 1        | 1.28%   |
| 0x306e4    | 1        | 1.28%   |
| 0x30679    | 1        | 1.28%   |
| 0x106a5    | 1        | 1.28%   |
| 0x0a50000c | 1        | 1.28%   |
| 0x0a50000b | 1        | 1.28%   |
| 0x0a201009 | 1        | 1.28%   |
| 0x08701021 | 1        | 1.28%   |
| 0x08701013 | 1        | 1.28%   |
| 0x08001138 | 1        | 1.28%   |
| 0x0700010f | 1        | 1.28%   |
| 0x06001119 | 1        | 1.28%   |
| 0x06000852 | 1        | 1.28%   |
| 0x010000c7 | 1        | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 8        | 10.53%  |
| Core          | 6        | 7.89%   |
| K10           | 5        | 6.58%   |
| Zen 3         | 4        | 5.26%   |
| Silvermont    | 4        | 5.26%   |
| K8 Hammer     | 4        | 5.26%   |
| Haswell       | 4        | 5.26%   |
| Bonnell       | 4        | 5.26%   |
| Zen+          | 3        | 3.95%   |
| SandyBridge   | 3        | 3.95%   |
| Piledriver    | 3        | 3.95%   |
| KabyLake      | 3        | 3.95%   |
| IvyBridge     | 3        | 3.95%   |
| Zen 2         | 2        | 2.63%   |
| Zen           | 2        | 2.63%   |
| Steamroller   | 2        | 2.63%   |
| Skylake       | 2        | 2.63%   |
| NetBurst      | 2        | 2.63%   |
| Nehalem       | 2        | 2.63%   |
| Goldmont plus | 2        | 2.63%   |
| CometLake     | 2        | 2.63%   |
| Tremont       | 1        | 1.32%   |
| K10 Llano     | 1        | 1.32%   |
| Jaguar        | 1        | 1.32%   |
| Goldmont      | 1        | 1.32%   |
| Bulldozer     | 1        | 1.32%   |
| Bobcat        | 1        | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 29       | 35.8%   |
| Nvidia | 28       | 34.57%  |
| Intel  | 24       | 29.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 4.65%   |
| Nvidia GT218 [ION]                                                                       | 3        | 3.49%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 3.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 3.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 3.49%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 3.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 3.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 2.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 2.33%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 2.33%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 2.33%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 2.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 2.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 2.33%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 1.16%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 1.16%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 1.16%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.16%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1        | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.16%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 1.16%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 1.16%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 1.16%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.16%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 1.16%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 1.16%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.16%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 1.16%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 1.16%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 1.16%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.16%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 1.16%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 1        | 1.16%   |
| Nvidia C78 [GeForce 9100]                                                                | 1        | 1.16%   |
| Nvidia C77 [GeForce 8200]                                                                | 1        | 1.16%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.16%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 1        | 1.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 25       | 32.89%  |
| 1 x AMD            | 23       | 30.26%  |
| 1 x Intel          | 21       | 27.63%  |
| 2 x AMD            | 3        | 3.95%   |
| AMD + Nvidia       | 2        | 2.63%   |
| Intel + 2 x Nvidia | 1        | 1.32%   |
| Intel + 2 x AMD    | 1        | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 80.26%  |
| Proprietary | 11       | 14.47%  |
| Unknown     | 4        | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 61.04%  |
| 0.01-0.5   | 9        | 11.69%  |
| 0.51-1.0   | 8        | 10.39%  |
| 7.01-8.0   | 5        | 6.49%   |
| 1.01-2.0   | 3        | 3.9%    |
| 3.01-4.0   | 2        | 2.6%    |
| 8.01-16.0  | 2        | 2.6%    |
| 2.01-3.0   | 1        | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 17.14%  |
| Dell                 | 8        | 11.43%  |
| Hewlett-Packard      | 7        | 10%     |
| Goldstar             | 6        | 8.57%   |
| Philips              | 4        | 5.71%   |
| Acer                 | 4        | 5.71%   |
| Eizo                 | 3        | 4.29%   |
| Ancor Communications | 3        | 4.29%   |
| Sony                 | 2        | 2.86%   |
| Iiyama               | 2        | 2.86%   |
| HannStar             | 2        | 2.86%   |
| Westinghouse         | 1        | 1.43%   |
| Vizio                | 1        | 1.43%   |
| ViewSonic            | 1        | 1.43%   |
| VHT                  | 1        | 1.43%   |
| Unknown (ADA)        | 1        | 1.43%   |
| Unknown              | 1        | 1.43%   |
| SNC                  | 1        | 1.43%   |
| Sharp                | 1        | 1.43%   |
| Sampo                | 1        | 1.43%   |
| Positivo             | 1        | 1.43%   |
| MSI                  | 1        | 1.43%   |
| LG Electronics       | 1        | 1.43%   |
| Jean                 | 1        | 1.43%   |
| Daewoo               | 1        | 1.43%   |
| Compal               | 1        | 1.43%   |
| BenQ                 | 1        | 1.43%   |
| Belinea              | 1        | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 2.78%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1        | 1.39%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                | 1        | 1.39%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 1.39%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 1.39%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 1.39%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1        | 1.39%   |
| Sony TV SNY9C01 1360x768                                             | 1        | 1.39%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1        | 1.39%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 1.39%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 1.39%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 1.39%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 1.39%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 440x250mm 19.9-inch     | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                  | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 1.39%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 1.39%   |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch    | 1        | 1.39%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                        | 1        | 1.39%   |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch               | 1        | 1.39%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 1        | 1.39%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1        | 1.39%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                 | 1        | 1.39%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                   | 1        | 1.39%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                  | 1        | 1.39%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.39%   |
| Jean JT178x4 JEN0DB2 1280x1024 338x270mm 17.0-inch                   | 1        | 1.39%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                 | 1        | 1.39%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                 | 1        | 1.39%   |
| Hewlett-Packard w2338h HWP281B 1920x1080 510x290mm 23.1-inch         | 1        | 1.39%   |
| Hewlett-Packard W2071d HWP299E 1600x900 443x249mm 20.0-inch          | 1        | 1.39%   |
| Hewlett-Packard E201 HWP305E 1600x900 440x250mm 19.9-inch            | 1        | 1.39%   |
| Hewlett-Packard Compaq CQ1569 HWP2836 1366x768 344x194mm 15.5-inch   | 1        | 1.39%   |
| Hewlett-Packard 2311 HWP293A 1920x1080 509x286mm 23.0-inch           | 1        | 1.39%   |
| Hewlett-Packard 2310 HWP2890 1920x1080 510x287mm 23.0-inch           | 1        | 1.39%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch            | 1        | 1.39%   |
| HannStar HL190APB HSD62C3 1366x768 410x230mm 18.5-inch               | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 34.78%  |
| 1280x1024 (SXGA)   | 9        | 13.04%  |
| 1680x1050 (WSXGA+) | 7        | 10.14%  |
| 1366x768 (WXGA)    | 7        | 10.14%  |
| 1600x900 (HD+)     | 5        | 7.25%   |
| 2560x1440 (QHD)    | 3        | 4.35%   |
| 1440x900 (WXGA+)   | 3        | 4.35%   |
| 1360x768           | 3        | 4.35%   |
| 800x600            | 1        | 1.45%   |
| 3840x2160 (4K)     | 1        | 1.45%   |
| 2560x1600          | 1        | 1.45%   |
| 1920x1200 (WUXGA)  | 1        | 1.45%   |
| 1280x800 (WXGA)    | 1        | 1.45%   |
| 1280x768           | 1        | 1.45%   |
| 1280x720 (HD)      | 1        | 1.45%   |
| 1024x768 (XGA)     | 1        | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 9        | 13.04%  |
| 27      | 7        | 10.14%  |
| 24      | 7        | 10.14%  |
| 22      | 7        | 10.14%  |
| 23      | 6        | 8.7%    |
| 19      | 6        | 8.7%    |
| Unknown | 6        | 8.7%    |
| 21      | 4        | 5.8%    |
| 20      | 4        | 5.8%    |
| 17      | 3        | 4.35%   |
| 15      | 2        | 2.9%    |
| 72      | 1        | 1.45%   |
| 49      | 1        | 1.45%   |
| 47      | 1        | 1.45%   |
| 43      | 1        | 1.45%   |
| 34      | 1        | 1.45%   |
| 14      | 1        | 1.45%   |
| 8       | 1        | 1.45%   |
| 7       | 1        | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 26       | 37.68%  |
| 501-600     | 20       | 28.99%  |
| 301-350     | 6        | 8.7%    |
| Unknown     | 6        | 8.7%    |
| 351-400     | 4        | 5.8%    |
| 101-200     | 2        | 2.9%    |
| 1001-1500   | 2        | 2.9%    |
| 701-800     | 1        | 1.45%   |
| 1501-2000   | 1        | 1.45%   |
| 901-1000    | 1        | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 59.7%   |
| 16/10   | 11       | 16.42%  |
| 5/4     | 7        | 10.45%  |
| Unknown | 5        | 7.46%   |
| 4/3     | 3        | 4.48%   |
| 3/2     | 1        | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 27.94%  |
| 151-200        | 13       | 19.12%  |
| 141-150        | 10       | 14.71%  |
| 301-350        | 7        | 10.29%  |
| Unknown        | 6        | 8.82%   |
| 251-300        | 3        | 4.41%   |
| 501-1000       | 3        | 4.41%   |
| More than 1000 | 2        | 2.94%   |
| 1-40           | 2        | 2.94%   |
| 81-90          | 1        | 1.47%   |
| 111-120        | 1        | 1.47%   |
| 101-110        | 1        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 43       | 65.15%  |
| 101-120 | 10       | 15.15%  |
| Unknown | 6        | 9.09%   |
| 1-50    | 5        | 7.58%   |
| 161-240 | 2        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 85.53%  |
| 2     | 7        | 9.21%   |
| 0     | 4        | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 48       | 44.04%  |
| Intel                           | 23       | 21.1%   |
| Qualcomm Atheros                | 9        | 8.26%   |
| TP-Link                         | 4        | 3.67%   |
| Broadcom                        | 4        | 3.67%   |
| Nvidia                          | 3        | 2.75%   |
| VIA Technologies                | 2        | 1.83%   |
| Samsung Electronics             | 2        | 1.83%   |
| Qualcomm Atheros Communications | 2        | 1.83%   |
| NetGear                         | 2        | 1.83%   |
| MediaTek                        | 2        | 1.83%   |
| Trident Microsystems            | 1        | 0.92%   |
| Texas Instruments               | 1        | 0.92%   |
| Ralink                          | 1        | 0.92%   |
| Marvell Technology Group        | 1        | 0.92%   |
| ICS Advent                      | 1        | 0.92%   |
| Broadcom Limited                | 1        | 0.92%   |
| ASUSTek Computer                | 1        | 0.92%   |
| Accton Technology               | 1        | 0.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 41       | 35.04%  |
| Intel Ethernet Controller I225-V                                    | 3        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 2.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 2        | 1.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 1.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 1.71%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 1.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.71%   |
| Nvidia MCP77 Ethernet                                               | 2        | 1.71%   |
| NetGear A6210                                                       | 2        | 1.71%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2        | 1.71%   |
| Intel I211 Gigabit Network Connection                               | 2        | 1.71%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 1.71%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 1.71%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 1.71%   |
| Trident Microsystems 4DWave DX                                      | 1        | 0.85%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 0.85%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.85%   |
| Texas Instruments CC2531 ZigBee                                     | 1        | 0.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.85%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.85%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 0.85%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.85%   |
| Realtek 802.11ac NIC                                                | 1        | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.85%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 1        | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 0.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 9        | 25.71%  |
| Intel                           | 6        | 17.14%  |
| TP-Link                         | 4        | 11.43%  |
| Qualcomm Atheros                | 4        | 11.43%  |
| Broadcom                        | 3        | 8.57%   |
| Qualcomm Atheros Communications | 2        | 5.71%   |
| NetGear                         | 2        | 5.71%   |
| MediaTek                        | 2        | 5.71%   |
| Ralink                          | 1        | 2.86%   |
| Broadcom Limited                | 1        | 2.86%   |
| ASUSTek Computer                | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 5.71%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 5.71%   |
| NetGear A6210                                                       | 2        | 5.71%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 5.71%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 2.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 2.86%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 2.86%   |
| TP-Link 802.11ac NIC                                                | 1        | 2.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 2.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 2.86%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 2.86%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 2.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 2.86%   |
| Realtek 802.11ac NIC                                                | 1        | 2.86%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 2.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 2.86%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 2.86%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 2.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 2.86%   |
| Intel Wireless 7265                                                 | 1        | 2.86%   |
| Intel Wireless 3165                                                 | 1        | 2.86%   |
| Intel Wi-Fi 6 AX200                                                 | 1        | 2.86%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1        | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 2.86%   |
| Intel Centrino Advanced-N 6235                                      | 1        | 2.86%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                             | 1        | 2.86%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                   | 1        | 2.86%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]      | 1        | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 45       | 56.96%  |
| Intel                    | 17       | 21.52%  |
| Qualcomm Atheros         | 6        | 7.59%   |
| Nvidia                   | 3        | 3.8%    |
| VIA Technologies         | 2        | 2.53%   |
| Trident Microsystems     | 1        | 1.27%   |
| Samsung Electronics      | 1        | 1.27%   |
| Marvell Technology Group | 1        | 1.27%   |
| ICS Advent               | 1        | 1.27%   |
| Broadcom                 | 1        | 1.27%   |
| Accton Technology        | 1        | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41       | 51.25%  |
| Intel Ethernet Controller I225-V                                  | 3        | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.75%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 2.5%    |
| Nvidia MCP77 Ethernet                                             | 2        | 2.5%    |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 2        | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.5%    |
| Trident Microsystems 4DWave DX                                    | 1        | 1.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.25%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.25%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.25%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.25%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.25%   |
| Intel 82567V-3 Gigabit Network Connection                         | 1        | 1.25%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.25%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 1.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.25%   |
| Accton SMC2-1211TX                                                | 1        | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 75       | 68.81%  |
| WiFi     | 32       | 29.36%  |
| Modem    | 2        | 1.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 70.13%  |
| WiFi     | 23       | 29.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 69.74%  |
| 2     | 19       | 25%     |
| 3     | 2        | 2.63%   |
| 4     | 1        | 1.32%   |
| 0     | 1        | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 72.37%  |
| Yes  | 21       | 27.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 33.33%  |
| MediaTek                        | 2        | 13.33%  |
| Cambridge Silicon Radio         | 2        | 13.33%  |
| TP-Link                         | 1        | 6.67%   |
| Realtek Semiconductor           | 1        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| Logitech                        | 1        | 6.67%   |
| Foxconn / Hon Hai               | 1        | 6.67%   |
| Broadcom                        | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                            | 2        | 13.33%  |
| Intel Bluetooth wireless interface                  | 2        | 13.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 13.33%  |
| TP-Link UB500 Adapter                               | 1        | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 6.67%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 6.67%   |
| Intel AX200 Bluetooth                               | 1        | 6.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 43       | 38.05%  |
| AMD                                          | 31       | 27.43%  |
| Nvidia                                       | 25       | 22.12%  |
| VIA Technologies                             | 3        | 2.65%   |
| C-Media Electronics                          | 3        | 2.65%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.88%   |
| Sony                                         | 1        | 0.88%   |
| Razer USA                                    | 1        | 0.88%   |
| GN Netcom                                    | 1        | 0.88%   |
| Focusrite-Novation                           | 1        | 0.88%   |
| Ensoniq                                      | 1        | 0.88%   |
| Creative Labs                                | 1        | 0.88%   |
| ASUSTek Computer                             | 1        | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 14       | 10.53%  |
| Nvidia High Definition Audio Controller                                     | 7        | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 7        | 5.26%   |
| AMD FCH Azalia Controller                                                   | 5        | 3.76%   |
| AMD Family 17h/19h HD Audio Controller                                      | 5        | 3.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 3        | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                  | 3        | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 3        | 2.26%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                           | 3        | 2.26%   |
| AMD Starship/Matisse HD Audio Controller                                    | 3        | 2.26%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                        | 3        | 2.26%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 3        | 2.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 3        | 2.26%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                   | 2        | 1.5%    |
| Nvidia MCP61 High Definition Audio                                          | 2        | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                             | 2        | 1.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 2        | 1.5%    |
| Nvidia GK106 HDMI Audio Controller                                          | 2        | 1.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                | 2        | 1.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller              | 2        | 1.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 2        | 1.5%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 2        | 1.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 2        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 2        | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 2        | 1.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                            | 2        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 2        | 1.5%    |
| AMD Kaveri HDMI/DP Audio Controller                                         | 2        | 1.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 2        | 1.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2        | 1.5%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID              | 1        | 0.75%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 1        | 0.75%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 1        | 0.75%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.75%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                | 1        | 0.75%   |
| Razer USA Razer Kraken X USB                                                | 1        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                               | 1        | 0.75%   |
| Nvidia TU104 HD Audio Controller                                            | 1        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                               | 1        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 25.49%  |
| Micron Technology   | 6        | 11.76%  |
| Kingston            | 6        | 11.76%  |
| SK hynix            | 4        | 7.84%   |
| Samsung Electronics | 4        | 7.84%   |
| G.Skill             | 4        | 7.84%   |
| Corsair             | 4        | 7.84%   |
| Unknown             | 3        | 5.88%   |
| Crucial             | 2        | 3.92%   |
| Unknown (ABCD)      | 1        | 1.96%   |
| Patriot             | 1        | 1.96%   |
| Nanya Technology    | 1        | 1.96%   |
| GOODRAM             | 1        | 1.96%   |
| Elpida              | 1        | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 3        | 5.26%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 3.51%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 2        | 3.51%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s           | 2        | 3.51%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 1.75%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                     | 1        | 1.75%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                       | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM                                    | 1        | 1.75%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 1.75%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s       | 1        | 1.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.75%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                     | 1        | 1.75%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s        | 1        | 1.75%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.75%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.75%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.75%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s                | 1        | 1.75%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.75%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2667MT/s            | 1        | 1.75%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s                | 1        | 1.75%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s             | 1        | 1.75%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                       | 1        | 1.75%   |
| Micron RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s         | 1        | 1.75%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1        | 1.75%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s             | 1        | 1.75%   |
| Micron RAM 16JTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s        | 1        | 1.75%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s         | 1        | 1.75%   |
| Kingston RAM KN2M64-ETB 8GB DIMM DDR3 1600MT/s                 | 1        | 1.75%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 1        | 1.75%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s        | 1        | 1.75%   |
| Kingston RAM 99U5474-028.A 4GB DIMM DDR3 1333MT/s              | 1        | 1.75%   |
| GOODRAM RAM IRX3200D464L16S/8G 8GB DIMM DDR4 3200MT/s          | 1        | 1.75%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3666MT/s            | 1        | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 16       | 34.04%  |
| DDR3    | 16       | 34.04%  |
| DDR2    | 7        | 14.89%  |
| Unknown | 4        | 8.51%   |
| SDRAM   | 3        | 6.38%   |
| LPDDR4  | 1        | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 37       | 80.43%  |
| SODIMM | 9        | 19.57%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 29.41%  |
| 2048  | 15       | 29.41%  |
| 4096  | 13       | 25.49%  |
| 16384 | 6        | 11.76%  |
| 32768 | 1        | 1.96%   |
| 1024  | 1        | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 11       | 22.92%  |
| 3200    | 6        | 12.5%   |
| 1333    | 4        | 8.33%   |
| 667     | 3        | 6.25%   |
| Unknown | 3        | 6.25%   |
| 3400    | 2        | 4.17%   |
| 2800    | 2        | 4.17%   |
| 2667    | 2        | 4.17%   |
| 2400    | 2        | 4.17%   |
| 2133    | 2        | 4.17%   |
| 1866    | 2        | 4.17%   |
| 800     | 2        | 4.17%   |
| 3933    | 1        | 2.08%   |
| 3666    | 1        | 2.08%   |
| 3066    | 1        | 2.08%   |
| 2048    | 1        | 2.08%   |
| 1066    | 1        | 2.08%   |
| 533     | 1        | 2.08%   |
| 333     | 1        | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 2        | 50%     |
| Samsung Electronics | 1        | 25%     |
| Brother Industries  | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung SCX-4200 series | 1        | 25%     |
| Canon PIXMA MP250       | 1        | 25%     |
| Canon LiDE 300          | 1        | 25%     |
| Brother DCP-7055W       | 1        | 25%     |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 4        | 44.44%  |
| WaveRider Communications | 1        | 11.11%  |
| Pixart Imaging           | 1        | 11.11%  |
| Microsoft                | 1        | 11.11%  |
| Generalplus Technology   | 1        | 11.11%  |
| AVerMedia Technologies   | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 2        | 22.22%  |
| WaveRider USB 2.0 Camera                 | 1        | 11.11%  |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1        | 11.11%  |
| Microsoft LifeCam VX-800                 | 1        | 11.11%  |
| Logitech Webcam C170                     | 1        | 11.11%  |
| Logitech HD Webcam C615                  | 1        | 11.11%  |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 11.11%  |
| AVerMedia Live Streamer CAM 313          | 1        | 11.11%  |

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


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Cherry | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Cherry SmartCard Reader Keyboard KC 1000 SC | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 67       | 87.01%  |
| 1     | 8        | 10.39%  |
| 2     | 2        | 2.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 41.67%  |
| Net/wireless             | 4        | 33.33%  |
| Sound                    | 1        | 8.33%   |
| Net/ethernet             | 1        | 8.33%   |
| Communication controller | 1        | 8.33%   |

