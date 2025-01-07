Linux in Israel - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

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

Total: 516

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | G31M-ES2L                   | [ba9c0c5153](https://linux-hardware.org/?probe=ba9c0c5153) | Dec 23, 2024 |
| Dell          | 0NC2VH A01                  | [4810f67ef7](https://linux-hardware.org/?probe=4810f67ef7) | Dec 15, 2024 |
| Dell          | 0TTDMJ A00                  | [4ee281d915](https://linux-hardware.org/?probe=4ee281d915) | Dec 11, 2024 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [e25da0298a](https://linux-hardware.org/?probe=e25da0298a) | Dec 06, 2024 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [0dc0dd7a62](https://linux-hardware.org/?probe=0dc0dd7a62) | Nov 20, 2024 |
| MSI           | H370 GAMING PLUS            | [73b7ffd3d7](https://linux-hardware.org/?probe=73b7ffd3d7) | Nov 13, 2024 |
| MSI           | H370 GAMING PLUS            | [967037bf19](https://linux-hardware.org/?probe=967037bf19) | Nov 13, 2024 |
| Gigabyte      | H61M-S2PV                   | [fb1cba8a45](https://linux-hardware.org/?probe=fb1cba8a45) | Nov 11, 2024 |
| Gigabyte      | B365M DS3H                  | [6dc9cbaf0c](https://linux-hardware.org/?probe=6dc9cbaf0c) | Nov 06, 2024 |
| Gigabyte      | B365M DS3H                  | [532b386733](https://linux-hardware.org/?probe=532b386733) | Nov 06, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [725759c6d6](https://linux-hardware.org/?probe=725759c6d6) | Oct 14, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [441346e35f](https://linux-hardware.org/?probe=441346e35f) | Oct 14, 2024 |
| Gigabyte      | B150M-D3H-CF                | [b3f66f8d51](https://linux-hardware.org/?probe=b3f66f8d51) | Oct 07, 2024 |
| Gigabyte      | Z690M DS3H DDR4             | [21cc874a16](https://linux-hardware.org/?probe=21cc874a16) | Oct 03, 2024 |
| Gigabyte      | Z690 AORUS ELITE AX         | [4a6207dc35](https://linux-hardware.org/?probe=4a6207dc35) | Oct 03, 2024 |
| HP            | 8597                        | [39f106b002](https://linux-hardware.org/?probe=39f106b002) | Sep 29, 2024 |
| Shenzhen M... | AHWSA                       | [b2095e6211](https://linux-hardware.org/?probe=b2095e6211) | Sep 16, 2024 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [8593e26a94](https://linux-hardware.org/?probe=8593e26a94) | Sep 11, 2024 |
| Shenzhen M... | AHWSA                       | [8279710a58](https://linux-hardware.org/?probe=8279710a58) | Sep 09, 2024 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [508cc6407e](https://linux-hardware.org/?probe=508cc6407e) | Sep 02, 2024 |
| MSI           | MPG Z790I EDGE WIFI         | [befece1a07](https://linux-hardware.org/?probe=befece1a07) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | [73df0e9be3](https://linux-hardware.org/?probe=73df0e9be3) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | [c3687b0959](https://linux-hardware.org/?probe=c3687b0959) | Aug 28, 2024 |
| HP            | 18E4                        | [d92f2ebee9](https://linux-hardware.org/?probe=d92f2ebee9) | Aug 22, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [d91c8a70ea](https://linux-hardware.org/?probe=d91c8a70ea) | Aug 21, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | [ff71054b4c](https://linux-hardware.org/?probe=ff71054b4c) | Aug 20, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | [1cceda0c67](https://linux-hardware.org/?probe=1cceda0c67) | Aug 20, 2024 |
| ASUSTek       | PRIME B365M-A               | [7e7177ec16](https://linux-hardware.org/?probe=7e7177ec16) | Aug 19, 2024 |
| HP            | 1497                        | [3eea55dbb0](https://linux-hardware.org/?probe=3eea55dbb0) | Aug 18, 2024 |
| ASUSTek       | H61M-E                      | [61f7b339bb](https://linux-hardware.org/?probe=61f7b339bb) | Aug 16, 2024 |
| PC Engines    | APU2                        | [d9b2540ad8](https://linux-hardware.org/?probe=d9b2540ad8) | Aug 09, 2024 |
| PC Engines    | APU2                        | [eb8b44a1a2](https://linux-hardware.org/?probe=eb8b44a1a2) | Aug 09, 2024 |
| JINGSHA       | X99-D8I                     | [562c50431e](https://linux-hardware.org/?probe=562c50431e) | Aug 07, 2024 |
| ASUSTek       | PRIME H410M-K               | [f97ebe97b9](https://linux-hardware.org/?probe=f97ebe97b9) | Aug 04, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | [75d20750c2](https://linux-hardware.org/?probe=75d20750c2) | Aug 04, 2024 |
| Lenovo        | NO DPK                      | [6cdf96758d](https://linux-hardware.org/?probe=6cdf96758d) | Aug 01, 2024 |
| Unknown       | Unknown                     | [74167b2017](https://linux-hardware.org/?probe=74167b2017) | Jul 21, 2024 |
| Gigabyte      | Z370 HD3P-CF                | [aa09fbc967](https://linux-hardware.org/?probe=aa09fbc967) | Jul 19, 2024 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [6b85eb16fe](https://linux-hardware.org/?probe=6b85eb16fe) | Jul 14, 2024 |
| ASRock        | H71M-DGS                    | [53971fc966](https://linux-hardware.org/?probe=53971fc966) | Jul 06, 2024 |
| Gigabyte      | G31M-ES2L                   | [bb1db7e4cf](https://linux-hardware.org/?probe=bb1db7e4cf) | Jul 06, 2024 |
| MSI           | PRO Z790-S WIFI             | [b2e22eb2a7](https://linux-hardware.org/?probe=b2e22eb2a7) | Jun 21, 2024 |
| Intel         | DH77EB AAG39073-304         | [3ed708f769](https://linux-hardware.org/?probe=3ed708f769) | Jun 14, 2024 |
| ASUSTek       | PRIME Z390-P                | [4ca7b4e167](https://linux-hardware.org/?probe=4ca7b4e167) | Jun 14, 2024 |
| Intel         | DH77EB AAG39073-304         | [85ba61cf34](https://linux-hardware.org/?probe=85ba61cf34) | Jun 13, 2024 |
| ASUSTek       | PRIME B550M-A               | [4d2d75e2c0](https://linux-hardware.org/?probe=4d2d75e2c0) | Jun 10, 2024 |
| ASUSTek       | H110M-K                     | [d4368125e3](https://linux-hardware.org/?probe=d4368125e3) | Jun 05, 2024 |
| ASUSTek       | H110M-K                     | [173ed79481](https://linux-hardware.org/?probe=173ed79481) | Jun 05, 2024 |
| Gigabyte      | H97M-D3H                    | [81620a0d8c](https://linux-hardware.org/?probe=81620a0d8c) | Jun 04, 2024 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [7fd5b705f5](https://linux-hardware.org/?probe=7fd5b705f5) | May 21, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | [dc23737df9](https://linux-hardware.org/?probe=dc23737df9) | May 12, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | [775f9b664d](https://linux-hardware.org/?probe=775f9b664d) | May 12, 2024 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [53dc445161](https://linux-hardware.org/?probe=53dc445161) | May 10, 2024 |
| Intel         | DH77EB AAG39073-304         | [6fd6f40abe](https://linux-hardware.org/?probe=6fd6f40abe) | May 08, 2024 |
| MSI           | H170M PRO-VDH               | [88dbd5e70e](https://linux-hardware.org/?probe=88dbd5e70e) | Apr 29, 2024 |
| ASUSTek       | H110I-PLUS                  | [14706b4b9f](https://linux-hardware.org/?probe=14706b4b9f) | Apr 28, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [8eb518c57d](https://linux-hardware.org/?probe=8eb518c57d) | Apr 26, 2024 |
| Dell          | 0KP561                      | [dd6f49d82f](https://linux-hardware.org/?probe=dd6f49d82f) | Apr 06, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [690e191e65](https://linux-hardware.org/?probe=690e191e65) | Mar 26, 2024 |
| ASUSTek       | PRIME H310M-A               | [972b9375c7](https://linux-hardware.org/?probe=972b9375c7) | Mar 16, 2024 |
| Lenovo        | 3176 SDK0K17763 WIN 1801... | [51143831ed](https://linux-hardware.org/?probe=51143831ed) | Mar 12, 2024 |
| ASUSTek       | PRIME A520M-K               | [859c361cb9](https://linux-hardware.org/?probe=859c361cb9) | Mar 12, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | [120f62e576](https://linux-hardware.org/?probe=120f62e576) | Mar 08, 2024 |
| Dell          | 0NC2VH A01                  | [3b3cdc41db](https://linux-hardware.org/?probe=3b3cdc41db) | Mar 07, 2024 |
| Gigabyte      | Z490 VISION G               | [23347b4c30](https://linux-hardware.org/?probe=23347b4c30) | Mar 02, 2024 |
| Gigabyte      | Z490 VISION G               | [f202c83002](https://linux-hardware.org/?probe=f202c83002) | Mar 02, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [4141eaaff5](https://linux-hardware.org/?probe=4141eaaff5) | Feb 25, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [c3f8f76b3a](https://linux-hardware.org/?probe=c3f8f76b3a) | Feb 24, 2024 |
| ASUSTek       | PRIME H310M-K               | [082308a172](https://linux-hardware.org/?probe=082308a172) | Feb 12, 2024 |
| Gigabyte      | B550 AORUS ELITE            | [44bda25372](https://linux-hardware.org/?probe=44bda25372) | Feb 08, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [87f113db8c](https://linux-hardware.org/?probe=87f113db8c) | Feb 03, 2024 |
| Gigabyte      | EP45T-UD3R                  | [d3aaef580d](https://linux-hardware.org/?probe=d3aaef580d) | Jan 28, 2024 |
| Gigabyte      | PH67A-D3-B3                 | [27878d88fd](https://linux-hardware.org/?probe=27878d88fd) | Jan 23, 2024 |
| Gigabyte      | Z790 UD AX                  | [a84ee0f485](https://linux-hardware.org/?probe=a84ee0f485) | Jan 23, 2024 |
| ASUSTek       | PRIME B365-PLUS             | [042f4d56ce](https://linux-hardware.org/?probe=042f4d56ce) | Jan 06, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [f42a6325e3](https://linux-hardware.org/?probe=f42a6325e3) | Dec 29, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [0d4c53d42f](https://linux-hardware.org/?probe=0d4c53d42f) | Dec 28, 2023 |
| Gigabyte      | B460M GAMING HD             | [6669971369](https://linux-hardware.org/?probe=6669971369) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [9425eb3c77](https://linux-hardware.org/?probe=9425eb3c77) | Dec 23, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [2464a532b8](https://linux-hardware.org/?probe=2464a532b8) | Dec 20, 2023 |
| Intel         | H61                         | [01b739e240](https://linux-hardware.org/?probe=01b739e240) | Dec 20, 2023 |
| Lenovo        | 310C SDK0J40705 WIN 3425... | [c1ee1cd84d](https://linux-hardware.org/?probe=c1ee1cd84d) | Dec 19, 2023 |
| Gigabyte      | H61M-S1                     | [44c8944047](https://linux-hardware.org/?probe=44c8944047) | Dec 18, 2023 |
| HP            | 18E4                        | [1dd0e805dc](https://linux-hardware.org/?probe=1dd0e805dc) | Dec 13, 2023 |
| Acer          | Predator G3610              | [0a8a3e6bc5](https://linux-hardware.org/?probe=0a8a3e6bc5) | Dec 10, 2023 |
| ASUSTek       | Q87M-E                      | [9bb3c76c9f](https://linux-hardware.org/?probe=9bb3c76c9f) | Dec 10, 2023 |
| ASUSTek       | D540MA-C                    | [a5beb93a51](https://linux-hardware.org/?probe=a5beb93a51) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [d28a7f3ad6](https://linux-hardware.org/?probe=d28a7f3ad6) | Dec 04, 2023 |
| ASUSTek       | Z170-P                      | [55eb62ad2f](https://linux-hardware.org/?probe=55eb62ad2f) | Dec 02, 2023 |
| ASUSTek       | B85M-G                      | [dac97296b0](https://linux-hardware.org/?probe=dac97296b0) | Nov 26, 2023 |
| ASUSTek       | B85M-G                      | [be36e8725c](https://linux-hardware.org/?probe=be36e8725c) | Nov 26, 2023 |
| MSI           | H77MA-G43                   | [f191f17f2a](https://linux-hardware.org/?probe=f191f17f2a) | Nov 14, 2023 |
| MSI           | H77MA-G43                   | [a814c93afe](https://linux-hardware.org/?probe=a814c93afe) | Nov 09, 2023 |
| MSI           | MS-1T31                     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| Gigabyte      | H81M-S1                     | [3dc549dba2](https://linux-hardware.org/?probe=3dc549dba2) | Oct 09, 2023 |
| Dell          | 0GTK4K A02                  | [05d87a2b59](https://linux-hardware.org/?probe=05d87a2b59) | Oct 08, 2023 |
| Dell          | 0GTK4K A02                  | [7480d29d9f](https://linux-hardware.org/?probe=7480d29d9f) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d5b22876c6](https://linux-hardware.org/?probe=d5b22876c6) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [18c399ea1e](https://linux-hardware.org/?probe=18c399ea1e) | Oct 04, 2023 |
| Gigabyte      | H77-D3H                     | [3d7d389342](https://linux-hardware.org/?probe=3d7d389342) | Sep 24, 2023 |
| Gigabyte      | 945GCMX-S2                  | [264e42215e](https://linux-hardware.org/?probe=264e42215e) | Sep 19, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [951faca7d0](https://linux-hardware.org/?probe=951faca7d0) | Sep 11, 2023 |
| ASUSTek       | PRIME Z490-P                | [433e6a45a9](https://linux-hardware.org/?probe=433e6a45a9) | Sep 11, 2023 |
| Gigabyte      | H61M-S2PV                   | [29d9f2566a](https://linux-hardware.org/?probe=29d9f2566a) | Sep 06, 2023 |
| ASRock        | Z490M-ITX/ac                | [681020d244](https://linux-hardware.org/?probe=681020d244) | Sep 01, 2023 |
| Gigabyte      | B150M-D3H-CF                | [b37d00fb4d](https://linux-hardware.org/?probe=b37d00fb4d) | Sep 01, 2023 |
| Gigabyte      | H61M-D2-B3                  | [6ffb2379fa](https://linux-hardware.org/?probe=6ffb2379fa) | Aug 30, 2023 |
| ASUSTek       | D540MA-C                    | [67eb1455a6](https://linux-hardware.org/?probe=67eb1455a6) | Aug 30, 2023 |
| Dell          | 0X75JG A01                  | [bdf9baca2f](https://linux-hardware.org/?probe=bdf9baca2f) | Aug 29, 2023 |
| ASUSTek       | H110M-A/M.2                 | [e45572b49a](https://linux-hardware.org/?probe=e45572b49a) | Aug 23, 2023 |
| Dell          | 0215PR A02                  | [dd5966ce9b](https://linux-hardware.org/?probe=dd5966ce9b) | Aug 23, 2023 |
| ASUSTek       | Z10PG-D24 Series            | [127be55832](https://linux-hardware.org/?probe=127be55832) | Aug 23, 2023 |
| ASRock        | Z490M-ITX/ac                | [a554b5fcd4](https://linux-hardware.org/?probe=a554b5fcd4) | Aug 22, 2023 |
| Gigabyte      | B150M-D3H-CF                | [a662b29087](https://linux-hardware.org/?probe=a662b29087) | Aug 21, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [28a27adc22](https://linux-hardware.org/?probe=28a27adc22) | Aug 20, 2023 |
| HP            | 805D                        | [672e431e69](https://linux-hardware.org/?probe=672e431e69) | Aug 06, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [0e28c2aae2](https://linux-hardware.org/?probe=0e28c2aae2) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| Gigabyte      | H61M-DS2                    | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | PRIME B365M-K               | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| Gigabyte      | H61M-DS2                    | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| Huanan        | X79 V7.11                   | [79bbc880ba](https://linux-hardware.org/?probe=79bbc880ba) | Jun 03, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | H61M-S2PV                   | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [16d7a61394](https://linux-hardware.org/?probe=16d7a61394) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| Gigabyte      | H61M-DS2                    | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| MSI           | H61M-E23                    | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| MSI           | B450M MORTAR MAX            | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| Gigabyte      | Z97X-UD5H                   | [1cb8a5dfb4](https://linux-hardware.org/?probe=1cb8a5dfb4) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6d206f88cb](https://linux-hardware.org/?probe=6d206f88cb) | Apr 16, 2023 |
| Gigabyte      | B560M H                     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [c47d5d79fd](https://linux-hardware.org/?probe=c47d5d79fd) | Apr 13, 2023 |
| Intel         | D945GCCR AAD78647-301       | [fac1992089](https://linux-hardware.org/?probe=fac1992089) | Apr 13, 2023 |
| Gigabyte      | B560M H                     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | 8455                        | [a52e3d086a](https://linux-hardware.org/?probe=a52e3d086a) | Apr 04, 2023 |
| Dell          | 0GDG8Y A02                  | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| Intel         | DH77EB AAG39073-304         | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [4cfac9a162](https://linux-hardware.org/?probe=4cfac9a162) | Mar 30, 2023 |
| ASUSTek       | PRIME Z690-P                | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASUSTek       | PRIME H510M-D               | [c0e9304de5](https://linux-hardware.org/?probe=c0e9304de5) | Mar 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [7415192b86](https://linux-hardware.org/?probe=7415192b86) | Feb 20, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [e958da375f](https://linux-hardware.org/?probe=e958da375f) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [e47bb0ee84](https://linux-hardware.org/?probe=e47bb0ee84) | Feb 19, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| Gigabyte      | G1.Sniper 3                 | [f7f587188e](https://linux-hardware.org/?probe=f7f587188e) | Feb 03, 2023 |
| Gigabyte      | G31M-ES2L                   | [79a45b9ea0](https://linux-hardware.org/?probe=79a45b9ea0) | Jan 19, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [b6a8598370](https://linux-hardware.org/?probe=b6a8598370) | Jan 19, 2023 |
| Unknown       | Unknown                     | [78a20b41ee](https://linux-hardware.org/?probe=78a20b41ee) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9767004b24](https://linux-hardware.org/?probe=9767004b24) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [87c4201895](https://linux-hardware.org/?probe=87c4201895) | Jan 07, 2023 |
| ASUSTek       | PRIME Z390-P                | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Gigabyte      | B150M-D3H-CF                | [504222de34](https://linux-hardware.org/?probe=504222de34) | Nov 20, 2022 |
| Gigabyte      | B150M-D3H-CF                | [f685fd9050](https://linux-hardware.org/?probe=f685fd9050) | Nov 20, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [c22dce3d23](https://linux-hardware.org/?probe=c22dce3d23) | Nov 16, 2022 |
| HP            | 88BE                        | [1c03e5957d](https://linux-hardware.org/?probe=1c03e5957d) | Nov 13, 2022 |
| Gigabyte      | H110M-S2H-CF                | [da03d56b4e](https://linux-hardware.org/?probe=da03d56b4e) | Nov 07, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [4099d3c69b](https://linux-hardware.org/?probe=4099d3c69b) | Nov 05, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c35a514fe5](https://linux-hardware.org/?probe=c35a514fe5) | Nov 05, 2022 |
| Gigabyte      | Z170X-Gaming 7              | [be2ceae6ca](https://linux-hardware.org/?probe=be2ceae6ca) | Nov 05, 2022 |
| Gigabyte      | H97-HD3                     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Gigabyte      | H77-DS3H                    | [4457c6182e](https://linux-hardware.org/?probe=4457c6182e) | Oct 29, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| Gigabyte      | X79-UP4                     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | PRIME H270-PRO              | [b98f2dc115](https://linux-hardware.org/?probe=b98f2dc115) | Oct 08, 2022 |
| Dell          | 014GRG A01                  | [05a023826f](https://linux-hardware.org/?probe=05a023826f) | Oct 06, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| Dell          | 06D7TR A02                  | [a0d832ff6a](https://linux-hardware.org/?probe=a0d832ff6a) | Sep 28, 2022 |
| ASUSTek       | Rampage II Extreme          | [c996a3c4dd](https://linux-hardware.org/?probe=c996a3c4dd) | Sep 19, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [4d7948b375](https://linux-hardware.org/?probe=4d7948b375) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [1e4d0a6189](https://linux-hardware.org/?probe=1e4d0a6189) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | 0CRH6C A01                  | [d4a37f016b](https://linux-hardware.org/?probe=d4a37f016b) | Sep 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| HP            | 18E7                        | [f1c1f9c891](https://linux-hardware.org/?probe=f1c1f9c891) | Aug 12, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [06d2014c22](https://linux-hardware.org/?probe=06d2014c22) | Aug 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| ASUSTek       | P7H55-M PRO                 | [5708a69dc1](https://linux-hardware.org/?probe=5708a69dc1) | Jun 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [150ea72986](https://linux-hardware.org/?probe=150ea72986) | Jun 23, 2022 |
| MSI           | Z170A KRAIT GAMING          | [7f2adf56e4](https://linux-hardware.org/?probe=7f2adf56e4) | Jun 21, 2022 |
| Foxconn       | H81MXV FAB A                | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Lenovo        | ThinkCentre M81 5049W15     | [df4917e32f](https://linux-hardware.org/?probe=df4917e32f) | May 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [7ba08ba4b5](https://linux-hardware.org/?probe=7ba08ba4b5) | May 21, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [81aa40219e](https://linux-hardware.org/?probe=81aa40219e) | May 21, 2022 |
| HP            | 8298                        | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Gigabyte      | Z170X-Gaming 7              | [813349f89b](https://linux-hardware.org/?probe=813349f89b) | May 17, 2022 |
| Intel         | DH77EB AAG39073-304         | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| ASUSTek       | D540MA-C                    | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Lenovo        | NO DPK                      | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| MSI           | H61M-E22                    | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| ASUSTek       | Z97-DELUXE                  | [8b2771b584](https://linux-hardware.org/?probe=8b2771b584) | Mar 07, 2022 |
| ASUSTek       | H97M-E                      | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [1398ef93be](https://linux-hardware.org/?probe=1398ef93be) | Feb 22, 2022 |
| Dell          | 0WN7Y6 A01                  | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| ASRock        | B450 Pro4                   | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [9295ca6d10](https://linux-hardware.org/?probe=9295ca6d10) | Feb 13, 2022 |
| Gigabyte      | H55M-D2H                    | [f85ece5bf7](https://linux-hardware.org/?probe=f85ece5bf7) | Feb 12, 2022 |
| Gigabyte      | B460M DS3H                  | [136ea58ce8](https://linux-hardware.org/?probe=136ea58ce8) | Feb 11, 2022 |
| Shuttle       | FH87                        | [1588ed0352](https://linux-hardware.org/?probe=1588ed0352) | Feb 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518NR8    | [cc2ea0bba2](https://linux-hardware.org/?probe=cc2ea0bba2) | Feb 08, 2022 |
| HP            | 2B34                        | [a44a14f358](https://linux-hardware.org/?probe=a44a14f358) | Feb 08, 2022 |
| Alienware     | 07W25T A00                  | [0bd0a24a20](https://linux-hardware.org/?probe=0bd0a24a20) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | [852eb2b367](https://linux-hardware.org/?probe=852eb2b367) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M91p 4524B96    | [5a90acd016](https://linux-hardware.org/?probe=5a90acd016) | Jan 31, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| Gigabyte      | B460 HD3                    | [48e8e52d84](https://linux-hardware.org/?probe=48e8e52d84) | Jan 13, 2022 |
| ASUSTek       | PRIME B560M-K               | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Supermicro    | X9DAi                       | [0f78e87ab1](https://linux-hardware.org/?probe=0f78e87ab1) | Jan 03, 2022 |
| Supermicro    | X9DAi                       | [a86bdc7f4d](https://linux-hardware.org/?probe=a86bdc7f4d) | Jan 03, 2022 |
| Gigabyte      | B75M-D3V                    | [0f43701ca4](https://linux-hardware.org/?probe=0f43701ca4) | Dec 20, 2021 |
| Gigabyte      | P55-UD3L                    | [6d2be9add8](https://linux-hardware.org/?probe=6d2be9add8) | Dec 17, 2021 |
| AZW           | U59                         | [021639604a](https://linux-hardware.org/?probe=021639604a) | Dec 15, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| ASUSTek       | PRIME B560M-K               | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| Gigabyte      | H87-D3H-CF                  | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Gigabyte      | B460 HD3                    | [19bfb20536](https://linux-hardware.org/?probe=19bfb20536) | Nov 19, 2021 |
| ASRock        | H370M Pro4                  | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| Gigabyte      | B560M H                     | [358ab5a9fe](https://linux-hardware.org/?probe=358ab5a9fe) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| Gigabyte      | B560M DS3H                  | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek       | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
| Dell          | 0XHGV1 A00                  | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| Dell          | 0V8F20 A01                  | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| MSI           | G41TM-P33                   | [8216f8bfae](https://linux-hardware.org/?probe=8216f8bfae) | Oct 24, 2021 |
| Foxconn       | H81MXV FAB A                | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| ASUSTek       | Z170-K                      | [b39ed56cc9](https://linux-hardware.org/?probe=b39ed56cc9) | Oct 19, 2021 |
| Gigabyte      | G31M-ES2L                   | [aa3b1b645e](https://linux-hardware.org/?probe=aa3b1b645e) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | [e3149252a0](https://linux-hardware.org/?probe=e3149252a0) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | [b78fec94ab](https://linux-hardware.org/?probe=b78fec94ab) | Oct 16, 2021 |
| Dell          | 0XHGV1 A00                  | [853a82796c](https://linux-hardware.org/?probe=853a82796c) | Oct 15, 2021 |
| ASUSTek       | PRIME Z390-A                | [f86adc0f8d](https://linux-hardware.org/?probe=f86adc0f8d) | Oct 12, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| HP            | 1497                        | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| ASUSTek       | H81M-E R2.0                 | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| ITI LIMITE... | SMAASH XU3i                 | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| ASUSTek       | Z170-K                      | [e5e1953ed8](https://linux-hardware.org/?probe=e5e1953ed8) | Sep 05, 2021 |
| HP            | 158A                        | [6c22e51bfc](https://linux-hardware.org/?probe=6c22e51bfc) | Sep 04, 2021 |
| Dell          | 06X1TJ A00                  | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| ASUSTek       | PRIME Z370-P II             | [68213450a7](https://linux-hardware.org/?probe=68213450a7) | Aug 14, 2021 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| Gigabyte      | X58-USB3                    | [8a48f8d2bc](https://linux-hardware.org/?probe=8a48f8d2bc) | Jul 31, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| ASUSTek       | P8P67 DELUXE                | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| Dell          | 06X1TJ A00                  | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell          | 06X1TJ A00                  | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| Dell          | 06X1TJ A00                  | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell          | 0GMM0G A00                  | [2c9050ccd9](https://linux-hardware.org/?probe=2c9050ccd9) | Jul 03, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| Pegatron      | 2A94h                       | [5475faba11](https://linux-hardware.org/?probe=5475faba11) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| Gigabyte      | B360M HD3                   | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| ASUSTek       | PRIME Z490-P                | [59cf3396c0](https://linux-hardware.org/?probe=59cf3396c0) | Jun 13, 2021 |
| ASRock        | H370M Pro4                  | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| ASUSTek       | PRIME X470-PRO              | [aea7394e24](https://linux-hardware.org/?probe=aea7394e24) | Jun 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Intel         | DP55WB AAE64798-205         | [a760607f4e](https://linux-hardware.org/?probe=a760607f4e) | May 27, 2021 |
| Gigabyte      | B450 AORUS M                | [a7a67287a3](https://linux-hardware.org/?probe=a7a67287a3) | May 26, 2021 |
| Intel         | DP55WB AAE64798-205         | [7070bcfa9a](https://linux-hardware.org/?probe=7070bcfa9a) | May 24, 2021 |
| Gigabyte      | H61M-S1                     | [2f7da43eb2](https://linux-hardware.org/?probe=2f7da43eb2) | May 23, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
| Gigabyte      | H81M-S2PV                   | [c8a2e1e897](https://linux-hardware.org/?probe=c8a2e1e897) | May 06, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [e0e3552e96](https://linux-hardware.org/?probe=e0e3552e96) | Apr 28, 2021 |
| ASRock        | H370M Pro4                  | [be75ff3da4](https://linux-hardware.org/?probe=be75ff3da4) | Apr 25, 2021 |
| HP            | 3397                        | [08ea9bb12b](https://linux-hardware.org/?probe=08ea9bb12b) | Apr 22, 2021 |
| Gigabyte      | G41MT-S2                    | [0752e29519](https://linux-hardware.org/?probe=0752e29519) | Apr 21, 2021 |
| Gigabyte      | G41MT-S2                    | [6dd3daccc6](https://linux-hardware.org/?probe=6dd3daccc6) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| ASUSTek       | PRIME B365M-A               | [c5109bab9c](https://linux-hardware.org/?probe=c5109bab9c) | Apr 17, 2021 |
| ASUSTek       | PRIME B250M-A               | [95f2d11b2e](https://linux-hardware.org/?probe=95f2d11b2e) | Apr 16, 2021 |
| ASUSTek       | D540MA-C                    | [945b05bee8](https://linux-hardware.org/?probe=945b05bee8) | Apr 16, 2021 |
| ASRock        | H370M Pro4                  | [e6b5c6b72b](https://linux-hardware.org/?probe=e6b5c6b72b) | Apr 11, 2021 |
| ASUSTek       | H97M-E                      | [9881ce611d](https://linux-hardware.org/?probe=9881ce611d) | Apr 09, 2021 |
| ASUSTek       | M5A97 R2.0                  | [a5823c243c](https://linux-hardware.org/?probe=a5823c243c) | Apr 02, 2021 |
| MSI           | H87-G43 GAMING              | [5bd49fbcea](https://linux-hardware.org/?probe=5bd49fbcea) | Mar 28, 2021 |
| Gigabyte      | G31M-S2C                    | [8d84b967f2](https://linux-hardware.org/?probe=8d84b967f2) | Mar 25, 2021 |
| Gigabyte      | G31M-S2C                    | [91a8d56cfd](https://linux-hardware.org/?probe=91a8d56cfd) | Mar 25, 2021 |
| Gigabyte      | G41M-Combo                  | [feb8706c98](https://linux-hardware.org/?probe=feb8706c98) | Mar 18, 2021 |
| ASRock        | H71M-DGS                    | [30424c4317](https://linux-hardware.org/?probe=30424c4317) | Mar 18, 2021 |
| MSI           | H170A GAMING PRO            | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Gigabyte      | Z490M                       | [6eecc1d3cc](https://linux-hardware.org/?probe=6eecc1d3cc) | Mar 15, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | [0fbdab8514](https://linux-hardware.org/?probe=0fbdab8514) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | [7140c5ee85](https://linux-hardware.org/?probe=7140c5ee85) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | [93a598b2c2](https://linux-hardware.org/?probe=93a598b2c2) | Mar 11, 2021 |
| Intel         | DG43RK AAE78175-403         | [942660dca5](https://linux-hardware.org/?probe=942660dca5) | Mar 11, 2021 |
| Gigabyte      | G41M-Combo                  | [2d19cc5e17](https://linux-hardware.org/?probe=2d19cc5e17) | Mar 11, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | [99082a91ac](https://linux-hardware.org/?probe=99082a91ac) | Mar 11, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [1e4054e9fe](https://linux-hardware.org/?probe=1e4054e9fe) | Mar 09, 2021 |
| Gigabyte      | H81-D3                      | [d05b1b3efc](https://linux-hardware.org/?probe=d05b1b3efc) | Feb 22, 2021 |
| ASRock        | H77M                        | [eb7af012c2](https://linux-hardware.org/?probe=eb7af012c2) | Feb 19, 2021 |
| Gigabyte      | G31M-S2C                    | [c2bd3800b7](https://linux-hardware.org/?probe=c2bd3800b7) | Feb 18, 2021 |
| ASUSTek       | PRIME Z370-P II             | [95fc52db78](https://linux-hardware.org/?probe=95fc52db78) | Feb 17, 2021 |
| Dell          | 0M9KCM A02                  | [802f6994df](https://linux-hardware.org/?probe=802f6994df) | Feb 16, 2021 |
| ASUSTek       | P7H55-M PRO                 | [aead87bf38](https://linux-hardware.org/?probe=aead87bf38) | Feb 14, 2021 |
| Lenovo        | 3176 NOK                    | [c5216ce396](https://linux-hardware.org/?probe=c5216ce396) | Feb 14, 2021 |
| MSI           | B150M BAZOOKA               | [66af036f49](https://linux-hardware.org/?probe=66af036f49) | Feb 13, 2021 |
| MSI           | B150M BAZOOKA               | [749beaf127](https://linux-hardware.org/?probe=749beaf127) | Feb 13, 2021 |
| Gigabyte      | B460M D3H                   | [8cdafac5a3](https://linux-hardware.org/?probe=8cdafac5a3) | Feb 13, 2021 |
| ASUSTek       | H110M-A/M.2                 | [351477b72b](https://linux-hardware.org/?probe=351477b72b) | Feb 13, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [3e8ad6be09](https://linux-hardware.org/?probe=3e8ad6be09) | Feb 10, 2021 |
| ASRock        | Z490M-ITX/ac                | [586d4a5a82](https://linux-hardware.org/?probe=586d4a5a82) | Feb 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [017e9abf15](https://linux-hardware.org/?probe=017e9abf15) | Feb 04, 2021 |
| ASUSTek       | H81M-K                      | [e6be0abafb](https://linux-hardware.org/?probe=e6be0abafb) | Jan 28, 2021 |
| Gigabyte      | H97M-D3H                    | [cc4593764d](https://linux-hardware.org/?probe=cc4593764d) | Jan 18, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [725729e04e](https://linux-hardware.org/?probe=725729e04e) | Jan 13, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [9c40fd9781](https://linux-hardware.org/?probe=9c40fd9781) | Jan 13, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [4723903be4](https://linux-hardware.org/?probe=4723903be4) | Jan 11, 2021 |
| Gigabyte      | P55-UD3L                    | [8c6a5c5e60](https://linux-hardware.org/?probe=8c6a5c5e60) | Jan 10, 2021 |
| ASRock        | H97M Anniversary            | [b630702ecc](https://linux-hardware.org/?probe=b630702ecc) | Jan 10, 2021 |
| Gigabyte      | G41M-ES2L                   | [2583ebac59](https://linux-hardware.org/?probe=2583ebac59) | Jan 08, 2021 |
| Gigabyte      | H81M-D2V                    | [b7c82c53b6](https://linux-hardware.org/?probe=b7c82c53b6) | Jan 07, 2021 |
| Unknown       | G41 Series                  | [578bc526ef](https://linux-hardware.org/?probe=578bc526ef) | Jan 06, 2021 |
| Unknown       | G41 Series                  | [5a6543b6f1](https://linux-hardware.org/?probe=5a6543b6f1) | Jan 03, 2021 |
| Gigabyte      | Z390 UD                     | [b4ebedb0e2](https://linux-hardware.org/?probe=b4ebedb0e2) | Dec 18, 2020 |
| ASUSTek       | H97M-E                      | [4f0b22ee7f](https://linux-hardware.org/?probe=4f0b22ee7f) | Nov 30, 2020 |
| MSI           | X470 GAMING PLUS            | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| Gigabyte      | Z270X-UD5-CF                | [f65b9a326b](https://linux-hardware.org/?probe=f65b9a326b) | Nov 21, 2020 |
| Gigabyte      | Z270X-UD5-CF                | [8f674b7608](https://linux-hardware.org/?probe=8f674b7608) | Nov 21, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [c42752eed3](https://linux-hardware.org/?probe=c42752eed3) | Nov 19, 2020 |
| ASUSTek       | P9X79 LE                    | [1674d3318e](https://linux-hardware.org/?probe=1674d3318e) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | [0ae9d90f3f](https://linux-hardware.org/?probe=0ae9d90f3f) | Nov 18, 2020 |
| Gigabyte      | H61M-S2PV                   | [accc9c10e5](https://linux-hardware.org/?probe=accc9c10e5) | Nov 16, 2020 |
| Gigabyte      | H61M-S2PV                   | [1c3bd52baa](https://linux-hardware.org/?probe=1c3bd52baa) | Nov 05, 2020 |
| Gigabyte      | H61M-S2PV                   | [1b6972fae9](https://linux-hardware.org/?probe=1b6972fae9) | Nov 05, 2020 |
| Dell          | 0CU409                      | [6adb83b2e0](https://linux-hardware.org/?probe=6adb83b2e0) | Nov 04, 2020 |
| Lenovo        | ThinkCentre A58 751581G     | [987ed81d7d](https://linux-hardware.org/?probe=987ed81d7d) | Nov 03, 2020 |
| Dell          | 0KWVT8 A02                  | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| Dell          | 0DR845                      | [c59e7b1e56](https://linux-hardware.org/?probe=c59e7b1e56) | Nov 01, 2020 |
| ASUSTek       | H110M-A                     | [f8fa4c9c31](https://linux-hardware.org/?probe=f8fa4c9c31) | Nov 01, 2020 |
| Dell          | 0KP561                      | [da357993dd](https://linux-hardware.org/?probe=da357993dd) | Oct 31, 2020 |
| Dell          | 0KP561                      | [b14be76868](https://linux-hardware.org/?probe=b14be76868) | Oct 31, 2020 |
| HP            | 158A                        | [f83412f912](https://linux-hardware.org/?probe=f83412f912) | Oct 27, 2020 |
| ASUSTek       | PRIME X470-PRO              | [5bd58e33be](https://linux-hardware.org/?probe=5bd58e33be) | Oct 27, 2020 |
| HP            | 82B4                        | [d98d676e9c](https://linux-hardware.org/?probe=d98d676e9c) | Oct 26, 2020 |
| ASUSTek       | PRIME B350M-A               | [7c9e9b741c](https://linux-hardware.org/?probe=7c9e9b741c) | Oct 25, 2020 |
| ASUSTek       | PRIME X570-PRO              | [d3f4deffa5](https://linux-hardware.org/?probe=d3f4deffa5) | Oct 25, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [6ba76947d7](https://linux-hardware.org/?probe=6ba76947d7) | Oct 18, 2020 |
| ASUSTek       | PRIME Z490-P                | [44d70b326c](https://linux-hardware.org/?probe=44d70b326c) | Oct 13, 2020 |
| Gigabyte      | B360M HD3                   | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | [986a5e604f](https://linux-hardware.org/?probe=986a5e604f) | Oct 03, 2020 |
| ASRock        | X399 Taichi                 | [268a9d5625](https://linux-hardware.org/?probe=268a9d5625) | Oct 01, 2020 |
| ASUSTek       | P5G41C-M LX                 | [353229fd96](https://linux-hardware.org/?probe=353229fd96) | Sep 29, 2020 |
| Unknown       | Unknown                     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| ASRock        | H97M Anniversary            | [cc0e0f5c04](https://linux-hardware.org/?probe=cc0e0f5c04) | Sep 29, 2020 |
| MSI           | G41M-E43                    | [5a567b1f97](https://linux-hardware.org/?probe=5a567b1f97) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | [5d73c67b98](https://linux-hardware.org/?probe=5d73c67b98) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | [9c9f5b4cfa](https://linux-hardware.org/?probe=9c9f5b4cfa) | Sep 10, 2020 |
| Gigabyte      | B360M HD3                   | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| HP            | 339A                        | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [42deb7cee5](https://linux-hardware.org/?probe=42deb7cee5) | Sep 03, 2020 |
| ASUSTek       | PRIME Z370-P                | [5bfd2a1403](https://linux-hardware.org/?probe=5bfd2a1403) | Sep 03, 2020 |
| MSI           | 2A9Ch                       | [aa629696b3](https://linux-hardware.org/?probe=aa629696b3) | Aug 28, 2020 |
| MSI           | 2A9Ch                       | [0ece5d52d2](https://linux-hardware.org/?probe=0ece5d52d2) | Aug 27, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [56afe1e282](https://linux-hardware.org/?probe=56afe1e282) | Aug 27, 2020 |
| ASRock        | H97M Anniversary            | [613aba4134](https://linux-hardware.org/?probe=613aba4134) | Aug 23, 2020 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a114ae9c9c](https://linux-hardware.org/?probe=a114ae9c9c) | Aug 12, 2020 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | [1828dedb7f](https://linux-hardware.org/?probe=1828dedb7f) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | [0d864b4feb](https://linux-hardware.org/?probe=0d864b4feb) | Aug 08, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | [69e782093d](https://linux-hardware.org/?probe=69e782093d) | Aug 08, 2020 |
| Gigabyte      | Z270-HD3P-CF                | [3fe0ec39fc](https://linux-hardware.org/?probe=3fe0ec39fc) | Aug 07, 2020 |
| ASRock        | H55M                        | [f2d0fa78ac](https://linux-hardware.org/?probe=f2d0fa78ac) | Aug 06, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5c3dc530c3](https://linux-hardware.org/?probe=5c3dc530c3) | Aug 04, 2020 |
| Gigabyte      | Z97-HD3                     | [2e41ce3f03](https://linux-hardware.org/?probe=2e41ce3f03) | Jul 31, 2020 |
| Gigabyte      | Z97-HD3                     | [50888e0851](https://linux-hardware.org/?probe=50888e0851) | Jul 31, 2020 |
| ASRock        | H55M                        | [dcbc0735f5](https://linux-hardware.org/?probe=dcbc0735f5) | Jul 30, 2020 |
| ASUSTek       | P8H67-M PRO                 | [a7e0318966](https://linux-hardware.org/?probe=a7e0318966) | Jul 30, 2020 |
| ASUSTek       | AT3N7A-I                    | [57c3ce82b7](https://linux-hardware.org/?probe=57c3ce82b7) | Jul 29, 2020 |
| Hardkernel    | ODROID-H2                   | [c86e7dc968](https://linux-hardware.org/?probe=c86e7dc968) | Jul 23, 2020 |
| Gigabyte      | H61M-S1                     | [2a63a11959](https://linux-hardware.org/?probe=2a63a11959) | Jul 08, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte      | G31M-S2C                    | [da847897f9](https://linux-hardware.org/?probe=da847897f9) | Jun 15, 2020 |
| MSI           | G41M-E43                    | [4c72170ef6](https://linux-hardware.org/?probe=4c72170ef6) | Jun 06, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [48f5173ede](https://linux-hardware.org/?probe=48f5173ede) | May 27, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [72b226183e](https://linux-hardware.org/?probe=72b226183e) | May 27, 2020 |
| ASUSTek       | F2A85-M PRO                 | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [bd5ec5436e](https://linux-hardware.org/?probe=bd5ec5436e) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [355e03bb68](https://linux-hardware.org/?probe=355e03bb68) | May 15, 2020 |
| HP            | 339A                        | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [c815568345](https://linux-hardware.org/?probe=c815568345) | May 14, 2020 |
| ASUSTek       | F2A85-M PRO                 | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [fc58b96f3e](https://linux-hardware.org/?probe=fc58b96f3e) | May 01, 2020 |
| Gigabyte      | B450M S2H                   | [0fe3c99d58](https://linux-hardware.org/?probe=0fe3c99d58) | Apr 30, 2020 |
| MSI           | G41TM-P33                   | [d1078cd496](https://linux-hardware.org/?probe=d1078cd496) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | [3512230c03](https://linux-hardware.org/?probe=3512230c03) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | [a648a57d33](https://linux-hardware.org/?probe=a648a57d33) | Apr 28, 2020 |
| Gigabyte      | Z270XP-SLI-CF               | [20f18f18b8](https://linux-hardware.org/?probe=20f18f18b8) | Apr 27, 2020 |
| Dell          | 097YXY A00                  | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| MSI           | G41TM-P33                   | [d99b7f2578](https://linux-hardware.org/?probe=d99b7f2578) | Apr 22, 2020 |
| Gigabyte      | H61M-S1                     | [ade023408c](https://linux-hardware.org/?probe=ade023408c) | Mar 26, 2020 |
| MSI           | B450-A PRO                  | [f9c1a4dd5d](https://linux-hardware.org/?probe=f9c1a4dd5d) | Mar 25, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [e02dd36f39](https://linux-hardware.org/?probe=e02dd36f39) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [5c3ecb2c5b](https://linux-hardware.org/?probe=5c3ecb2c5b) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [1004ffcce5](https://linux-hardware.org/?probe=1004ffcce5) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [e0f2c8f133](https://linux-hardware.org/?probe=e0f2c8f133) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [03d86fb8e8](https://linux-hardware.org/?probe=03d86fb8e8) | Mar 21, 2020 |
| ASUSTek       | PRIME B450M-A               | [a53152418d](https://linux-hardware.org/?probe=a53152418d) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | [32428dda92](https://linux-hardware.org/?probe=32428dda92) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | [5d56415e4c](https://linux-hardware.org/?probe=5d56415e4c) | Mar 14, 2020 |
| Gigabyte      | Q87M-D2H                    | [48afe5fac3](https://linux-hardware.org/?probe=48afe5fac3) | Mar 08, 2020 |
| ASUSTek       | H81M-K                      | [08d45d3162](https://linux-hardware.org/?probe=08d45d3162) | Mar 07, 2020 |
| HP            | 1495                        | [ff4447983a](https://linux-hardware.org/?probe=ff4447983a) | Feb 22, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [72475e5edb](https://linux-hardware.org/?probe=72475e5edb) | Feb 22, 2020 |
| HP            | 1495                        | [e1d927d5ce](https://linux-hardware.org/?probe=e1d927d5ce) | Feb 16, 2020 |
| HP            | 1495                        | [c9e7f762e4](https://linux-hardware.org/?probe=c9e7f762e4) | Feb 16, 2020 |
| Gigabyte      | H110M-DS2 DDR3-CF           | [e2a558c35b](https://linux-hardware.org/?probe=e2a558c35b) | Feb 11, 2020 |
| MSI           | G41TM-P33                   | [524089d286](https://linux-hardware.org/?probe=524089d286) | Jan 29, 2020 |
| Pegatron      | NARRA5                      | [f0bd8ead24](https://linux-hardware.org/?probe=f0bd8ead24) | Jan 17, 2020 |
| ASRock        | H97M Anniversary            | [221a2cfac8](https://linux-hardware.org/?probe=221a2cfac8) | Jan 13, 2020 |
| Dell          | 0GM819                      | [d99391a30c](https://linux-hardware.org/?probe=d99391a30c) | Jan 06, 2020 |
| ASUSTek       | M2N-MX SE Plus              | [f3b22a675a](https://linux-hardware.org/?probe=f3b22a675a) | Dec 20, 2019 |
| ASUSTek       | A88XM-A/USB                 | [8f93bf715a](https://linux-hardware.org/?probe=8f93bf715a) | Dec 11, 2019 |
| ASRock        | H97M Anniversary            | [831ff4b7fc](https://linux-hardware.org/?probe=831ff4b7fc) | Dec 10, 2019 |
| Gigabyte      | F2A88XM-D3H                 | [8fbc16ebfa](https://linux-hardware.org/?probe=8fbc16ebfa) | Dec 03, 2019 |
| Gigabyte      | H170-HD3-CF                 | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASRock        | G41C-GS                     | [920a88f615](https://linux-hardware.org/?probe=920a88f615) | Nov 08, 2019 |
| HP            | 2B38                        | [8a919fff76](https://linux-hardware.org/?probe=8a919fff76) | Oct 26, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [6d5ea39af4](https://linux-hardware.org/?probe=6d5ea39af4) | Oct 26, 2019 |
| Dell          | 0GM819                      | [4468e2e57e](https://linux-hardware.org/?probe=4468e2e57e) | Oct 21, 2019 |
| Gigabyte      | Z87MX-D3H-CF                | [8a9e5f7293](https://linux-hardware.org/?probe=8a9e5f7293) | Oct 14, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [cafdeb1b3a](https://linux-hardware.org/?probe=cafdeb1b3a) | Oct 06, 2019 |
| HP            | 2B38                        | [f690313ecf](https://linux-hardware.org/?probe=f690313ecf) | Sep 30, 2019 |
| ASUSTek       | PRIME X370-PRO              | [2ad6f6b23d](https://linux-hardware.org/?probe=2ad6f6b23d) | Sep 25, 2019 |
| AMI           | Cherry Trail CR             | [0398059e29](https://linux-hardware.org/?probe=0398059e29) | Sep 16, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [3bfc472643](https://linux-hardware.org/?probe=3bfc472643) | Sep 15, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d90225cad7](https://linux-hardware.org/?probe=d90225cad7) | Sep 15, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [c090add0c0](https://linux-hardware.org/?probe=c090add0c0) | Sep 04, 2019 |
| Dell          | 0GM819                      | [863ec2a484](https://linux-hardware.org/?probe=863ec2a484) | Sep 02, 2019 |
| Dell          | 0GM819                      | [7bf21b409d](https://linux-hardware.org/?probe=7bf21b409d) | Sep 02, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [f6c7aa7735](https://linux-hardware.org/?probe=f6c7aa7735) | Sep 02, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | [b1fb625f3d](https://linux-hardware.org/?probe=b1fb625f3d) | Aug 26, 2019 |
| Dell          | 0CKCXH A04                  | [2679a50fe1](https://linux-hardware.org/?probe=2679a50fe1) | Aug 24, 2019 |
| Gigabyte      | H55M-S2H                    | [2479a0b0c9](https://linux-hardware.org/?probe=2479a0b0c9) | Aug 24, 2019 |
| Gigabyte      | J1800N-D2H                  | [616bb81d97](https://linux-hardware.org/?probe=616bb81d97) | Aug 17, 2019 |
| Foxconn       | 2A8C                        | [54cbeed66e](https://linux-hardware.org/?probe=54cbeed66e) | Jul 10, 2019 |
| ASUSTek       | TUF X470-PLUS GAMING        | [10a2ff392a](https://linux-hardware.org/?probe=10a2ff392a) | Jul 09, 2019 |
| Gigabyte      | H57M-USB3                   | [10ba468b45](https://linux-hardware.org/?probe=10ba468b45) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | [0b6b3550b5](https://linux-hardware.org/?probe=0b6b3550b5) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | [a920b40c9f](https://linux-hardware.org/?probe=a920b40c9f) | Jul 01, 2019 |
| Dell          | 0GDG8Y A00                  | [4f0fb75146](https://linux-hardware.org/?probe=4f0fb75146) | Jun 20, 2019 |
| ASRock        | H110M-ITX/ac                | [6f2ecbf51c](https://linux-hardware.org/?probe=6f2ecbf51c) | Jun 04, 2019 |
| Gigabyte      | H97-HD3                     | [64e47e9922](https://linux-hardware.org/?probe=64e47e9922) | May 28, 2019 |
| Gigabyte      | X58A-UD3R                   | [112dc8e71a](https://linux-hardware.org/?probe=112dc8e71a) | May 23, 2019 |
| ASUSTek       | H110M-K                     | [c736db6599](https://linux-hardware.org/?probe=c736db6599) | May 01, 2019 |
| ASUSTek       | H110M-K                     | [109947ebc6](https://linux-hardware.org/?probe=109947ebc6) | May 01, 2019 |
| ASUSTek       | H110M-A/M.2                 | [05fcc6199e](https://linux-hardware.org/?probe=05fcc6199e) | Apr 21, 2019 |
| ASUSTek       | P7H55-M PRO                 | [f8a69693bc](https://linux-hardware.org/?probe=f8a69693bc) | Mar 30, 2019 |
| Biostar       | H61MLV2                     | [19146b787b](https://linux-hardware.org/?probe=19146b787b) | Mar 28, 2019 |
| Gigabyte      | H97M-HD3                    | [a6818d6761](https://linux-hardware.org/?probe=a6818d6761) | Mar 20, 2019 |
| Gigabyte      | F2A88XM-HD3                 | [b1e21a522f](https://linux-hardware.org/?probe=b1e21a522f) | Feb 26, 2019 |
| ASUSTek       | H81M-K                      | [569fd85150](https://linux-hardware.org/?probe=569fd85150) | Dec 05, 2018 |
| Gigabyte      | H370 HD3-CF                 | [ac7a7dc15b](https://linux-hardware.org/?probe=ac7a7dc15b) | Nov 13, 2018 |
| ASUSTek       | Z87-K                       | [1d8a707c72](https://linux-hardware.org/?probe=1d8a707c72) | Sep 11, 2018 |
| Gigabyte      | Z170MX-Gaming 5             | [935991dc2b](https://linux-hardware.org/?probe=935991dc2b) | May 04, 2018 |
| ASUSTek       | P7H55-M PRO                 | [d147cce967](https://linux-hardware.org/?probe=d147cce967) | Dec 06, 2017 |
| ASUSTek       | M5A87                       | [242554d0b3](https://linux-hardware.org/?probe=242554d0b3) | Apr 27, 2017 |
| ASRock        | G41C-GS                     | [ff9333f313](https://linux-hardware.org/?probe=ff9333f313) | Apr 13, 2017 |
| ASUSTek       | M5A87                       | [bbe4de9927](https://linux-hardware.org/?probe=bbe4de9927) | Apr 07, 2017 |
| Gigabyte      | Z170MX-Gaming 5             | [10108844b5](https://linux-hardware.org/?probe=10108844b5) | Mar 17, 2017 |
| ASUSTek       | M5A87                       | [653cce33bd](https://linux-hardware.org/?probe=653cce33bd) | Mar 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | [c869336270](https://linux-hardware.org/?probe=c869336270) | Jan 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | [c7554e6e05](https://linux-hardware.org/?probe=c7554e6e05) | Jan 14, 2017 |
| MSI           | G41TM-P33                   | [dd04fa411c](https://linux-hardware.org/?probe=dd04fa411c) | Dec 12, 2016 |
| ASUSTek       | P7H55-M PRO                 | [0a729a3728](https://linux-hardware.org/?probe=0a729a3728) | Oct 07, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Israel/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 54       | 13.95%  |
| Ubuntu 18.04                 | 26       | 6.72%   |
| Arch Rolling                 | 16       | 4.13%   |
| Ubuntu 22.04                 | 15       | 3.88%   |
| OpenMandriva 4.2             | 14       | 3.62%   |
| OpenMandriva 4.3             | 11       | 2.84%   |
| ROSA R11                     | 9        | 2.33%   |
| Ubuntu 19.04                 | 8        | 2.07%   |
| Manjaro                      | 7        | 1.81%   |
| Ubuntu 24.04                 | 6        | 1.55%   |
| Ubuntu 23.10                 | 6        | 1.55%   |
| ROSA R11.1                   | 6        | 1.55%   |
| OpenMandriva 5.0             | 6        | 1.55%   |
| OpenMandriva 23.08           | 6        | 1.55%   |
| Ubuntu 20.10                 | 5        | 1.29%   |
| Linux Mint 20.3              | 5        | 1.29%   |
| Debian 11                    | 5        | 1.29%   |
| Ubuntu 23.04                 | 4        | 1.03%   |
| Pop!_OS 22.04                | 4        | 1.03%   |
| Pop!_OS 20.04                | 4        | 1.03%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.03%   |
| OpenMandriva 23.01           | 4        | 1.03%   |
| Linux Mint 19.3              | 4        | 1.03%   |
| Kubuntu 20.04                | 4        | 1.03%   |
| Fedora 40                    | 4        | 1.03%   |
| Fedora 37                    | 4        | 1.03%   |
| Fedora 36                    | 4        | 1.03%   |
| ArcoLinux Rolling            | 4        | 1.03%   |
| Ubuntu 19.10                 | 3        | 0.78%   |
| Ubuntu 16.04                 | 3        | 0.78%   |
| SteamOS 4                    | 3        | 0.78%   |
| ROSA R8.1                    | 3        | 0.78%   |
| ROSA R8                      | 3        | 0.78%   |
| ROSA R10                     | 3        | 0.78%   |
| Pop!_OS 21.10                | 3        | 0.78%   |
| OpenMandriva 23.03           | 3        | 0.78%   |
| Linux Mint 21.1              | 3        | 0.78%   |
| Linux Mint 20.2              | 3        | 0.78%   |
| Linux Mint 20.1              | 3        | 0.78%   |
| KDE neon 20.04               | 3        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 129      | 36.44%  |
| OpenMandriva  | 45       | 12.71%  |
| ROSA          | 22       | 6.21%   |
| Linux Mint    | 21       | 5.93%   |
| Fedora        | 19       | 5.37%   |
| Arch          | 18       | 5.08%   |
| Manjaro       | 14       | 3.95%   |
| Pop!_OS       | 13       | 3.67%   |
| Debian        | 12       | 3.39%   |
| Kubuntu       | 7        | 1.98%   |
| Xubuntu       | 6        | 1.69%   |
| openSUSE      | 4        | 1.13%   |
| ArcoLinux     | 4        | 1.13%   |
| Zorin         | 3        | 0.85%   |
| Ubuntu Unity  | 3        | 0.85%   |
| SteamOS       | 3        | 0.85%   |
| Rocky Linux   | 3        | 0.85%   |
| Nobara        | 3        | 0.85%   |
| KDE neon      | 3        | 0.85%   |
| Gentoo        | 3        | 0.85%   |
| Elementary    | 3        | 0.85%   |
| Ubuntu Studio | 2        | 0.56%   |
| Ubuntu MATE   | 2        | 0.56%   |
| CentOS        | 2        | 0.56%   |
| Ubuntu Budgie | 1        | 0.28%   |
| Pikaos        | 1        | 0.28%   |
| Kali          | 1        | 0.28%   |
| Garuda Linux  | 1        | 0.28%   |
| Endless       | 1        | 0.28%   |
| EndeavourOS   | 1        | 0.28%   |
| Dts-distro    | 1        | 0.28%   |
| Devuan        | 1        | 0.28%   |
| Clear Linux   | 1        | 0.28%   |
| BlackPanther  | 1        | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 14       | 3.29%   |
| 5.4.0-42-generic                    | 13       | 3.06%   |
| 5.16.7-desktop-1omv4003             | 11       | 2.59%   |
| 6.6.2-desktop-1omv2390              | 7        | 1.65%   |
| 6.4.11-desktop-1omv2390             | 6        | 1.41%   |
| 5.4.0-48-generic                    | 6        | 1.41%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6        | 1.41%   |
| 6.5.0-14-generic                    | 5        | 1.18%   |
| 5.11.0-37-generic                   | 5        | 1.18%   |
| 6.8.0-45-generic                    | 4        | 0.94%   |
| 6.1.1-desktop-1omv2290              | 4        | 0.94%   |
| 5.4.0-52-generic                    | 4        | 0.94%   |
| 6.6.7-arch1-1                       | 3        | 0.71%   |
| 6.2.6-desktop-1omv2390              | 3        | 0.71%   |
| 6.2.0-20-generic                    | 3        | 0.71%   |
| 5.8.0-55-generic                    | 3        | 0.71%   |
| 5.8.0-48-generic                    | 3        | 0.71%   |
| 5.4.0-72-generic                    | 3        | 0.71%   |
| 5.4.0-65-generic                    | 3        | 0.71%   |
| 5.15.0-47-generic                   | 3        | 0.71%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 3        | 0.71%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 3        | 0.71%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 3        | 0.71%   |
| 4.15.0-58-generic                   | 3        | 0.71%   |
| 4.15.0-50-generic                   | 3        | 0.71%   |
| 6.9.3-76060903-generic              | 2        | 0.47%   |
| 6.8.8-zen1-1-zen                    | 2        | 0.47%   |
| 6.8.11-300.fc40.x86_64              | 2        | 0.47%   |
| 6.8.0-35-generic                    | 2        | 0.47%   |
| 6.2.0-39-generic                    | 2        | 0.47%   |
| 6.2.0-33-generic                    | 2        | 0.47%   |
| 6.2.0-32-generic                    | 2        | 0.47%   |
| 6.12.1-desktop-1omv2490             | 2        | 0.47%   |
| 5.8.0-43-generic                    | 2        | 0.47%   |
| 5.8.0-34-generic                    | 2        | 0.47%   |
| 5.8.0-25-generic                    | 2        | 0.47%   |
| 5.4.0-45-generic                    | 2        | 0.47%   |
| 5.4.0-37-generic                    | 2        | 0.47%   |
| 5.4.0-26-generic                    | 2        | 0.47%   |
| 5.4.0-131-generic                   | 2        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 55       | 13.85%  |
| 4.15.0  | 26       | 6.55%   |
| 5.8.0   | 20       | 5.04%   |
| 5.15.0  | 18       | 4.53%   |
| 5.11.0  | 14       | 3.53%   |
| 5.10.14 | 14       | 3.53%   |
| 5.0.0   | 13       | 3.27%   |
| 6.5.0   | 12       | 3.02%   |
| 6.2.0   | 12       | 3.02%   |
| 5.13.0  | 12       | 3.02%   |
| 5.16.7  | 11       | 2.77%   |
| 5.3.0   | 10       | 2.52%   |
| 6.8.0   | 9        | 2.27%   |
| 6.6.2   | 7        | 1.76%   |
| 6.4.11  | 6        | 1.51%   |
| 5.19.0  | 5        | 1.26%   |
| 5.10.0  | 5        | 1.26%   |
| 4.18.0  | 5        | 1.26%   |
| 6.2.6   | 4        | 1.01%   |
| 6.1.1   | 4        | 1.01%   |
| 6.8.8   | 3        | 0.76%   |
| 6.6.7   | 3        | 0.76%   |
| 4.9.60  | 3        | 0.76%   |
| 6.9.3   | 2        | 0.5%    |
| 6.8.7   | 2        | 0.5%    |
| 6.8.11  | 2        | 0.5%    |
| 6.3.5   | 2        | 0.5%    |
| 6.12.1  | 2        | 0.5%    |
| 6.11.0  | 2        | 0.5%    |
| 6.10.3  | 2        | 0.5%    |
| 6.10.2  | 2        | 0.5%    |
| 6.1.12  | 2        | 0.5%    |
| 5.9.16  | 2        | 0.5%    |
| 5.19.5  | 2        | 0.5%    |
| 5.16.19 | 2        | 0.5%    |
| 5.15.72 | 2        | 0.5%    |
| 5.14.10 | 2        | 0.5%    |
| 5.12.0  | 2        | 0.5%    |
| 5.10.74 | 2        | 0.5%    |
| 4.19.0  | 2        | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 57       | 14.58%  |
| 5.15    | 28       | 7.16%   |
| 5.10    | 26       | 6.65%   |
| 4.15    | 26       | 6.65%   |
| 5.8     | 22       | 5.63%   |
| 6.2     | 20       | 5.12%   |
| 6.8     | 15       | 3.84%   |
| 6.6     | 15       | 3.84%   |
| 6.5     | 15       | 3.84%   |
| 5.11    | 15       | 3.84%   |
| 5.16    | 14       | 3.58%   |
| 5.13    | 13       | 3.32%   |
| 5.0     | 13       | 3.32%   |
| 6.1     | 12       | 3.07%   |
| 5.3     | 10       | 2.56%   |
| 5.19    | 8        | 2.05%   |
| 6.4     | 7        | 1.79%   |
| 6.10    | 7        | 1.79%   |
| 5.9     | 6        | 1.53%   |
| 4.9     | 6        | 1.53%   |
| 4.18    | 6        | 1.53%   |
| 6.0     | 5        | 1.28%   |
| 5.17    | 5        | 1.28%   |
| 4.19    | 5        | 1.28%   |
| 6.9     | 4        | 1.02%   |
| 6.7     | 4        | 1.02%   |
| 5.14    | 4        | 1.02%   |
| 5.12    | 4        | 1.02%   |
| 4.1     | 4        | 1.02%   |
| 6.3     | 3        | 0.77%   |
| 6.11    | 3        | 0.77%   |
| 6.12    | 2        | 0.51%   |
| 3.10    | 2        | 0.51%   |
| 5.7     | 1        | 0.26%   |
| 5.6     | 1        | 0.26%   |
| 5.5     | 1        | 0.26%   |
| 4.7     | 1        | 0.26%   |
| 4.4     | 1        | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 336      | 99.12%  |
| i686   | 3        | 0.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| GNOME          | 140      | 38.46%  |
| KDE5           | 90       | 24.73%  |
| Unknown        | 45       | 12.36%  |
| X-Cinnamon     | 21       | 5.77%   |
| KDE4           | 18       | 4.95%   |
| xfce           | 14       | 3.85%   |
| KDE            | 7        | 1.92%   |
| MATE           | 6        | 1.65%   |
| KDE6           | 5        | 1.37%   |
| Unity          | 4        | 1.1%    |
| Pantheon       | 3        | 0.82%   |
| i3             | 3        | 0.82%   |
| Cinnamon       | 3        | 0.82%   |
| LXQt           | 1        | 0.27%   |
| i3-with-shmlog | 1        | 0.27%   |
| GNOME Classic  | 1        | 0.27%   |
| dwm            | 1        | 0.27%   |
| Budgie         | 1        | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 261      | 73.31%  |
| Wayland | 62       | 17.42%  |
| Unknown | 25       | 7.02%   |
| Tty     | 8        | 2.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 149      | 41.97%  |
| SDDM    | 78       | 21.97%  |
| GDM3    | 47       | 13.24%  |
| GDM     | 32       | 9.01%   |
| LightDM | 24       | 6.76%   |
| KDM     | 17       | 4.79%   |
| TDM     | 7        | 1.97%   |
| XDM     | 1        | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 125      | 35.61%  |
| en_IL      | 113      | 32.19%  |
| Unknown    | 44       | 12.54%  |
| ru_RU      | 22       | 6.27%   |
| he_IL      | 18       | 5.13%   |
| C          | 11       | 3.13%   |
| uk_UA      | 2        | 0.57%   |
| fr_FR      | 2        | 0.57%   |
| en_AG      | 2        | 0.57%   |
| pt_BR      | 1        | 0.28%   |
| POSIX      | 1        | 0.28%   |
| is         | 1        | 0.28%   |
| es_ES      | 1        | 0.28%   |
| en_US.UTF8 | 1        | 0.28%   |
| en_IN      | 1        | 0.28%   |
| en_GB      | 1        | 0.28%   |
| en_DK      | 1        | 0.28%   |
| de_DE      | 1        | 0.28%   |
| C.UTF8     | 1        | 0.28%   |
| ar_EG      | 1        | 0.28%   |
| aa_DJ      | 1        | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 204      | 58.29%  |
| EFI  | 146      | 41.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 236      | 67.05%  |
| Overlay | 37       | 10.51%  |
| Btrfs   | 35       | 9.94%   |
| Tmpfs   | 22       | 6.25%   |
| Unknown | 10       | 2.84%   |
| Xfs     | 8        | 2.27%   |
| Zfs     | 3        | 0.85%   |
| F2fs    | 1        | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 152      | 44.06%  |
| GPT     | 141      | 40.87%  |
| MBR     | 52       | 15.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 276      | 78.86%  |
| Yes       | 74       | 21.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 230      | 65.53%  |
| Yes       | 121      | 34.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 113      | 33.43%  |
| Gigabyte Technology                  | 107      | 31.66%  |
| Dell                                 | 26       | 7.69%   |
| MSI                                  | 20       | 5.92%   |
| Lenovo                               | 18       | 5.33%   |
| Hewlett-Packard                      | 16       | 4.73%   |
| ASRock                               | 10       | 2.96%   |
| Intel                                | 6        | 1.78%   |
| Unknown                              | 4        | 1.18%   |
| Pegatron                             | 2        | 0.59%   |
| Huanan                               | 2        | 0.59%   |
| Foxconn                              | 2        | 0.59%   |
| Supermicro                           | 1        | 0.3%    |
| Shuttle                              | 1        | 0.3%    |
| Shenzhen Meigao Electronic Equipment | 1        | 0.3%    |
| PC Engines                           | 1        | 0.3%    |
| JINGSHA                              | 1        | 0.3%    |
| ITI LIMITED                          | 1        | 0.3%    |
| Hardkernel                           | 1        | 0.3%    |
| Biostar                              | 1        | 0.3%    |
| AZW                                  | 1        | 0.3%    |
| AMI                                  | 1        | 0.3%    |
| Alienware                            | 1        | 0.3%    |
| Acer                                 | 1        | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 11       | 3.25%   |
| Gigabyte H61M-S2PV                                | 5        | 1.48%   |
| Gigabyte G31M-ES2L                                | 4        | 1.18%   |
| Unknown                                           | 4        | 1.18%   |
| MSI MS-7592                                       | 3        | 0.89%   |
| Gigabyte H61M-S1                                  | 3        | 0.89%   |
| ASUS PRIME Z490-P                                 | 3        | 0.89%   |
| ASUS P8H61-M LX R2.0                              | 3        | 0.89%   |
| ASUS H110M-K                                      | 3        | 0.89%   |
| ASUS H110M-A/M.2                                  | 3        | 0.89%   |
| MSI MS-7982                                       | 2        | 0.59%   |
| Intel DH77EB AAG39073-304                         | 2        | 0.59%   |
| HP Compaq 6200 Pro MT PC                          | 2        | 0.59%   |
| Gigabyte Z390 GAMING X                            | 2        | 0.59%   |
| Gigabyte X570 AORUS ULTRA                         | 2        | 0.59%   |
| Gigabyte P55-UD3L                                 | 2        | 0.59%   |
| Gigabyte H97M-D3H                                 | 2        | 0.59%   |
| Gigabyte H97-HD3                                  | 2        | 0.59%   |
| Gigabyte H55M-D2H                                 | 2        | 0.59%   |
| Gigabyte B460HD3                                  | 2        | 0.59%   |
| Gigabyte B450M DS3H                               | 2        | 0.59%   |
| Dell OptiPlex 9020                                | 2        | 0.59%   |
| Dell OptiPlex 755                                 | 2        | 0.59%   |
| Dell OptiPlex 7050                                | 2        | 0.59%   |
| ASUS TUF Gaming B650M-E WIFI                      | 2        | 0.59%   |
| ASUS TUF Gaming B550M-PLUS                        | 2        | 0.59%   |
| ASUS TUF Gaming B550-PLUS                         | 2        | 0.59%   |
| ASUS ROG STRIX Z390-E GAMING                      | 2        | 0.59%   |
| ASUS ROG STRIX Z370-F GAMING                      | 2        | 0.59%   |
| ASUS ROG STRIX X570-F GAMING                      | 2        | 0.59%   |
| ASUS PRIME Z390-P                                 | 2        | 0.59%   |
| ASUS PRIME X470-PRO                               | 2        | 0.59%   |
| ASUS PRIME H610M-K D4                             | 2        | 0.59%   |
| ASUS PRIME H310M-E R2.0                           | 2        | 0.59%   |
| ASUS PRIME B560M-K                                | 2        | 0.59%   |
| ASUS PRIME B365M-A                                | 2        | 0.59%   |
| ASUS PRIME B365-PLUS                              | 2        | 0.59%   |
| Supermicro X9DAi                                  | 1        | 0.3%    |
| Shuttle SH87R                                     | 1        | 0.3%    |
| Shenzhen Meigao Electronic Equipment Venus Series | 1        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 43       | 12.72%  |
| ASUS ROG                                   | 15       | 4.44%   |
| Dell OptiPlex                              | 14       | 4.14%   |
| ASUS TUF                                   | 11       | 3.25%   |
| ASUS All                                   | 11       | 3.25%   |
| Lenovo ThinkCentre                         | 10       | 2.96%   |
| HP Compaq                                  | 5        | 1.48%   |
| Gigabyte Z690                              | 5        | 1.48%   |
| Gigabyte H61M-S2PV                         | 5        | 1.48%   |
| Dell Precision                             | 5        | 1.48%   |
| HP ProDesk                                 | 4        | 1.18%   |
| Gigabyte X570                              | 4        | 1.18%   |
| Gigabyte G31M-ES2L                         | 4        | 1.18%   |
| Dell Vostro                                | 4        | 1.18%   |
| ASUS H110M-A                               | 4        | 1.18%   |
| Unknown                                    | 4        | 1.18%   |
| MSI MS-7592                                | 3        | 0.89%   |
| Lenovo V520-15IKL                          | 3        | 0.89%   |
| Gigabyte Z390                              | 3        | 0.89%   |
| Gigabyte H61M-S1                           | 3        | 0.89%   |
| Gigabyte B450M                             | 3        | 0.89%   |
| ASUS P8H61-M                               | 3        | 0.89%   |
| ASUS H110M-K                               | 3        | 0.89%   |
| MSI MS-7982                                | 2        | 0.59%   |
| Lenovo V530-15ICR                          | 2        | 0.59%   |
| Lenovo ThinkStation                        | 2        | 0.59%   |
| Intel DH77EB                               | 2        | 0.59%   |
| HP Z2                                      | 2        | 0.59%   |
| HP EliteDesk                               | 2        | 0.59%   |
| Gigabyte Z370                              | 2        | 0.59%   |
| Gigabyte P55-UD3L                          | 2        | 0.59%   |
| Gigabyte H97M-D3H                          | 2        | 0.59%   |
| Gigabyte H97-HD3                           | 2        | 0.59%   |
| Gigabyte H55M-D2H                          | 2        | 0.59%   |
| Gigabyte B560M                             | 2        | 0.59%   |
| Gigabyte B460HD3                           | 2        | 0.59%   |
| Supermicro X9DAi                           | 1        | 0.3%    |
| Shuttle SH87R                              | 1        | 0.3%    |
| Shenzhen Meigao Electronic Equipment Venus | 1        | 0.3%    |
| Pegatron Pro                               | 1        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 35       | 10.36%  |
| 2012 | 35       | 10.36%  |
| 2021 | 30       | 8.88%   |
| 2020 | 30       | 8.88%   |
| 2019 | 28       | 8.28%   |
| 2014 | 23       | 6.8%    |
| 2015 | 21       | 6.21%   |
| 2013 | 21       | 6.21%   |
| 2016 | 19       | 5.62%   |
| 2011 | 19       | 5.62%   |
| 2017 | 18       | 5.33%   |
| 2010 | 18       | 5.33%   |
| 2009 | 13       | 3.85%   |
| 2022 | 8        | 2.37%   |
| 2023 | 6        | 1.78%   |
| 2008 | 6        | 1.78%   |
| 2007 | 6        | 1.78%   |
| 2024 | 1        | 0.3%    |
| 2006 | 1        | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 338      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 332      | 98.22%  |
| Enabled  | 6        | 1.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 337      | 99.7%   |
| Yes  | 1        | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 92       | 26.06%  |
| 32.01-64.0  | 72       | 20.4%   |
| 8.01-16.0   | 60       | 17%     |
| 3.01-4.0    | 43       | 12.18%  |
| 4.01-8.0    | 40       | 11.33%  |
| 64.01-256.0 | 28       | 7.93%   |
| 1.01-2.0    | 10       | 2.83%   |
| 24.01-32.0  | 5        | 1.42%   |
| 2.01-3.0    | 2        | 0.57%   |
| Unknown     | 1        | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 119      | 31.15%  |
| 2.01-3.0   | 75       | 19.63%  |
| 4.01-8.0   | 65       | 17.02%  |
| 3.01-4.0   | 47       | 12.3%   |
| 8.01-16.0  | 38       | 9.95%   |
| 0.51-1.0   | 23       | 6.02%   |
| 0.01-0.5   | 7        | 1.83%   |
| 24.01-32.0 | 3        | 0.79%   |
| 32.01-64.0 | 2        | 0.52%   |
| 16.01-24.0 | 2        | 0.52%   |
| Unknown    | 1        | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 135      | 37.82%  |
| 2      | 105      | 29.41%  |
| 3      | 68       | 19.05%  |
| 4      | 24       | 6.72%   |
| 5      | 13       | 3.64%   |
| 8      | 3        | 0.84%   |
| 7      | 3        | 0.84%   |
| 6      | 3        | 0.84%   |
| 0      | 2        | 0.56%   |
| 10     | 1        | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 229      | 65.8%   |
| Yes       | 119      | 34.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 336      | 99.41%  |
| No        | 2        | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 201      | 58.6%   |
| Yes       | 142      | 41.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 245      | 71.01%  |
| Yes       | 100      | 28.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Israel  | 338      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Tel Aviv            | 127      | 33.87%  |
| Haifa               | 32       | 8.53%   |
| Ramat Gan           | 25       | 6.67%   |
| Jerusalem           | 16       | 4.27%   |
| Petaẖ Tiqwa       | 13       | 3.47%   |
| Petah Tikva         | 12       | 3.2%    |
| Rishon LeZiyyon     | 9        | 2.4%    |
| Holon               | 9        | 2.4%    |
| Netanya             | 8        | 2.13%   |
| Rehovot             | 7        | 1.87%   |
| Qiryat Ata          | 7        | 1.87%   |
| Ashdod              | 7        | 1.87%   |
| Rosh HaAyin         | 6        | 1.6%    |
| Herzliya            | 6        | 1.6%    |
| Kfar Saba           | 5        | 1.33%   |
| Rishon LeTsiyyon    | 4        | 1.07%   |
| Ramat HaSharon      | 4        | 1.07%   |
| Beersheba           | 4        | 1.07%   |
| Ashquelon           | 4        | 1.07%   |
| Ness Ziona          | 3        | 0.8%    |
| Nahariya            | 3        | 0.8%    |
| Hod HaSharon        | 3        | 0.8%    |
| Givatayim           | 3        | 0.8%    |
| Ge'a                | 3        | 0.8%    |
| Be'er Ya'aqov       | 3        | 0.8%    |
| Bat Yam             | 3        | 0.8%    |
| Yehud               | 2        | 0.53%   |
| Yaqum               | 2        | 0.53%   |
| Raanana             | 2        | 0.53%   |
| Pardes Hanna Karkur | 2        | 0.53%   |
| Lod                 | 2        | 0.53%   |
| Kiryat Gat          | 2        | 0.53%   |
| Bet Shemesh         | 2        | 0.53%   |
| Afula               | 2        | 0.53%   |
| Ziqim               | 1        | 0.27%   |
| Tiberias            | 1        | 0.27%   |
| Tel Mond            | 1        | 0.27%   |
| Shoham              | 1        | 0.27%   |
| Sderot              | 1        | 0.27%   |
| Ramla               | 1        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 141      | 256    | 22.31%  |
| Seagate                   | 87       | 141    | 13.77%  |
| Samsung Electronics       | 81       | 134    | 12.82%  |
| SanDisk                   | 52       | 65     | 8.23%   |
| Kingston                  | 43       | 56     | 6.8%    |
| Hitachi                   | 41       | 71     | 6.49%   |
| Toshiba                   | 26       | 31     | 4.11%   |
| Crucial                   | 20       | 35     | 3.16%   |
| Transcend                 | 18       | 24     | 2.85%   |
| Intel                     | 14       | 18     | 2.22%   |
| Corsair                   | 12       | 21     | 1.9%    |
| HGST                      | 9        | 11     | 1.42%   |
| Silicon Motion            | 6        | 6      | 0.95%   |
| China                     | 6        | 9      | 0.95%   |
| A-DATA Technology         | 6        | 7      | 0.95%   |
| XPG                       | 5        | 11     | 0.79%   |
| Phison                    | 5        | 6      | 0.79%   |
| Micron Technology         | 5        | 9      | 0.79%   |
| SK hynix                  | 4        | 4      | 0.63%   |
| Phison Electronics        | 4        | 5      | 0.63%   |
| Unknown                   | 3        | 5      | 0.47%   |
| StoreJet                  | 3        | 3      | 0.47%   |
| SPCC                      | 3        | 3      | 0.47%   |
| Micron/Crucial Technology | 3        | 3      | 0.47%   |
| KIOXIA-EXCERIA            | 3        | 4      | 0.47%   |
| ADATA Technology          | 3        | 3      | 0.47%   |
| XrayDisk                  | 2        | 3      | 0.32%   |
| PNY                       | 2        | 2      | 0.32%   |
| OCZ                       | 2        | 2      | 0.32%   |
| Netac                     | 2        | 2      | 0.32%   |
| Gigabyte Technology       | 2        | 2      | 0.32%   |
| Unknown                   | 2        | 2      | 0.32%   |
| Verbatim                  | 1        | 1      | 0.16%   |
| USB3.0                    | 1        | 1      | 0.16%   |
| UMIS                      | 1        | 2      | 0.16%   |
| TPH01204000GB             | 1        | 1      | 0.16%   |
| Plextor                   | 1        | 1      | 0.16%   |
| Patriot                   | 1        | 1      | 0.16%   |
| OCZ-VERTEX3               | 1        | 1      | 0.16%   |
| NGFF                      | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| SanDisk SSD PLUS 240GB                               | 15       | 2.04%   |
| Seagate ST500DM002-1BD142 500GB                      | 11       | 1.5%    |
| Hitachi HDS721050CLA362 500GB                        | 10       | 1.36%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 9        | 1.23%   |
| Kingston SA400S37240G 240GB SSD                      | 9        | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB                       | 7        | 0.95%   |
| Samsung SSD 860 EVO 500GB                            | 7        | 0.95%   |
| WDC WD20PURX-64P6ZY0 2TB                             | 6        | 0.82%   |
| Toshiba DT01ACA100 1TB                               | 6        | 0.82%   |
| Samsung SSD 850 EVO 250GB                            | 6        | 0.82%   |
| Kingston SV300S37A120G 120GB SSD                     | 6        | 0.82%   |
| WDC WD10EZEX-60WN4A0 1TB                             | 5        | 0.68%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 5        | 0.68%   |
| SanDisk SSD PLUS 480GB                               | 5        | 0.68%   |
| Samsung SSD 990 PRO 1TB                              | 5        | 0.68%   |
| Samsung NVMe SSD Drive 500GB                         | 5        | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 5        | 0.68%   |
| HGST HTS545050A7E680 500GB                           | 5        | 0.68%   |
| WDC WD1003FZEX-00MK2A0 1TB                           | 4        | 0.54%   |
| Toshiba DT01ACA050 500GB                             | 4        | 0.54%   |
| Seagate ST500DM002-1SB10A 500GB                      | 4        | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB                       | 4        | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB                       | 4        | 0.54%   |
| Seagate ST1000DM003-1SB102 1TB                       | 4        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                       | 4        | 0.54%   |
| Samsung SSD 860 QVO 1TB                              | 4        | 0.54%   |
| Samsung NVMe SSD Drive 1TB                           | 4        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 4        | 0.54%   |
| Kingston SA400S37480G 480GB SSD                      | 4        | 0.54%   |
| Kingston SA400S37120G 120GB SSD                      | 4        | 0.54%   |
| Crucial CT250MX500SSD1 250GB                         | 4        | 0.54%   |
| WDC WD5000AAKX-60U6AA0 500GB                         | 3        | 0.41%   |
| WDC WD5000AAKX-001CA0 500GB                          | 3        | 0.41%   |
| WDC WD3200AAKS-00L9A0 320GB                          | 3        | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 3        | 0.41%   |
| WDC WD20EZAZ-00GGJB0 2TB                             | 3        | 0.41%   |
| WDC WD2003FZEX-00Z4SA0 2TB                           | 3        | 0.41%   |
| WDC WD10EZEX-08M2NA0 1TB                             | 3        | 0.41%   |
| WDC WD10EARS-00Y5B1 1TB                              | 3        | 0.41%   |
| WDC WD10EADS-00L5B1 1TB                              | 3        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 132      | 240    | 43.42%  |
| Seagate             | 86       | 139    | 28.29%  |
| Hitachi             | 41       | 71     | 13.49%  |
| Toshiba             | 21       | 26     | 6.91%   |
| Samsung Electronics | 10       | 16     | 3.29%   |
| HGST                | 9        | 11     | 2.96%   |
| USB3.0              | 1        | 1      | 0.33%   |
| TPH01204000GB       | 1        | 1      | 0.33%   |
| Lenovo              | 1        | 1      | 0.33%   |
| IBM/Hitachi         | 1        | 1      | 0.33%   |
| Apple               | 1        | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 38       | 62     | 18.27%  |
| SanDisk             | 35       | 45     | 16.83%  |
| Kingston            | 35       | 43     | 16.83%  |
| Transcend           | 17       | 23     | 8.17%   |
| Crucial             | 14       | 27     | 6.73%   |
| Intel               | 11       | 13     | 5.29%   |
| Corsair             | 9        | 16     | 4.33%   |
| WDC                 | 7        | 7      | 3.37%   |
| China               | 6        | 9      | 2.88%   |
| A-DATA Technology   | 6        | 7      | 2.88%   |
| Micron Technology   | 5        | 9      | 2.4%    |
| KIOXIA-EXCERIA      | 3        | 3      | 1.44%   |
| Toshiba             | 2        | 2      | 0.96%   |
| SPCC                | 2        | 2      | 0.96%   |
| PNY                 | 2        | 2      | 0.96%   |
| OCZ                 | 2        | 2      | 0.96%   |
| Netac               | 2        | 2      | 0.96%   |
| XrayDisk            | 1        | 2      | 0.48%   |
| Verbatim            | 1        | 1      | 0.48%   |
| StoreJet            | 1        | 1      | 0.48%   |
| Seagate             | 1        | 1      | 0.48%   |
| Plextor             | 1        | 1      | 0.48%   |
| Patriot             | 1        | 1      | 0.48%   |
| OCZ-VERTEX3         | 1        | 1      | 0.48%   |
| NGFF                | 1        | 1      | 0.48%   |
| LS600               | 1        | 1      | 0.48%   |
| KingSpec            | 1        | 1      | 0.48%   |
| KingDian            | 1        | 2      | 0.48%   |
| Apacer              | 1        | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 231      | 508    | 44.51%  |
| SSD     | 172      | 288    | 33.14%  |
| NVMe    | 108      | 167    | 20.81%  |
| Unknown | 7        | 9      | 1.35%   |
| MMC     | 1        | 1      | 0.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 286      | 776    | 68.59%  |
| NVMe | 108      | 165    | 25.9%   |
| SAS  | 22       | 31     | 5.28%   |
| MMC  | 1        | 1      | 0.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 219      | 449    | 51.41%  |
| 0.51-1.0   | 106      | 160    | 24.88%  |
| 1.01-2.0   | 59       | 107    | 13.85%  |
| 3.01-4.0   | 16       | 39     | 3.76%   |
| 2.01-3.0   | 14       | 21     | 3.29%   |
| 4.01-10.0  | 10       | 14     | 2.35%   |
| 10.01-20.0 | 2        | 6      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 68       | 18.73%  |
| 101-250        | 67       | 18.46%  |
| 501-1000       | 54       | 14.88%  |
| 1001-2000      | 42       | 11.57%  |
| More than 3000 | 37       | 10.19%  |
| 1-20           | 31       | 8.54%   |
| 2001-3000      | 30       | 8.26%   |
| 21-50          | 14       | 3.86%   |
| 51-100         | 12       | 3.31%   |
| Unknown        | 8        | 2.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 143      | 38.24%  |
| 21-50          | 48       | 12.83%  |
| 101-250        | 40       | 10.7%   |
| 1001-2000      | 32       | 8.56%   |
| 251-500        | 28       | 7.49%   |
| 51-100         | 24       | 6.42%   |
| 501-1000       | 23       | 6.15%   |
| More than 3000 | 14       | 3.74%   |
| 2001-3000      | 14       | 3.74%   |
| Unknown        | 8        | 2.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| HGST HTS545050A7E680 500GB          | 5        | 7      | 8.33%   |
| WDC WD10EZEX-00BN5A0 1TB            | 2        | 2      | 3.33%   |
| WDC WD10EARS-00Y5B1 1TB             | 2        | 4      | 3.33%   |
| WDC WD10EADS-00L5B1 1TB             | 2        | 2      | 3.33%   |
| Hitachi HDS721050DLE630 500GB       | 2        | 2      | 3.33%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 3      | 3.33%   |
| WDC WDS240G1G0B-00RC30 240GB SSD    | 1        | 1      | 1.67%   |
| WDC WD5001AALS-00LWTA0 500GB        | 1        | 1      | 1.67%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 1.67%   |
| WDC WD5000AAKX-221CA1 500GB         | 1        | 1      | 1.67%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 1      | 1.67%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 1.67%   |
| WDC WD30PURX-64P6ZY0 3TB            | 1        | 1      | 1.67%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1        | 2      | 1.67%   |
| WDC WD2500AAJS-00VTA0 250GB         | 1        | 1      | 1.67%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 2      | 1.67%   |
| WDC WD1600JS-00SGB0 160GB           | 1        | 1      | 1.67%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 2      | 1.67%   |
| WDC WD10EZEX-00ZF5A0 1TB            | 1        | 1      | 1.67%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1      | 1.67%   |
| WDC WD10EAVS-32D7B1 1TB             | 1        | 1      | 1.67%   |
| WDC WD10EADS-00M2B0 1TB             | 1        | 1      | 1.67%   |
| WDC WD1001FALS-00J7B1 1TB           | 1        | 1      | 1.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 1.67%   |
| Seagate ST3750528AS 752GB           | 1        | 1      | 1.67%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 1.67%   |
| Seagate ST3250318AS 250GB           | 1        | 1      | 1.67%   |
| Seagate ST31000528AS 1TB            | 1        | 1      | 1.67%   |
| Seagate ST3000DM001-9YN166 3TB      | 1        | 1      | 1.67%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 3      | 1.67%   |
| Seagate ST1000LM014-SSHD-8GB        | 1        | 1      | 1.67%   |
| Seagate ST1000DM003-1SB102 1TB      | 1        | 1      | 1.67%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 1.67%   |
| SanDisk SSD PLUS 240GB              | 1        | 1      | 1.67%   |
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 1.67%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 2      | 1.67%   |
| Samsung Electronics HD103UJ 1TB     | 1        | 1      | 1.67%   |
| Intel SSDSC2CT120A3 120GB           | 1        | 1      | 1.67%   |
| Hitachi HUA723020ALA640 2TB         | 1        | 3      | 1.67%   |
| Hitachi HTS545050B9A300 500GB       | 1        | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 28     | 36.21%  |
| Hitachi             | 13       | 17     | 22.41%  |
| Seagate             | 10       | 12     | 17.24%  |
| HGST                | 6        | 8      | 10.34%  |
| Samsung Electronics | 3        | 4      | 5.17%   |
| Corsair             | 2        | 3      | 3.45%   |
| SanDisk             | 1        | 1      | 1.72%   |
| Intel               | 1        | 1      | 1.72%   |
| Gigabyte Technology | 1        | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 27     | 39.22%  |
| Hitachi             | 13       | 17     | 25.49%  |
| Seagate             | 10       | 12     | 19.61%  |
| HGST                | 6        | 8      | 11.76%  |
| Samsung Electronics | 2        | 3      | 3.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 67     | 85.42%  |
| SSD  | 5        | 6      | 10.42%  |
| NVMe | 2        | 2      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Toshiba MK3256GSY 320GB         | 1        | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 33.33%  |
| Hitachi HTS547550A9E384 500GB   | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |
| Hitachi             | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 193      | 575    | 50.92%  |
| Works    | 139      | 319    | 36.68%  |
| Malfunc  | 45       | 75     | 11.87%  |
| Failed   | 2        | 4      | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 281      | 57.7%   |
| AMD                          | 53       | 10.88%  |
| Samsung Electronics          | 43       | 8.83%   |
| SanDisk                      | 22       | 4.52%   |
| Kingston Technology Company  | 11       | 2.26%   |
| Phison Electronics           | 10       | 2.05%   |
| JMicron Technology           | 10       | 2.05%   |
| Micron/Crucial Technology    | 9        | 1.85%   |
| ASMedia Technology           | 8        | 1.64%   |
| Silicon Motion               | 7        | 1.44%   |
| Marvell Technology Group     | 7        | 1.44%   |
| ADATA Technology             | 7        | 1.44%   |
| SK hynix                     | 4        | 0.82%   |
| Toshiba America Info Systems | 3        | 0.62%   |
| Nvidia                       | 3        | 0.62%   |
| Transcend                    | 2        | 0.41%   |
| Realtek Semiconductor        | 2        | 0.41%   |
| VIA Technologies             | 1        | 0.21%   |
| Union Memory (Shenzhen)      | 1        | 0.21%   |
| KIOXIA                       | 1        | 0.21%   |
| Broadcom / LSI               | 1        | 0.21%   |
| Adaptec                      | 1        | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 35       | 6.06%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 5.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26       | 4.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23       | 3.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20       | 3.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 19       | 3.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 3.11%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 18       | 3.11%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15       | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15       | 2.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 2.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14       | 2.42%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 13       | 2.25%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10       | 1.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9        | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8        | 1.38%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 1.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8        | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 1.21%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 6        | 1.04%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 1.04%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 1.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.04%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 5        | 0.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 0.87%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 5        | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.69%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.69%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 0.69%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 0.69%   |
| AMD 600 Series Chipset SATA Controller                                                  | 4        | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 268      | 56.9%   |
| NVMe | 109      | 23.14%  |
| IDE  | 63       | 13.38%  |
| RAID | 28       | 5.94%   |
| SAS  | 3        | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 283      | 83.73%  |
| AMD    | 55       | 16.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz            | 9        | 2.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 2.62%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 7        | 2.03%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6        | 1.74%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 6        | 1.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.74%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 5        | 1.45%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 1.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 1.45%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4        | 1.16%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 1.16%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 4        | 1.16%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 1.16%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 1.16%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4        | 1.16%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 1.16%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 4        | 1.16%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.16%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.16%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.16%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.16%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.16%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 3        | 0.87%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 3        | 0.87%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.87%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.87%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 0.87%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 0.87%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 0.87%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 0.87%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.87%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3        | 0.87%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 0.87%   |
| Intel 12th Gen Core i7-12700K               | 3        | 0.87%   |
| Intel 12th Gen Core i5-12600K               | 3        | 0.87%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 3        | 0.87%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 0.87%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 3        | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 79       | 23.1%   |
| Intel Core i7           | 78       | 22.81%  |
| Other                   | 30       | 8.77%   |
| Intel Core i3           | 30       | 8.77%   |
| Intel Xeon              | 17       | 4.97%   |
| AMD Ryzen 5             | 17       | 4.97%   |
| Intel Pentium Dual-Core | 14       | 4.09%   |
| AMD Ryzen 7             | 14       | 4.09%   |
| Intel Pentium           | 12       | 3.51%   |
| AMD Ryzen 9             | 7        | 2.05%   |
| Intel Core 2 Duo        | 6        | 1.75%   |
| Intel Core i9           | 5        | 1.46%   |
| Intel Pentium Dual      | 4        | 1.17%   |
| Intel Celeron           | 3        | 0.88%   |
| AMD FX                  | 3        | 0.88%   |
| AMD A8                  | 3        | 0.88%   |
| Intel Pentium Gold      | 2        | 0.58%   |
| Intel Genuine           | 2        | 0.58%   |
| Intel Core 2 Quad       | 2        | 0.58%   |
| Intel Atom              | 2        | 0.58%   |
| AMD Ryzen 3             | 2        | 0.58%   |
| Intel Pentium 4         | 1        | 0.29%   |
| AMD Ryzen Threadripper  | 1        | 0.29%   |
| AMD Ryzen 3 PRO         | 1        | 0.29%   |
| AMD Phenom II X4        | 1        | 0.29%   |
| AMD Phenom              | 1        | 0.29%   |
| AMD GX                  | 1        | 0.29%   |
| AMD Athlon II X3        | 1        | 0.29%   |
| AMD Athlon 64 X2        | 1        | 0.29%   |
| AMD A6                  | 1        | 0.29%   |
| AMD A10                 | 1        | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 138      | 40.59%  |
| 2      | 70       | 20.59%  |
| 6      | 51       | 15%     |
| 8      | 39       | 11.47%  |
| 12     | 14       | 4.12%   |
| 16     | 8        | 2.35%   |
| 14     | 7        | 2.06%   |
| 10     | 5        | 1.47%   |
| 24     | 2        | 0.59%   |
| 3      | 2        | 0.59%   |
| 1      | 2        | 0.59%   |
| 44     | 1        | 0.29%   |
| 20     | 1        | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 334      | 98.82%  |
| 2      | 4        | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 195      | 57.02%  |
| 1      | 147      | 42.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 336      | 99.41%  |
| Unknown        | 2        | 0.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 134      | 37.02%  |
| 0x306c3    | 26       | 7.18%   |
| 0x1067a    | 18       | 4.97%   |
| 0x906e9    | 17       | 4.7%    |
| 0x306a9    | 16       | 4.42%   |
| 0x206a7    | 15       | 4.14%   |
| 0x506e3    | 14       | 3.87%   |
| 0x906ea    | 10       | 2.76%   |
| 0x90672    | 8        | 2.21%   |
| 0xa0671    | 6        | 1.66%   |
| 0x906ed    | 6        | 1.66%   |
| 0xa0655    | 5        | 1.38%   |
| 0xa0653    | 5        | 1.38%   |
| 0x306e4    | 5        | 1.38%   |
| 0x106e5    | 5        | 1.38%   |
| 0x08701021 | 5        | 1.38%   |
| 0x08108109 | 5        | 1.38%   |
| 0x6fd      | 4        | 1.1%    |
| 0x0a201009 | 3        | 0.83%   |
| 0x08701013 | 3        | 0.83%   |
| 0x0800820d | 3        | 0.83%   |
| 0x906ec    | 2        | 0.55%   |
| 0x806ec    | 2        | 0.55%   |
| 0x206c2    | 2        | 0.55%   |
| 0x20652    | 2        | 0.55%   |
| 0x10676    | 2        | 0.55%   |
| 0x0a601206 | 2        | 0.55%   |
| 0x0a201016 | 2        | 0.55%   |
| 0x06003106 | 2        | 0.55%   |
| 0x06001119 | 2        | 0.55%   |
| 0x010000c8 | 2        | 0.55%   |
| 0x906eb    | 1        | 0.28%   |
| 0x906c0    | 1        | 0.28%   |
| 0x90675    | 1        | 0.28%   |
| 0x806ea    | 1        | 0.28%   |
| 0x706a1    | 1        | 0.28%   |
| 0x506e0    | 1        | 0.28%   |
| 0x50657    | 1        | 0.28%   |
| 0x406f1    | 1        | 0.28%   |
| 0x406c4    | 1        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 65       | 19.06%  |
| Haswell          | 40       | 11.73%  |
| IvyBridge        | 30       | 8.8%    |
| Skylake          | 26       | 7.62%   |
| SandyBridge      | 23       | 6.74%   |
| Penryn           | 23       | 6.74%   |
| Unknown          | 21       | 6.16%   |
| CometLake        | 16       | 4.69%   |
| Zen 2            | 13       | 3.81%   |
| Zen 3            | 10       | 2.93%   |
| Alderlake Hybrid | 10       | 2.93%   |
| Zen+             | 9        | 2.64%   |
| Nehalem          | 8        | 2.35%   |
| Icelake          | 7        | 2.05%   |
| Zen              | 6        | 1.76%   |
| Broadwell        | 6        | 1.76%   |
| Westmere         | 5        | 1.47%   |
| Piledriver       | 4        | 1.17%   |
| Core             | 4        | 1.17%   |
| Steamroller      | 3        | 0.88%   |
| K10              | 3        | 0.88%   |
| Silvermont       | 2        | 0.59%   |
| Tremont          | 1        | 0.29%   |
| Puma             | 1        | 0.29%   |
| NetBurst         | 1        | 0.29%   |
| K8 Hammer        | 1        | 0.29%   |
| Goldmont plus    | 1        | 0.29%   |
| Bulldozer        | 1        | 0.29%   |
| Bonnell          | 1        | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 166      | 43.46%  |
| Intel             | 151      | 39.53%  |
| AMD               | 64       | 16.75%  |
| ASPEED Technology | 1        | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 29       | 7.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 19       | 4.85%   |
| Nvidia GK208B [GeForce GT 710]                                              | 12       | 3.06%   |
| Intel HD Graphics 530                                                       | 12       | 3.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 11       | 2.81%   |
| Intel HD Graphics 630                                                       | 11       | 2.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 2.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 2.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 2.55%   |
| Intel AlderLake-S GT1                                                       | 8        | 2.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 1.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 1.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.53%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 6        | 1.53%   |
| Nvidia GP107GL [Quadro P400]                                                | 5        | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.28%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.28%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 1.28%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.02%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.02%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 1.02%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.02%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 3        | 0.77%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.77%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.77%   |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 0.77%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.77%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 0.77%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 0.77%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 0.77%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 144      | 41.03%  |
| 1 x Intel       | 120      | 34.19%  |
| 1 x AMD         | 50       | 14.25%  |
| Intel + Nvidia  | 18       | 5.13%   |
| AMD + Nvidia    | 6        | 1.71%   |
| 2 x AMD         | 4        | 1.14%   |
| Intel + AMD     | 4        | 1.14%   |
| 2 x Intel       | 2        | 0.57%   |
| Other           | 1        | 0.28%   |
| 2 x Nvidia      | 1        | 0.28%   |
| Nvidia + ASPEED | 1        | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 213      | 61.03%  |
| Proprietary | 112      | 32.09%  |
| Unknown     | 24       | 6.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 177      | 49.44%  |
| 1.01-2.0   | 51       | 14.25%  |
| 7.01-8.0   | 31       | 8.66%   |
| 3.01-4.0   | 27       | 7.54%   |
| 0.51-1.0   | 27       | 7.54%   |
| 8.01-16.0  | 15       | 4.19%   |
| 0.01-0.5   | 14       | 3.91%   |
| 5.01-6.0   | 8        | 2.23%   |
| 2.01-3.0   | 5        | 1.4%    |
| 16.01-24.0 | 3        | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 88       | 24.38%  |
| Dell                 | 61       | 16.9%   |
| Philips              | 31       | 8.59%   |
| Goldstar             | 28       | 7.76%   |
| AOC                  | 19       | 5.26%   |
| Hewlett-Packard      | 13       | 3.6%    |
| Ancor Communications | 12       | 3.32%   |
| Lenovo               | 9        | 2.49%   |
| ASUSTek Computer     | 9        | 2.49%   |
| ViewSonic            | 7        | 1.94%   |
| BenQ                 | 7        | 1.94%   |
| Acer                 | 7        | 1.94%   |
| Unknown              | 5        | 1.39%   |
| Lenovo Group Limited | 4        | 1.11%   |
| Hyundai ImageQuest   | 4        | 1.11%   |
| SANYO                | 3        | 0.83%   |
| LG Electronics       | 3        | 0.83%   |
| Gigabyte Technology  | 3        | 0.83%   |
| Unknown              | 3        | 0.83%   |
| VIE                  | 2        | 0.55%   |
| Sony                 | 2        | 0.55%   |
| Sharp                | 2        | 0.55%   |
| Plain Tree Systems   | 2        | 0.55%   |
| Panasonic            | 2        | 0.55%   |
| NEX                  | 2        | 0.55%   |
| Iiyama               | 2        | 0.55%   |
| HKC                  | 2        | 0.55%   |
| Hitachi              | 2        | 0.55%   |
| Fujitsu Siemens      | 2        | 0.55%   |
| Eizo                 | 2        | 0.55%   |
| ___                  | 1        | 0.28%   |
| Xiaomi               | 1        | 0.28%   |
| Vestel Elektronik    | 1        | 0.28%   |
| Unknown (AAA)        | 1        | 0.28%   |
| Toshiba              | 1        | 0.28%   |
| SSD                  | 1        | 0.28%   |
| Sceptre Tech         | 1        | 0.28%   |
| Pioneer              | 1        | 0.28%   |
| Optoma               | 1        | 0.28%   |
| NXG                  | 1        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 6        | 1.56%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                      | 6        | 1.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 5        | 1.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch              | 5        | 1.3%    |
| Philips 222EL PHLC052 1920x1080 476x268mm 21.5-inch                  | 4        | 1.04%   |
| Hyundai ImageQuest L90D+ D-SUB HIQ91DA 1280x1024 376x301mm 19.0-inch | 4        | 1.04%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 4        | 1.04%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                    | 4        | 1.04%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch | 3        | 0.78%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch | 3        | 0.78%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch  | 3        | 0.78%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 3        | 0.78%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 3        | 0.78%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                     | 3        | 0.78%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 3        | 0.78%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 3        | 0.78%   |
| Unknown                                                              | 3        | 0.78%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                        | 2        | 0.52%   |
| SANYO LCD MONITOR SAN07BE 1280x1024 350x270mm 17.4-inch              | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch | 2        | 0.52%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch    | 2        | 0.52%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch    | 2        | 0.52%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch    | 2        | 0.52%   |
| Samsung Electronics S24E650 SAM0CC2 1920x1200 518x324mm 24.1-inch    | 2        | 0.52%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2        | 0.52%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch    | 2        | 0.52%   |
| Samsung Electronics LS27A80 SAM7184 3840x2160 597x336mm 27.0-inch    | 2        | 0.52%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch  | 2        | 0.52%   |
| Samsung Electronics LCD Monitor SMBX2450 1920x1080                   | 2        | 0.52%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 2        | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2        | 0.52%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                  | 2        | 0.52%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 2        | 0.52%   |
| Lenovo Group Limited LCD Monitor L24q-10                             | 2        | 0.52%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2        | 0.52%   |
| Hewlett-Packard 27cw HWP3195 1920x1080 598x336mm 27.0-inch           | 2        | 0.52%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                 | 2        | 0.52%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                               | 2        | 0.52%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2        | 0.52%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                    | 2        | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 196      | 56%     |
| 3840x2160 (4K)     | 28       | 8%      |
| 2560x1440 (QHD)    | 22       | 6.29%   |
| 1680x1050 (WSXGA+) | 22       | 6.29%   |
| 1280x1024 (SXGA)   | 22       | 6.29%   |
| 1920x1200 (WUXGA)  | 14       | 4%      |
| Unknown            | 8        | 2.29%   |
| 1440x900 (WXGA+)   | 7        | 2%      |
| 3440x1440          | 5        | 1.43%   |
| 2560x1080          | 5        | 1.43%   |
| 3840x1080          | 3        | 0.86%   |
| 1600x900 (HD+)     | 3        | 0.86%   |
| 1920x540           | 2        | 0.57%   |
| 1366x768 (WXGA)    | 2        | 0.57%   |
| 1360x768           | 2        | 0.57%   |
| 5360x1440          | 1        | 0.29%   |
| 5120x1440          | 1        | 0.29%   |
| 4480x1440          | 1        | 0.29%   |
| 3840x1200          | 1        | 0.29%   |
| 3520x1080          | 1        | 0.29%   |
| 2560x1600          | 1        | 0.29%   |
| 2288x1287          | 1        | 0.29%   |
| 1280x768           | 1        | 0.29%   |
| 1024x768 (XGA)     | 1        | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 58       | 16.2%   |
| 21      | 56       | 15.64%  |
| 27      | 54       | 15.08%  |
| 23      | 51       | 14.25%  |
| Unknown | 31       | 8.66%   |
| 22      | 18       | 5.03%   |
| 19      | 15       | 4.19%   |
| 31      | 11       | 3.07%   |
| 17      | 9        | 2.51%   |
| 34      | 8        | 2.23%   |
| 20      | 7        | 1.96%   |
| 72      | 5        | 1.4%    |
| 84      | 4        | 1.12%   |
| 33      | 4        | 1.12%   |
| 60      | 3        | 0.84%   |
| 40      | 3        | 0.84%   |
| 32      | 3        | 0.84%   |
| 18      | 3        | 0.84%   |
| 48      | 2        | 0.56%   |
| 26      | 2        | 0.56%   |
| 142     | 1        | 0.28%   |
| 65      | 1        | 0.28%   |
| 54      | 1        | 0.28%   |
| 52      | 1        | 0.28%   |
| 49      | 1        | 0.28%   |
| 42      | 1        | 0.28%   |
| 37      | 1        | 0.28%   |
| 29      | 1        | 0.28%   |
| 25      | 1        | 0.28%   |
| 16      | 1        | 0.28%   |
| 15      | 1        | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 153      | 43.97%  |
| 401-500        | 86       | 24.71%  |
| Unknown        | 31       | 8.91%   |
| 601-700        | 17       | 4.89%   |
| 701-800        | 15       | 4.31%   |
| 351-400        | 11       | 3.16%   |
| 301-350        | 11       | 3.16%   |
| 1501-2000      | 9        | 2.59%   |
| 1001-1500      | 9        | 2.59%   |
| 801-900        | 4        | 1.15%   |
| More than 2000 | 1        | 0.29%   |
| 901-1000       | 1        | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 223      | 66.77%  |
| 16/10   | 48       | 14.37%  |
| Unknown | 30       | 8.98%   |
| 5/4     | 18       | 5.39%   |
| 21/9    | 8        | 2.4%    |
| 4/3     | 3        | 0.9%    |
| 32/9    | 1        | 0.3%    |
| 3/2     | 1        | 0.3%    |
| 1.96    | 1        | 0.3%    |
| 1.00    | 1        | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 148      | 42.29%  |
| 301-350        | 56       | 16%     |
| 151-200        | 31       | 8.86%   |
| Unknown        | 31       | 8.86%   |
| 351-500        | 27       | 7.71%   |
| 251-300        | 21       | 6%      |
| More than 1000 | 17       | 4.86%   |
| 141-150        | 10       | 2.86%   |
| 501-1000       | 7        | 2%      |
| 131-140        | 1        | 0.29%   |
| 101-110        | 1        | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 206      | 61.13%  |
| 101-120 | 71       | 21.07%  |
| Unknown | 31       | 9.2%    |
| 1-50    | 14       | 4.15%   |
| 121-160 | 10       | 2.97%   |
| 161-240 | 5        | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 264      | 76.3%   |
| 2     | 56       | 16.18%  |
| 0     | 20       | 5.78%   |
| 3     | 5        | 1.45%   |
| 4     | 1        | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 212      | 44.07%  |
| Intel                           | 149      | 30.98%  |
| Qualcomm Atheros                | 29       | 6.03%   |
| Ralink Technology               | 18       | 3.74%   |
| TP-Link                         | 14       | 2.91%   |
| Edimax Technology               | 7        | 1.46%   |
| Broadcom                        | 5        | 1.04%   |
| Xiaomi                          | 4        | 0.83%   |
| MediaTek                        | 4        | 0.83%   |
| Ralink                          | 3        | 0.62%   |
| D-Link                          | 3        | 0.62%   |
| ASIX Electronics                | 3        | 0.62%   |
| STMicroelectronics              | 2        | 0.42%   |
| Samsung Electronics             | 2        | 0.42%   |
| Qualcomm Atheros Communications | 2        | 0.42%   |
| Nvidia                          | 2        | 0.42%   |
| Microsoft                       | 2        | 0.42%   |
| Marvell Technology Group        | 2        | 0.42%   |
| Google                          | 2        | 0.42%   |
| Broadcom Limited                | 2        | 0.42%   |
| Aquantia                        | 2        | 0.42%   |
| VIA Technologies                | 1        | 0.21%   |
| U.S. Robotics                   | 1        | 0.21%   |
| U-Blox                          | 1        | 0.21%   |
| Texas Instruments               | 1        | 0.21%   |
| ROCCAT                          | 1        | 0.21%   |
| Mellanox Technologies           | 1        | 0.21%   |
| Huawei Technologies             | 1        | 0.21%   |
| GDMicroelectronics              | 1        | 0.21%   |
| DisplayLink                     | 1        | 0.21%   |
| Davicom Semiconductor           | 1        | 0.21%   |
| BUFFALO                         | 1        | 0.21%   |
| Accton Technology               | 1        | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 161      | 29.11%  |
| Realtek RTL8125 2.5GbE Controller                                      | 25       | 4.52%   |
| Intel Ethernet Connection (2) I219-V                                   | 22       | 3.98%   |
| Intel I211 Gigabit Network Connection                                  | 16       | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14       | 2.53%   |
| Intel Wi-Fi 6 AX200                                                    | 13       | 2.35%   |
| Intel Ethernet Connection (7) I219-V                                   | 10       | 1.81%   |
| Intel Ethernet Connection I217-LM                                      | 9        | 1.63%   |
| Realtek 802.11ac NIC                                                   | 8        | 1.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8        | 1.45%   |
| Intel Ethernet Controller I225-V                                       | 8        | 1.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 7        | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 6        | 1.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 6        | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5        | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 0.9%    |
| Ralink MT7601U Wireless Adapter                                        | 5        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5        | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                  | 5        | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                                  | 5        | 0.9%    |
| Intel Ethernet Connection (14) I219-V                                  | 5        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4        | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 4        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4        | 0.72%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4        | 0.72%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 0.72%   |
| Intel Ethernet Connection I217-V                                       | 4        | 0.72%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 0.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3        | 0.54%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 3        | 0.54%   |
| TP-Link Archer T4U ver.3                                               | 3        | 0.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 3        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.54%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 3        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 0.54%   |
| Edimax RTL8192S WLAN Adapter                                           | 3        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 48       | 30.77%  |
| Realtek Semiconductor           | 37       | 23.72%  |
| Ralink Technology               | 18       | 11.54%  |
| TP-Link                         | 14       | 8.97%   |
| Qualcomm Atheros                | 13       | 8.33%   |
| Edimax Technology               | 7        | 4.49%   |
| MediaTek                        | 4        | 2.56%   |
| Broadcom                        | 4        | 2.56%   |
| Ralink                          | 3        | 1.92%   |
| D-Link                          | 3        | 1.92%   |
| Qualcomm Atheros Communications | 2        | 1.28%   |
| Microsoft                       | 2        | 1.28%   |
| BUFFALO                         | 1        | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13       | 8.07%   |
| Realtek 802.11ac NIC                                           | 8        | 4.97%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 8        | 4.97%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 7        | 4.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 6        | 3.73%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6        | 3.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5        | 3.11%   |
| Ralink MT7601U Wireless Adapter                                | 5        | 3.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 2.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4        | 2.48%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4        | 2.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3        | 1.86%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 3        | 1.86%   |
| TP-Link Archer T4U ver.3                                       | 3        | 1.86%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 3        | 1.86%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 3        | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 1.86%   |
| Edimax RTL8192S WLAN Adapter                                   | 3        | 1.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 1.24%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2        | 1.24%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2        | 1.24%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 2        | 1.24%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2        | 1.24%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 1.24%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 1.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2        | 1.24%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2        | 1.24%   |
| Microsoft Xbox 360 Wireless Adapter                            | 2        | 1.24%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 2        | 1.24%   |
| Intel Wireless 8265 / 8275                                     | 2        | 1.24%   |
| Intel Wireless 3165                                            | 2        | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 1.24%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2        | 1.24%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]       | 2        | 1.24%   |
| Edimax AC600 USB                                               | 2        | 1.24%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2        | 1.24%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1        | 0.62%   |
| TP-Link 802.11n NIC                                            | 1        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 197      | 53.53%  |
| Intel                    | 127      | 34.51%  |
| Qualcomm Atheros         | 18       | 4.89%   |
| Xiaomi                   | 4        | 1.09%   |
| ASIX Electronics         | 3        | 0.82%   |
| Samsung Electronics      | 2        | 0.54%   |
| Nvidia                   | 2        | 0.54%   |
| Marvell Technology Group | 2        | 0.54%   |
| Google                   | 2        | 0.54%   |
| Broadcom Limited         | 2        | 0.54%   |
| Aquantia                 | 2        | 0.54%   |
| VIA Technologies         | 1        | 0.27%   |
| Mellanox Technologies    | 1        | 0.27%   |
| Huawei Technologies      | 1        | 0.27%   |
| DisplayLink              | 1        | 0.27%   |
| Davicom Semiconductor    | 1        | 0.27%   |
| Broadcom                 | 1        | 0.27%   |
| Accton Technology        | 1        | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 161      | 41.82%  |
| Realtek RTL8125 2.5GbE Controller                                      | 25       | 6.49%   |
| Intel Ethernet Connection (2) I219-V                                   | 22       | 5.71%   |
| Intel I211 Gigabit Network Connection                                  | 16       | 4.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14       | 3.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 10       | 2.6%    |
| Intel Ethernet Connection I217-LM                                      | 9        | 2.34%   |
| Intel Ethernet Controller I225-V                                       | 8        | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 1.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5        | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                                  | 5        | 1.3%    |
| Intel Ethernet Connection (5) I219-LM                                  | 5        | 1.3%    |
| Intel Ethernet Connection (14) I219-V                                  | 5        | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 1.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4        | 1.04%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 1.04%   |
| Intel Ethernet Connection I217-V                                       | 4        | 1.04%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 0.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 2        | 0.52%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 0.52%   |
| Intel Ethernet Controller I226-V                                       | 2        | 0.52%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.52%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.52%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.52%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.52%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.26%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.26%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 0.26%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 336      | 69.28%  |
| WiFi     | 142      | 29.28%  |
| Modem    | 6        | 1.24%   |
| Unknown  | 1        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 276      | 77.97%  |
| WiFi     | 78       | 22.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 243      | 71.26%  |
| 2     | 80       | 23.46%  |
| 3     | 15       | 4.4%    |
| 0     | 2        | 0.59%   |
| 5     | 1        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 273      | 77.12%  |
| Yes  | 81       | 22.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 41       | 40.2%   |
| Cambridge Silicon Radio         | 30       | 29.41%  |
| Realtek Semiconductor           | 9        | 8.82%   |
| Qualcomm Atheros Communications | 5        | 4.9%    |
| IMC Networks                    | 4        | 3.92%   |
| ASUSTek Computer                | 3        | 2.94%   |
| TP-Link                         | 2        | 1.96%   |
| Broadcom                        | 2        | 1.96%   |
| Realtek                         | 1        | 0.98%   |
| MediaTek                        | 1        | 0.98%   |
| Lite-On Technology              | 1        | 0.98%   |
| Foxconn / Hon Hai               | 1        | 0.98%   |
| Apple                           | 1        | 0.98%   |
| Unknown                         | 1        | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30       | 29.41%  |
| Intel AX200 Bluetooth                               | 11       | 10.78%  |
| Realtek Bluetooth Radio                             | 9        | 8.82%   |
| Intel Bluetooth wireless interface                  | 7        | 6.86%   |
| Intel AX210 Bluetooth                               | 5        | 4.9%    |
| Intel AX201 Bluetooth                               | 5        | 4.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 3.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 3.92%   |
| Intel AX211 Bluetooth                               | 3        | 2.94%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2        | 1.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 1.96%   |
| IMC Networks Wireless_Device                        | 2        | 1.96%   |
| ASUS Bluetooth Adapter                              | 2        | 1.96%   |
| Realtek Bluetooth Radio                             | 1        | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 0.98%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.98%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 0.98%   |
| MediaTek Wireless_Device                            | 1        | 0.98%   |
| Lite-On Bluetooth Device                            | 1        | 0.98%   |
| IMC Networks Bluetooth Radio                        | 1        | 0.98%   |
| IMC Networks Bluetooth Device                       | 1        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 0.98%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 0.98%   |
| ASUS BCM20702A0                                     | 1        | 0.98%   |
| Apple Bluetooth Host Controller                     | 1        | 0.98%   |
| Unknown                                             | 1        | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 272      | 45.03%  |
| Nvidia                                       | 160      | 26.49%  |
| AMD                                          | 82       | 13.58%  |
| C-Media Electronics                          | 12       | 1.99%   |
| Logitech                                     | 9        | 1.49%   |
| Creative Labs                                | 8        | 1.32%   |
| XMOS                                         | 5        | 0.83%   |
| Texas Instruments                            | 4        | 0.66%   |
| JMTek                                        | 4        | 0.66%   |
| Focusrite-Novation                           | 4        | 0.66%   |
| Creative Technology                          | 4        | 0.66%   |
| SteelSeries ApS                              | 3        | 0.5%    |
| Razer USA                                    | 3        | 0.5%    |
| Micro Star International                     | 3        | 0.5%    |
| Kingston Technology                          | 3        | 0.5%    |
| GN Netcom                                    | 3        | 0.5%    |
| Generalplus Technology                       | 3        | 0.5%    |
| Cambridge Silicon Radio                      | 3        | 0.5%    |
| Unknown                                      | 3        | 0.5%    |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.17%   |
| VIA Technologies                             | 1        | 0.17%   |
| Samson Technologies                          | 1        | 0.17%   |
| Realtek Semiconductor                        | 1        | 0.17%   |
| Plantronics                                  | 1        | 0.17%   |
| Microsoft                                    | 1        | 0.17%   |
| Meridian                                     | 1        | 0.17%   |
| M-Audio                                      | 1        | 0.17%   |
| Jieli Technology                             | 1        | 0.17%   |
| iCreate Technologies                         | 1        | 0.17%   |
| Hewlett-Packard                              | 1        | 0.17%   |
| Giga-Byte Technology                         | 1        | 0.17%   |
| FIFINE Microphones                           | 1        | 0.17%   |
| EGO SYStems                                  | 1        | 0.17%   |
| ASUSTek Computer                             | 1        | 0.17%   |
| Areson Technology                            | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 36       | 5.35%   |
| Intel 200 Series PCH HD Audio                                              | 35       | 5.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 26       | 3.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26       | 3.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24       | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 21       | 3.12%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21       | 3.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20       | 2.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 18       | 2.67%   |
| Intel Alder Lake-S HD Audio Controller                                     | 17       | 2.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 13       | 1.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 13       | 1.93%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 12       | 1.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 1.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 1.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.34%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 1.34%   |
| Nvidia High Definition Audio Controller                                    | 8        | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8        | 1.19%   |
| Intel Comet Lake PCH-V cAVS                                                | 8        | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8        | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 1.19%   |
| Nvidia GF119 HDMI Audio Controller                                         | 7        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                              | 7        | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 6        | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 0.74%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5        | 0.74%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 0.74%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 52       | 24.88%  |
| Unknown             | 29       | 13.88%  |
| Corsair             | 25       | 11.96%  |
| G.Skill             | 23       | 11%     |
| Crucial             | 19       | 9.09%   |
| SK hynix            | 18       | 8.61%   |
| Samsung Electronics | 12       | 5.74%   |
| Micron Technology   | 9        | 4.31%   |
| Ramaxel Technology  | 7        | 3.35%   |
| Transcend           | 3        | 1.44%   |
| Team                | 3        | 1.44%   |
| A-DATA Technology   | 3        | 1.44%   |
| GeIL                | 2        | 0.96%   |
| Unknown (09D5)      | 1        | 0.48%   |
| Patriot             | 1        | 0.48%   |
| KETECH              | 1        | 0.48%   |
| Ankowall            | 1        | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                        | 4        | 1.72%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s       | 4        | 1.72%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 3        | 1.29%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s             | 3        | 1.29%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 3        | 1.29%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 3        | 1.29%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s       | 3        | 1.29%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s      | 3        | 1.29%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 2        | 0.86%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 2        | 0.86%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2        | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 2        | 0.86%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 2        | 0.86%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 2        | 0.86%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s       | 2        | 0.86%   |
| SK hynix RAM HMA851U6JJR6N-VK 4GB DIMM DDR4 2667MT/s       | 2        | 0.86%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 2        | 0.86%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s        | 2        | 0.86%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s          | 2        | 0.86%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s        | 2        | 0.86%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s      | 2        | 0.86%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 2        | 0.86%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s      | 2        | 0.86%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s      | 2        | 0.86%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s         | 2        | 0.86%   |
| Crucial RAM CT16G4DFD832A.C16FP 16384MB DIMM DDR4 3200MT/s | 2        | 0.86%   |
| Crucial RAM BL8G32C16U4B.M8FE1 8GB DIMM DDR4 3600MT/s      | 2        | 0.86%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s     | 2        | 0.86%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3466MT/s      | 2        | 0.86%   |
| A-DATA RAM DDR4 3600 8GB DIMM DDR4 3800MT/s                | 2        | 0.86%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 0.43%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                       | 1        | 0.43%   |
| Unknown RAM Module 8GB DIMM                                | 1        | 0.43%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1        | 0.43%   |
| Unknown RAM Module 8192MB DIMM 800MT/s                     | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                   | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM 667MT/s                        | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM 400MT/s                        | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 0.43%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 1        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 105      | 56.15%  |
| DDR3    | 41       | 21.93%  |
| Unknown | 22       | 11.76%  |
| DDR2    | 7        | 3.74%   |
| SDRAM   | 5        | 2.67%   |
| DDR5    | 5        | 2.67%   |
| DRAM    | 1        | 0.53%   |
| DDR     | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 182      | 97.85%  |
| SODIMM | 4        | 2.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 56       | 27.05%  |
| 4096  | 56       | 27.05%  |
| 16384 | 54       | 26.09%  |
| 2048  | 22       | 10.63%  |
| 32768 | 12       | 5.8%    |
| 1024  | 7        | 3.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 29       | 13.68%  |
| 3200    | 24       | 11.32%  |
| 2400    | 16       | 7.55%   |
| 1333    | 16       | 7.55%   |
| 2133    | 14       | 6.6%    |
| 800     | 14       | 6.6%    |
| 3600    | 13       | 6.13%   |
| 2667    | 10       | 4.72%   |
| 3800    | 7        | 3.3%    |
| 3466    | 5        | 2.36%   |
| 667     | 5        | 2.36%   |
| Unknown | 5        | 2.36%   |
| 6000    | 4        | 1.89%   |
| 2933    | 4        | 1.89%   |
| 2666    | 4        | 1.89%   |
| 1867    | 4        | 1.89%   |
| 1866    | 3        | 1.42%   |
| 1800    | 3        | 1.42%   |
| 3933    | 2        | 0.94%   |
| 3666    | 2        | 0.94%   |
| 3534    | 2        | 0.94%   |
| 3266    | 2        | 0.94%   |
| 3151    | 2        | 0.94%   |
| 2800    | 2        | 0.94%   |
| 2000    | 2        | 0.94%   |
| 400     | 2        | 0.94%   |
| 49926   | 1        | 0.47%   |
| 5900    | 1        | 0.47%   |
| 5600    | 1        | 0.47%   |
| 4800    | 1        | 0.47%   |
| 4400    | 1        | 0.47%   |
| 4000    | 1        | 0.47%   |
| 3733    | 1        | 0.47%   |
| 3467    | 1        | 0.47%   |
| 3334    | 1        | 0.47%   |
| 3066    | 1        | 0.47%   |
| 3000    | 1        | 0.47%   |
| 2733    | 1        | 0.47%   |
| 2134    | 1        | 0.47%   |
| 1648    | 1        | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 11       | 55%     |
| Samsung Electronics   | 3        | 15%     |
| Canon                 | 2        | 10%     |
| Seiko Epson           | 1        | 5%      |
| Lexmark International | 1        | 5%      |
| GODEX INTERNATIONAL   | 1        | 5%      |
| Brother Industries    | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP DeskJet 4670 series        | 3        | 15%     |
| Samsung M2070 Series          | 2        | 10%     |
| HP Printing Support           | 2        | 10%     |
| HP Officejet 4500 G510g-m     | 2        | 10%     |
| Seiko Epson L3150 Series      | 1        | 5%      |
| Samsung SCX-4623 Series       | 1        | 5%      |
| Lexmark International CS417dn | 1        | 5%      |
| HP Smart Tank 510 series      | 1        | 5%      |
| HP OfficeJet 5600 (USBHUB)    | 1        | 5%      |
| HP HP LaserJet M14-M17        | 1        | 5%      |
| HP Deskjet 4640 series        | 1        | 5%      |
| GODEX INTERNATIONAL DT2       | 1        | 5%      |
| Canon TR7500 series           | 1        | 5%      |
| Canon PIXMA MX490 Series      | 1        | 5%      |
| Brother MFC-J497DW            | 1        | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 100 | 2        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 31       | 31.96%  |
| Microsoft                     | 27       | 27.84%  |
| Generalplus Technology        | 7        | 7.22%   |
| Microdia                      | 5        | 5.15%   |
| Samsung Electronics           | 4        | 4.12%   |
| Sunplus Innovation Technology | 3        | 3.09%   |
| Realtek Semiconductor         | 3        | 3.09%   |
| Apple                         | 3        | 3.09%   |
| IMC Networks                  | 2        | 2.06%   |
| Xiaomi                        | 1        | 1.03%   |
| WaveRider Communications      | 1        | 1.03%   |
| Quanta                        | 1        | 1.03%   |
| Lenovo                        | 1        | 1.03%   |
| KYE Systems (Mouse Systems)   | 1        | 1.03%   |
| Jieli Technology              | 1        | 1.03%   |
| Hewlett-Packard               | 1        | 1.03%   |
| GEMBIRD                       | 1        | 1.03%   |
| Chicony Electronics           | 1        | 1.03%   |
| Aveo Technology               | 1        | 1.03%   |
| Allwinner Technology          | 1        | 1.03%   |
| Alcor Micro                   | 1        | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                           | 18       | 18.37%  |
| Logitech Webcam C270                                | 6        | 6.12%   |
| Generalplus GENERAL WEBCAM                          | 6        | 6.12%   |
| Logitech HD Pro Webcam C920                         | 5        | 5.1%    |
| Samsung Galaxy series, misc. (MTP mode)             | 4        | 4.08%   |
| Logitech Webcam C310                                | 4        | 4.08%   |
| Logitech C922 Pro Stream Webcam                     | 3        | 3.06%   |
| Realtek USB Camera                                  | 2        | 2.04%   |
| Microsoft MicrosoftÂ LifeCam Studio                | 2        | 2.04%   |
| Microsoft LifeCam VX-800                            | 2        | 2.04%   |
| Microdia Integrated Camera                          | 2        | 2.04%   |
| Logitech Webcam C930e                               | 2        | 2.04%   |
| Logitech Logitech Webcam C925e                      | 2        | 2.04%   |
| Logitech HD Webcam C615                             | 2        | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 2        | 2.04%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                  | 1        | 1.02%   |
| WaveRider USB Live camera                           | 1        | 1.02%   |
| Sunplus NexiGo N950P 4K Webcam                      | 1        | 1.02%   |
| Sunplus MTD Camera                                  | 1        | 1.02%   |
| Sunplus Depstech webcam                             | 1        | 1.02%   |
| Realtek Web Camera                                  | 1        | 1.02%   |
| Quanta Astro HD Camera                              | 1        | 1.02%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 1.02%   |
| Microsoft MicrosoftÂ LifeCam Cinema                | 1        | 1.02%   |
| Microsoft LifeCam VX-500 [1357]                     | 1        | 1.02%   |
| Microsoft LifeCam HD-5000                           | 1        | 1.02%   |
| Microsoft LifeCam Cinema                            | 1        | 1.02%   |
| Microdia USB 2.0 Camera                             | 1        | 1.02%   |
| Microdia Streaming Camera W8GS                      | 1        | 1.02%   |
| Microdia AUKEY-W1                                   | 1        | 1.02%   |
| Logitech Webcam C920-C                              | 1        | 1.02%   |
| Logitech Webcam C170                                | 1        | 1.02%   |
| Logitech QuickCam E 3500                            | 1        | 1.02%   |
| Logitech Mic (Fusion)                               | 1        | 1.02%   |
| Logitech HD Webcam C525                             | 1        | 1.02%   |
| Logitech C930c                                      | 1        | 1.02%   |
| Logitech BRIO Ultra HD Webcam                       | 1        | 1.02%   |
| Logitech BRIO 4K Stream Edition                     | 1        | 1.02%   |
| Lenovo Lenovo 500 RGB Camera                        | 1        | 1.02%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera          | 1        | 1.02%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 288      | 82.76%  |
| 1     | 50       | 14.37%  |
| 2     | 8        | 2.3%    |
| 6     | 1        | 0.29%   |
| 3     | 1        | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 28       | 41.18%  |
| Net/wireless             | 22       | 32.35%  |
| Communication controller | 9        | 13.24%  |
| Unassigned class         | 5        | 7.35%   |
| Camera                   | 3        | 4.41%   |
| Bluetooth                | 1        | 1.47%   |

